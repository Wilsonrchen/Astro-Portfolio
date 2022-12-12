---
layout: ../../layouts/project.astro
title: Real Fake Clothes
client: Self
publishDate: 2022-12-09 00:00:00
img: https://res.cloudinary.com/dsvltch46/image/upload/v1670824839/Astro%20Portfolio/Images/graceShopper_g1zlxf.png?fit=crop&w=1400&h=700&q=75
description: |
  A fully interactive E-commerce website that allows users to exchange currency for a variety of clothing.
tags:
  - Node.js
  - Express
  - PostgreSQL
  - React
  - Material UI
  - Tailwind
  - Prisma
  - Easy-Peasy
---

Real Fake Clothes is my Capstone Project for the 2209 Web Development Bootcamp. With a group of 3, we made a fully interactive E-commerce website that sells clothes that can be sorted by category.

Users can register and log in to access their own cart created during the register process and can begin adding items to their cart. Users are also protected with a JSON web token and a cookie secret placed in the backend.

The cart functionality does not allow for duplicates as an alert will display once the user clicks the same item already in the cart, the user however may continue shopping as the error will fade. The cart also comes with its very own page that allows users to update the quantity. If the quantity goes below 1 the item gets removed, but users can also simply push the remove button to remove it as well.

The site also comes with a checkout form for users to enter in their card information when they are ready to confirm the purchase.

The site is styled with a mixture of Material UI and Tailwind where the data is stored in PostgreSQL and condensed with Prisma and Easy-Peasy.

<div>
<a href="https://github.com/LunchBoxBandits/graceShopper" >Github</a>
</div>
