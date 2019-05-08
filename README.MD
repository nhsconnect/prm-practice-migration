# GP Clinical System Migration Guide

This guide aims to help Practices, Commissioning Support Units (CSUs) and Clinical Commissioning Groups (CCGs) plan and prepare their migration from one core clinical system to another. 

You can find the guide at https://nhsconnect.github.io/prm-practice-migration

### Menu navigation and sidebar items
To add, edit or reorder the menu items at the top of the page, edit the file `_data/menu_navigation.yml` page. 

Similarly, to add, edit or reorder the sidebar items at side of the page when a `page_with_sidebar` layout is use on a page, edit the file `_data/sidebar_navigation.yml` page. To add sub items in the hierarchy, include a subitems attribute and repeat the title/url structure.

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

### Formatting breadcrumbs and previous/next links
When adding permalinks in pages to other pages, either for breadcrumbs or for next/previous page follow these rules:
 - *DO* include the leading forward slash
 - *DO NOT* include the trailing forward slash

Example:

| Correctly formatting | Incorrect formatting |
| -------------------- | -------------------- |
| `/guide/kick-off`     | `/guide/kick-off/`    |
|                      | `guide/kick-off`      |


### Linking to a particular section within the guide
There is often a need to link to a particular section of the guide, this may be to a point half way down on a long page. To do this you can use bookmarks. Every Heading you create will auto generate a bookmark that you can link to

For example, if you have a heading such as:

```### Notification of 3rd parties and links```

Will auto generate a heading with an ID as follows:

```<h2 id="notification-of-3rd-parties-and-links">Notification of 3rd parties and links</h2>```

You can also define a custom ID to guarrantee the integrity of any links should the heading copy be changed. You do this using the following syntax

```### Notification of 3rd parties and links  {#notify-3rd-parties}```
