---
description: Comprehensive Meta conversion tracking setup and optimization tool. Configure Pixel events, Conversions API, and custom conversions with proper deduplication for maximum attribution accuracy.
---

# Meta Conversion Tracker

Comprehensive Meta conversion tracking setup and optimization tool. Configure Pixel events, Conversions API, and custom conversions with proper deduplication for maximum attribution accuracy.

**Category:** [Facebook & Meta Ads](../facebook-meta.md) · **Badge:** Facebook/Meta

## Where to find it

* **Web app** — [app.marketingtool.pro/tools/meta-conversion-tracker](https://app.marketingtool.pro/tools/meta-conversion-tracker)
* **iOS / Android app** — open the **Tools** tab and search “Meta Conversion Tracker”

## Inputs

| Input | Type | Required |
| --- | --- | --- |
| Website URL or Pixel ID | text | ✅ |
| Tracking Setup | select — Browser Pixel Only, Conversions API Only, Pixel + CAPI (Recommended), Custom Events | optional |
| Priority Events | select — E-commerce (Purchase, ATC, IC), Lead Gen (Lead, CompleteReg), App (Install, AppEvent), Custom Events | optional |

## Result workspace

Your result page is organized into tabs: **Overview**, **Targeting**, **Creative**, **Optimize**.

## Tips for best results

* **Deduplicate events** — Ensure browser Pixel and server-side CAPI events share the same event_id to prevent double-counting.
* **Track micro-conversions** — Beyond purchases, track AddToCart, ViewContent, and InitiateCheckout for richer optimization signals.
* **Test with diagnostics** — Use Meta's Event Manager diagnostics to verify events fire correctly before scaling campaigns.

## How to run it

1. Open **Meta Conversion Tracker** (links above).
2. Fill in the inputs and press **Generate**.
3. Review your full result page — it's saved to your History automatically. On desktop, use **Download All** to save every asset.
