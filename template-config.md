# Template Configuration

{% hint style="info" %}
You can edit this file at **`[ ../src/app-config.ts ]`**
{% endhint %}

| **Option** | **Default** | **Data Type** | **Description** |
| :--- | :--- | :--- | :--- |
| **layout** | vertical | String | `vertical`, `horizontal` |
| **subLayout** | - | String | `horizontal-2` \(only used for layout is horizontal\) |
| **collapseMenu** | false | Boolean | `true`, `false` |
| **layoutType** | menu-light | String | `menu-dark`, `menu-light`, `dark` |
| **headerBackColor** | background-blue | String | `backgorund-blue`, `backgorund-red`, `backgorund-purple`, `backgorund-info`, `backgorund-green`, `backgorund-dark`, `backgorund-grd-blue`, `backgorund-grd-red`, `backgorund-grd-purple`, `backgorund-grd-info`, `backgorund-grd-green`, `backgorund-grd-dark`, `backgorund-img-1`, `backgorund-img-2`, `backgorund-img-3`, `backgorund-img-4`, `backgorund-img-5`, `backgorund-img-6` |
| **rtlLayout** | false | Boolean | `true`, `false` |
| **navFixedLayout** | false | Boolean | `true`, `false` |
| **headerFixedLayout** | false | Boolean | `true`, `false` |
| **boxLayout** | false | Boolean | `true`, `false` |

\*\*\*\*

{% code-tabs %}
{% code-tabs-item title="config.js" %}
```javascript
export default {
    defaultPath: 'sample-page',
    basename: '/react/default', // only at build time to set, like //next/react/
    layout: 'vertical', // vertical, horizontal
    subLayout: '', // horizontal-2
    collapseMenu: false, // mini-menu
    layoutType: 'menu-light', // menu-dark, menu-light, dark
    headerBackColor: 'header-blue', // header-default, header-blue, header-red, header-purple, header-info, header-dark
    navBrandColor: 'brand-default', // brand-default, brand-blue, brand-red, brand-purple, brand-info, brand-dark
    rtlLayout: false,
    navFixedLayout: false,
    headerFixedLayout: false,
    boxLayout: false
};

```
{% endcode-tabs-item %}
{% endcode-tabs %}

