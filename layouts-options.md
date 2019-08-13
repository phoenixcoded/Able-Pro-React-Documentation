---
description: Layout Variants
---

# Layouts Options

{% hint style="info" %}
You can edit this file at **`[ ../src/app-config.ts ]`**
{% endhint %}

## Main Layouts

{% tabs %}
{% tab title="Default / Vertical" %}
* layout: `vertical`
* subLayout: ' '
* collapseMenu: `false`
* layoutType: `menu-light`
* headerBackColor: `header-blue`
* rtlLayout: `false`
* navFixedLayout: `false`
* headerFixedLayout: `false`
* boxLayout: `false`
{% endtab %}

{% tab title="Horizontal" %}
* layout: `horizontal`
* navFixedLayout: `false`
* headerFixedLayout: `false`
{% endtab %}

{% tab title="Light Layout" %}
* layout: `vertical/horizontal`
* layoutType: `menu-light`
* headerBackColor: `header-default`
{% endtab %}

{% tab title="Dark Layout" %}
* layout: `vertical/horizontal`
* layoutType: `dark`
* headerBackColor: `header-dark`
{% endtab %}
{% endtabs %}

## Vertical Layouts

{% tabs %}
{% tab title="Static Layout" %}
* layout: `vertical`
* navFixedLayout: `false`
* headerFixedLayout: `false`
{% endtab %}

{% tab title="Fixed Layout" %}
* layout: `vertical`
* navFixedLayout: `true`
* headerFixedLayout: `true`
{% endtab %}

{% tab title="Nav Fixed" %}
* ayout: `vertical`
* navFixedLayout: `true`
* headerFixedLayout: `false`
{% endtab %}

{% tab title="Collapsed Menu" %}
* layout: `vertical`
* collapseMenu: `true`
{% endtab %}

{% tab title="RTL Layout" %}
* layout: `vertical`
* rtlLayout: `true`
{% endtab %}

{% tab title="Box Layout" %}
* layout: `vertical`
* navFixedLayout: `true`
* headerFixedLayout: `false`
* boxLayout: `true`
{% endtab %}
{% endtabs %}

## Horizontal Layouts

{% tabs %}
{% tab title="Horizontal-2" %}
* layout: `horizontal`
* subLayout: `horizontal-2`
* navFixedLayout: `false`
* headerFixedLayout: `false`
{% endtab %}

{% tab title="Horizontal RTL" %}
* layout: `horizontal`
* subLayout: `horizontal-2`
* navFixedLayout: `false`
* headerFixedLayout: `false`
* rtlLayout: `true`
{% endtab %}
{% endtabs %}

