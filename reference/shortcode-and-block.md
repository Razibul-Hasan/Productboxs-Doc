---
description: Place a box anywhere with the Gutenberg block or the [mmbb_box] shortcode.
---

# Shortcode and block

## Block

Add the **ProductBoxes Box Builder** block in the block editor, then choose which box to show.

## Shortcode

```
[mmbb_box id="12"]
```

### Attributes

| Attribute | Values | Default | Description |
| --- | --- | --- | --- |
| `id` | Box ID | none | **Required.** The box to display. |
| `layout` | `panel`, `bar`, `both` | `default` | Where the box summary sits. |
| `columns` | `3`, `4`, `5` | from design | Products per row. |
| `hero` | `true`, `false` | `true` | Show or hide the hero heading. |
| `template` | Template ID | from design | Override the box's template. |

### Examples

```
[mmbb_box id="12" columns="4"]
[mmbb_box id="12" template="night" hero="false"]
[mmbb_box id="12" layout="bar"]
```

{% hint style="info" %}
You can find a box's ID and a ready-made shortcode on the **Publish** step, or copy it with **Copy shortcode**.
{% endhint %}

<!-- cta -->
---

{% hint style="success" %}
**Need help or want it done for you?**

💬 [Chat with live support](https://bestwebexpert.com/) · 🧑‍💻 [Hire an expert](https://bestwebexpert.com/) · 🎮 [Try the live demos](../demos.md) · 📚 [All support options](../support.md)
{% endhint %}
