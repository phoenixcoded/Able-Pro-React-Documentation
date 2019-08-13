# Routing

This template routing system based on [react-router](https://reacttraining.com/react-router/) and its package [react-router-dom,](https://reacttraining.com/react-router/web/guides/quick-start) it's also use code splitting for better performance.

{% hint style="info" %}
**How can I add new page with menu item ?**

You can use the below explanation to add/remove menu routs and their menu items.
{% endhint %}

## Configure route

Open `able-pro/src/app/router.js` You will find the below example code. In below code we have show how you can add new page route.

{% code-tabs %}
{% code-tabs-item title="router.js" %}
```javascript
import React from 'react';
import $ from 'jquery';

window.jQuery = $;
window.$ = $;
global.jQuery = $;

const OtherSamplePage = React.lazy(() => import('./Demo/Other/SamplePage'));

const routes = [
    { path: '/sample-page', exact: true, name: 'Sample Page', component: OtherSamplePage },
];

export default routes;
```
{% endcode-tabs-item %}
{% endcode-tabs %}

## Add menu item

To add menu items you can use `able-pro/src/menu-items.js` file. Below code we have show how you can use new menu item.

You can use `MenuSingle`for single menu item and `MultiMenu` for multiple menu items. You can also add badge to menu by using `badgeText`option and set badge color by using `badgeColor`Option.

{% code-tabs %}
{% code-tabs-item title="menus.js" %}
```javascript
export default {
    items: [
        {
            id: 'admin',
            title: 'Admin',
            type: 'group',
            icon: 'icon-support',
            children: [
                {
                    id: 'sample-page',
                    title: 'Sample Page',
                    type: 'item',
                    url: '/sample-page',
                    classes: 'nav-item',
                    icon: 'feather icon-sidebar'
                },
                {
                    id: 'menu-level',
                    title: 'Menu Levels',
                    type: 'collapse',
                    icon: 'feather icon-menu',
                    children: [
                        {
                            id: 'menu-level-1.1',
                            title: 'Menu Level 1.1',
                            type: 'item',
                            url: '#!',
                        },
                        {
                            id: 'menu-level-1.2',
                            title: 'Menu Level 2.2',
                            type: 'collapse',
                            children: [
                                {
                                    id: 'menu-level-2.1',
                                    title: 'Menu Level 2.1',
                                    type: 'item',
                                    url: '#',
                                },
                                {
                                    id: 'menu-level-2.2',
                                    title: 'Menu Level 2.2',
                                    type: 'collapse',
                                    children: [
                                        {
                                            id: 'menu-level-3.1',
                                            title: 'Menu Level 3.1',
                                            type: 'item',
                                            url: '#',
                                        },
                                        {
                                            id: 'menu-level-3.2',
                                            title: 'Menu Level 3.2',
                                            type: 'item',
                                            url: '#',
                                        }
                                    ]
                                }
                            ]
                        }
                    ]
                }
            ]
        }
    ]
}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

