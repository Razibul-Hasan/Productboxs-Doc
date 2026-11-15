---
description: Filters, actions and REST routes for developers.
---

# Hooks and REST API

All hooks start with `mmbb_`. REST routes live under `/wp-json/mmbb/v1/`.

## Filters

| Filter | Use it to |
| --- | --- |
| `mmbb_templates` | Register or modify storefront templates. |
| `mmbb_campaign_config_defaults` | Change the defaults for new campaigns. |
| `mmbb_pricing_quote` | Adjust the price quote for a box. |
| `mmbb_convert_amount` | Convert amounts, used for multi-currency. |
| `mmbb_ensure_container_product` | Control the container product behind a box. |
| `mmbb_products_cache_context` | Vary the product cache by context. |
| `mmbb_compatibility_integrations` | Add or remove theme and plugin integrations. |
| `mmbb_track_events` | Return `false` to disable analytics tracking. |

## Actions

| Action | Fires |
| --- | --- |
| `mmbb_campaign_saved` | After a campaign is saved. |

## Examples

```php
// Disable analytics entirely.
add_filter( 'mmbb_track_events', '__return_false' );
```

```php
// Run code when a campaign is saved.
add_action( 'mmbb_campaign_saved', function ( $campaign_id ) {
	// Clear a custom cache, notify a service, etc.
}, 10, 1 );
```

{% hint style="warning" %}
Hook signatures can evolve between major versions. Check the source in `includes/` for the exact arguments before relying on a hook.
{% endhint %}

## Build from source

Source code is included in `src/`. Node.js **20.19 or later** is required.

```bash
npm install
npm run build
```

<!-- cta -->
---

{% hint style="success" %}
**Need help or want it done for you?**

💬 [Chat with live support](https://bestwebexpert.com/) · 🧑‍💻 [Hire an expert](https://bestwebexpert.com/) · 🎮 [Try the live demos](../demos.md) · 📚 [All support options](../support.md)
{% endhint %}
