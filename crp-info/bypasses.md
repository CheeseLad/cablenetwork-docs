# Cable Creative Roleplay | Bypasses Guide

*If you have any suggestions for this document, please let us know on Discord!*

Bypasses allow players and donors to obtain and use restricted items and vehicles on the server. You can control your bypasses and personal group directly in-game using commands.

## Overview

### Donation Bypasses
On a donor's first eligible free bypass claim, the plugin automatically creates their personal group with default metadata and adds the claim. Donors can later use `/bypassgroup name <display name>` and `/bypassgroup color <#HexCode>` to customize it. Free claims are subject to the combined limit from the donor's donation tiers.

### Shop Bypasses (All Players)
All players can buy permanent bypasses from the shop list using in-game money. Purchases are placed in your personal group; if you do not have one, a group is created automatically. 

Shop-only players do not need `/bypassgroup`. If you later qualify for a donation tier, your existing group and purchased bypasses are retained, and your first free claim attaches the donor tier to that group.

### Important Rules
- **Paid purchases do not use donor free-claim slots** and cannot be removed using player free-claim commands.
- A bypass already granted by a free claim, a rank, or another group cannot be purchased again.
- Bypasses purchased using in-game money are **non-refundable** and **non-changeable**.

## For All Players

| Command | Description |
|---|---|
| `/bypasses` (`/bypasslist`) | Shows your donor bypasses used/allowed, paid bypasses purchased/allowed, and your active bypass list. |
| `/bypassshop` (`/bshop`) | Lists item and vehicle bypass offers currently available for purchase with in-game money. |
| `/bypasscost <ID>` | Shows the price for the listed item or vehicle bypass offer with that ID. If both item and vehicle offers use the ID, specify `item` or `vehicle`. |
| `/bypassbuy <item\|vehicle> <ID>` (`/bbuy`) | Purchases one listed bypass offer with in-game money. |

## For Donators

These claim and group customization commands require an active donation tier.

| Command | Description |
|---|---|
| `/bypassgroup name <display name>` (`/bg`) | Changes your personal group display name and prefix. |
| `/bypassgroup color <#HexCode>` (`/bg`) | Changes your personal group color. The six-digit hex color may optionally start with `#` (e.g. `#FF0000`). |
| `/bypassitem <item ID>` (`/bi`) | Adds an eligible item bypass to your personal group. If already added, enters removal confirmation. |
| `/bypassitem confirm` / `/bi confirm`<br>`/bypassitem cancel` / `/bi cancel` | Confirms or cancels a pending item bypass removal. Confirmation expires after 30 seconds. |
| `/bypassvehicle <vehicle ID>` (`/bv`) | Adds an eligible vehicle bypass to your personal group. If already added, enters removal confirmation. |
| `/bypassvehicle confirm` / `/bv confirm`<br>`/bypassvehicle cancel` / `/bv cancel` | Confirms or cancels a pending vehicle bypass removal. Confirmation expires after 30 seconds. |
