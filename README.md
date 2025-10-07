# neighbourhood-kitchen
# Neighbourhood Kitchen Mobile Menu App

A mobile-friendly food ordering app for Neighbourhood Kitchen, with Google Sheets integration.

## Features

- Sticky top bar for category selection (always visible)
- Scrollable menu for adding items to cart
- Floating cart bar at the bottom: shows item count, bill, and “Place Order”
- Modal popup to review items, enter table/online, and send your order
- Orders sent directly to Google Sheets via Apps Script backend

## Quick Start

1. Upload `index.html` to your GitHub repository (**root folder**).
2. Go to **Settings > Pages** and select `main` branch and root.
3. Your app will be live at:  
   `https://yourusername.github.io/your-repo-name/`
4. Orders are sent to:  
   `https://script.google.com/macros/s/AKfycbzEgDgE-8NeNudGa24a4BUQcnjylOVcdD0_v40fQDYeU9EmA8nr3Bu3vsI7EwMPvDnY/exec`

## Usage

- Browse menu by category (sticky top bar)
- Tap “Add” to select menu items
- Bar at the bottom always shows number of items and bill
- Tap the bar to review order and enter Table Name (“Online” for pickup)
- Place order—data sent instantly to Google Sheets

## Customization

- Edit menu items and prices in the `menu` array in `index.html`
- Change appearance by editing the `<style>` section in `index.html`
- Update backend URL if you change your script 

## Backend Setup

- Your provided Apps Script endpoint saves orders in Sheets: https://script.google.com/macros/s/AKfycbzEgDgE-8NeNudGa24a4BUQcnjylOVcdD0_v40fQDYeU9EmA8nr3Bu3vsI7EwMPvDnY/exec

