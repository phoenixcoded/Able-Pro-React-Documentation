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
| **headerBackColor** | background-blue | String | `background-blue`, `background-red`, `background-purple`, `background-info`, `background-green`, `background-dark`, `background-grd-blue`, `background-grd-red`, `background-grd-purple,` `background-grd-info`, `background-grd-green`, `background-grd-dark`, `background-img-1`, `background-img-2`, `background-img-3`, `background-img-4`, `background-img-5`, `background-img-6` |
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
    basename: '/react/default', // only at build time to set, like //able-pro/react/
    layout: 'vertical', // vertical, horizontal
    subLayout: '', // horizontal-2
    collapseMenu: false, // mini-menu
    layoutType: 'menu-light', // menu-dark, menu-light, dark
    headerBackColor: 'background-blue', // background-blue, background-red, background-purple, background-info, background-green, background-dark, background-grd-blue, background-grd-red, background-grd-purple, background-grd-info, background-grd-green, background-grd-dark, background-img-1, background-img-2, background-img-3, background-img-4, background-img-5, background-img-6
    rtlLayout: false,
    navFixedLayout: false,
    headerFixedLayout: false,
    boxLayout: false
};

```
{% endcode-tabs-item %}
{% endcode-tabs %}

