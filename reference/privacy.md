---
description: What ProductBoxes stores, what it never collects, and how to control it.
---

# Privacy and data

{% hint style="success" %}
ProductBoxes does **not** connect to external services. No remote fonts, CDNs, telemetry, license checks or external preview services. All assets are bundled locally.
{% endhint %}

## Analytics

Optional analytics are stored **only in your WordPress database**.

* Random session IDs live in browser `sessionStorage`. No tracking cookies are created.
* Only **daily salted hashes** are stored.
* No IP addresses or user agents are collected.
* Raw events are deleted after the retention period (90 days by default).

Turn analytics off in **Settings**, or with the `mmbb_track_events` filter.

## Gift messages

Gift messages are stored with WooCommerce order items and are supported by the WordPress **personal data export and erasure** tools.

## Uninstalling

By default, uninstalling keeps your data. Enable **Delete all ProductBoxes data when I uninstall** in Settings to remove boxes, settings and analytics. Orders are never touched.

<!-- cta -->
---

{% hint style="success" %}
**Need help or want it done for you?**

💬 [Chat with live support](https://bestwebexpert.com/) · 🧑‍💻 [Hire an expert](https://bestwebexpert.com/) · 🎮 [Try the live demos](../demos.md) · 📚 [All support options](../support.md)
{% endhint %}
