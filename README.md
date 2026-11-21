# Mobile Push Notifications for CS-Cart

**🛑 PREMIUM ADD-ON: This repository does not contain the open-source code. It serves as the official listing and documentation page for the WebGraphiq premium add-on.**

**Mobile Push Notifications** sends real-time admin alerts to your phone when the shop needs attention. Delivery uses a **Pushover** or **Pushbullet** account you already have — no custom mobile app to maintain.

## [🛒 Buy & View Live Demo](https://webgraphiq.com/mobile-push-notifications.html)

One-time license. The current price and the live demo are on the product page.

## Why store owners use it

- **New order** — when the order status is set to notify the department (same idea as the admin order email).
- **New customer** — storefront registration.
- **Low stock** — product quantity drops to zero or below.
- Optional floor: only send order pushes when the order total is above an amount you set.
- Optional message bits: customer name and order total.
- On **Multi-Vendor**, a copy can go to the vendor (per-vendor Pushover / Pushbullet keys on the company).
- Test links on the settings screen for either service.
- No CS-Cart core file edits.

## Events

| Event | When it fires |
|---|---|
| On new order | Order status change / place path where that status notifies the department |
| New customer registered | Storefront profile create (`AREA` customer) |
| Product quantity less than zero | Inventory update leaves amount at zero or below |

Each event is a checkbox under **Add-ons → Wg Mobile Push Notifications**.

## Pushover and Pushbullet

Enable one or both under the **Pushover and Pushbullet settings** section:

- **Pushover** — user key, application API key, optional single device name, optional sound (default `pushover`).
- **Pushbullet** — access token and device iden.
- **Test** links send a sample push so you can confirm keys before going live.

You need an account at [Pushover](https://pushover.net/) and/or [Pushbullet](https://www.pushbullet.com/).

## Multi-Vendor

- Root setting: **Send Push Notifications to vendor**.
- Vendors can store their own Pushover / Pushbullet keys on the company contact fields.
- Vendor copy covers order and low-stock paths when enabled.

## What you control

- License key.
- Each event on or off (defaults: all three on).
- Minimum order total for order pushes (default `0` = no floor).
- Customer name / order amount in the message (defaults on).
- Vendor delivery (Multi-Vendor, default off).
- Pushover and Pushbullet credentials, device, and sound.

## Requirements

- CS-Cart or Multi-Vendor **4.12.1** or newer, including **4.21**
- PHP **8.3** or a current 8.x release used by that shop
- A Pushover and/or Pushbullet account

## This repository

<p align="center">
  <a href="https://webgraphiq.com/mobile-push-notifications.html">
    <img alt="Buy and view the live demo" src="https://img.shields.io/badge/CS--Cart-Buy%20%26%20View%20Live%20Demo-28a745?style=for-the-badge&labelColor=1A365D">
  </a>
</p>

<p align="center"><strong>One-time license · order and stock alerts on your phone</strong></p>

This is the public product listing. The add-on package, license checks, and source files are not published here. After purchase, the package is readable PHP under the WebGraphiq commercial license, installed from your WebGraphiq account.

Support: [webgraphiq.com](https://www.webgraphiq.com) · webgraphiq@gmail.com

© WebGraphiq. All rights reserved. [License](https://www.webgraphiq.com/license.html)

## Other Premium CS-Cart Add-ons by WebGraphiq

More CS-Cart and Multi-Vendor add-ons are listed on the [WebGraphiq GitHub profile](https://github.com/webgraphiq).
