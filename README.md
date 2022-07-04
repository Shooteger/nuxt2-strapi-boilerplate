# Nuxt2 and Strapi v4 Template [WORK-IN-PROGRESS]

## Build Setup 

# Install and start Nuxt.js
```bash
#go to
$ cd nuxt-frontend

# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

# Install and start Strapi CMS
```bash
#go to
$ cd strapi-cms

# install dependencies
$ yarn install

# Start your Strapi application with autoReload enabled.
$ yarn dev

# Start your Strapi application with autoReload disabled.
$ yarn start

# Build your admin panel.
$ yarn build
```

## Description

A Boilerplate template of Nuxt.js 2 and Strapi v4.
The Strapi CMS shows the setup of a simple website, built with single types, collection types and components. You can use multiple frontends with this backend and use it as the only backend to host multiple websites with the same components and collections.
One example compans is already setup: Mpsys. You can copy its structure and create a new website or change the existing one and implement the components in the frontend as you like. Localisation with i18n is in Strapi enabled, Nuxt hast no need for i18 because all the content comes from the CMS.

# Strapi CMS Backend

A single type is a website. In this template for example, Mpsys. A website (single type / Mpsys), has many pages, Home, About, Contact... you get it. So one company can have multiple colletion types from with the name "page". A page has three sections. A hero-, body-, and footer-section. The hero can serve only one component at a time, while in the body section, multiple components can be choosen, as well in the footer section too. The Header is for every page fix programmed in the Frontend but the content/navigation is in the official UI Navigation Plugin in Strapi to define.

As summary, to create a new website, create a new single type in strapi and name it like your brand or the name of the website. Then add as many pages as you desire to the single type website. The name attribute of each page must be used, you can name it like About, Contact, Home, Solutions, etc... 
Each pages as three sections. A fixed header which can be changed in the Navigation Plugin Tab in Strapi CMS Admin Dashboard, a hero-section with one hero, a body-section which has repeatble components, a footer section with repeatable components. Each component can be named and reused. They are seperated into the three categories which a page can hold.

# Nuxt.js Frontend

CONTENT TO BE WRITTEN

## Instruction to add and implement a new component

# Create component in Strapi

# Implement the component in Frontend

## Features

* Latest Nuxt.js 2
* Strapi v4
* Tailwind CSS, Nuxt Fontawesome and SSR
* Strapi Navigation Plugin [WIP]
* Strapi Preview Button Plugin [WIP]
* Localisation enabled and integrated in routing [WIP]
