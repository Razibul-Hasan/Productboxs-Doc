---
description: Install and activate ProductBoxes in under a minute.
---

# Install ProductBoxes

## Before you begin

| Requirement | Minimum |
| --- | --- |
| WordPress | 6.6 |
| WooCommerce | 9.0 (tested up to 11.2) |
| PHP | 7.4 |

{% hint style="warning" %}
WooCommerce must be installed and active first. ProductBoxes declares it as a required plugin, so WordPress will prompt you if it is missing.
{% endhint %}

## Install

{% tabs %}
{% tab title="From WordPress.org" %}
{% stepper %}
{% step %}
### Open Add New Plugin

In your WordPress admin, go to **Plugins → Add New Plugin**.
{% endstep %}

{% step %}
### Search

Search for **ProductBoxes** and find *ProductBoxes – Mix & Match Box Builder for WooCommerce*.
{% endstep %}

{% step %}
### Install and activate

Click **Install Now**, then **Activate**.
{% endstep %}

{% step %}
### Open ProductBoxes

A new **ProductBoxes** item appears in the admin menu, right below WooCommerce Products.
{% endstep %}
{% endstepper %}
{% endtab %}

{% tab title="Upload a ZIP" %}
1. Go to **Plugins → Add New Plugin → Upload Plugin**.
2. Choose the `productboxes-mix-and-match-box-builder.zip` file and click **Install Now**.
3. Click **Activate Plugin**.
{% endtab %}

{% tab title="Manual (FTP)" %}
Upload the `productboxes-mix-and-match-box-builder` folder to `/wp-content/plugins/`, then activate it from the **Plugins** screen.
{% endtab %}
{% endtabs %}

## Upgrading from 1.x

Updating to 2.0 is safe. Your existing campaigns, boxes, settings, orders and analytics are preserved through versioned migrations. Existing shortcodes, blocks and hooks keep working.

{% hint style="success" %}
After updating, open **ProductBoxes → Boxes**. Your campaigns are already there, now with the new three-step editor and ten templates.
{% endhint %}

## Next step

{% content-ref url="quick-start.md" %}
[quick-start.md](quick-start.md)
{% endcontent-ref %}

<!-- cta -->
---

{% hint style="success" %}
**Need help or want it done for you?**

💬 [Chat with live support](https://bestwebexpert.com/) · 🧑‍💻 [Hire an expert](https://bestwebexpert.com/) · 🎮 [Try the live demos](../demos.md) · 📚 [All support options](../support.md)
{% endhint %}
