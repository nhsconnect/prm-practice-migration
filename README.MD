# GP Clinical System Migration Guide

This guide aims to help Practices, GP IT delivery partners (such as a Commissioning Support Unit) and Clinical Commissioning Groups (CCGs) plan and prepare their migration from one principal clinical system to another. 

You can find the guide at https://nhsconnect.github.io/prm-practice-migration

## Content
- [Editing this guide](#editing-this-guide)
  - [Links and Permalinks](#link-and-permalinks)
    - [How to format permalinks/links throughout the guide](#how-to-format-permalinkslinks-throughout-the-guide)
    - [Linking to a particular section within the guide](#linking-to-a-particular-section-within-the-guide)
  - [Guide Navigation](#guide-navigation)
    - [Change the menu/footer navigation](#change-the-menufooter-navigation)
    - [Change the sidebar items in the guide pages](#change-the-sidebar-items-in-the-guide-pages)
  - [Adding breadcrumbs to a page and previous/next links](#adding-breadcrumbs-to-a-page-and-previousnext-links)
    - [Breadcrumbs](#breadcrumbs)
    - [Previous / Next links](#previous--next-links)
  - [Custom Parts/Sections of the Guide](#custom-partssections-of-the-guide)
    - [Adding a CTA button](#adding-a-cta-button)
    - [Adding an action link](#adding-an-action-link)
    - [Adding emphasis to page content with Insets](#adding-emphasis-to-page-content-with-insets)
    - [Steps/Timeline Component](#stepstimeline-component)
      - [Adding steps/events timeline to a page](#adding-stepsevents-timeline-to-a-page)
      - [Ordering the steps/events](#ordering-the-stepsevents)
      - [Displaying the steps in a page](#displaying-the-steps-in-a-page)
 

## Editing this guide 
The guide's content is rendered statically by Jekyll. We have used, applied and adapted certain components from the NHS Design System to be able to use and reuse throughout the pages. To be able to change them, we have done our best to document them below.

### Link and Permalinks

#### How to format permalinks/links throughout the guide
As the guide is currently hosted on Github Pages, if the content you're editing is markdown, make sure to include the leading `/prm-practice-migration/` prefix to the links when linking from Markdown.

However, when setting content variables for Jekyll pages, that is not necessary, as Jekyll is aware of this prefix.

When adding permalinks in page header to other pages, either for breadcrumbs or for next/previous page follow these rules:
 - *DO* include the leading forward slash
 - *DO NOT* include the trailing forward slash

Example:

| Correctly formatting | Incorrect formatting |
| -------------------- | -------------------- |
| `/guide/kick-off`    | `/guide/kick-off/`   |
|                      | `guide/kick-off`     |

#### Linking to a particular section within the guide
There is often a need to link to a particular section of the guide, this may be to a point half way down on a long page. To do this you can use bookmarks. Every Heading you create will auto generate a bookmark that you can link to

For example, if you have a heading such as:

```### Notification of 3rd parties and links```

Will auto generate a heading with an ID as follows:

```<h2 id="notification-of-3rd-parties-and-links">Notification of 3rd parties and links</h2>```

You can also define a custom ID to guarrantee the integrity of any links should the heading copy be changed. You do this using the following syntax

```### Notification of 3rd parties and links  {#notify-3rd-parties}```

Which will auto generate a heading with an ID as follows:

```<h2 id="#notify-3rd-parties">Notification of 3rd parties and links</h2>```


### Guide navigation

#### Change the menu/footer navigation
To add, edit or reorder the menu items at the top of the page, edit the file `_data/menu_navigation.yml` page. 


#### Change the sidebar items in the guide pages
Similar to the menu navigtion, to add, edit or reorder the sidebar items at side of the page when a `page_with_sidebar` layout is use on a page, edit the file `_data/sidebar_navigation.yml` page. To add sub items in the hierarchy, include a subitems attribute and repeat the title/url structure.

```yml
sidebar_items:
  - title: Sidebar item 1 with subitems
    url: /sidebar-item-url-1
    subitems:
        - title: Subitem title 1
          url: /sidebar-sub-item-url-1
        - title: Subitem title 2
          url: /sidebar-sub-item-url-2
  - title: Sidebar item 2
    url: /sidebar-item-url-2
```

### Adding breadcrumbs to a page and previous/next links
Before adding links to a page, make sure to check the above guidance on permalinks.

To set breadcrumbs and previous/next links, pages can have certain variables defined which will allow the breadcrumbs and previous/next modules to display correctly.

#### Breadcrumbs
By default, the top link for breadcrumbs will be "Home". This can be changed in the `_includes/header.html` page by changing the `home` parameter to false.

For a page to correctly display it's parent, the `breadcrumbparent` parameter has to be set in the header of that page.

```markdown
breadcrumbparent: /guide
```

#### Previous / Next links
For a page to correctly display it's previous and next links, the `previouspage` and `nextpage` parameters have to be set in the header of that page.

```markdown
nextpage: /guide/technical-survey
previouspage: /guide/get-started
```

### Custom Parts/Sections of the Guide
Some content can be displayed in certain format for emphasis. We have reused and adapted elements from the NHS Design System for this.

### Adding buttons to a page 

#### Adding a CTA button
To add a big CTA button into your page, copy this code and add to your file and edit where you wan to link and what you want it read.

Example:
`{%- include button.html title="Read the guide" link="/guide" -%}`

#### Adding an action link
To add a big action link into your page, copy this code and add to your file and edit where you wan to link and what you want it read.

Example:
`{%- include action_link.html link="/improve-this-guide" title="Give feedback on this guide" -%}`

### Adding emphasis to page content with Insets
Insets are highlighting important content (like lessons learnt) in this guide. Because they are directly related to the content of a page, their content is "captured" inline and given a unique identifier like so:

```
{%- capture lesson_learnt_1 -%}
__Recommendation__ The Personal Demographic Service and NHAIS can get out of sync. Thus the reconciliation and any outstanding registration for any patient needs to be done before Go Live. If not done before Go Live, patient information can be lost and it could also cause issues during data migration.
{%- endcapture -%}
```

Then to be able to highlight the captured content, add the module code and pass the unique identifier (e.g. `lesson_learnt_1`), the title and specify if the content contains markdown (default: HTML).

```
{%- include inset.html content=lesson_learnt_1 accessibility_text="Lesson learnt" markdown=true -%}
```

### Steps/Timeline Component
This component is a custom component built to showcase a series of events or steps. In order to set one you'll have to add new Markdown pages in the `_steps` folder and ensure their group ID and order is set.

#### Adding steps/events timeline to a page
Under the `_steps` folder create a folder named on the group of steps or events. Each page under a group must have the following headings:

```
---
title: Example Step Title 
title_url: /path/to/file/permalink
subtitle: Subtitle
order:  1
group: example-group-id
---

Example content.
```

#### Ordering the steps/events
Ensure the `order` parameter is set correctly in the right desired order on all the pages mathing the same group.

#### Displaying the steps in a page
Finally, add the include code into the page you want the steps/timeline to be displayed. Change the group from `example-group-id` to your own group name. All steps under the same group will be then displayed on the page the module is included.

```{%- include steps/steps.html group='example-group-id' -%}```
