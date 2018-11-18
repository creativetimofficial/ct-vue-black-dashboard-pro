# [Vue Black Dashboard PRO](https://www.creative-tim.com/product/vue-black-dashboard-pro) [![version][version-badge]][CHANGELOG]

![alt text](https://s3.amazonaws.com/creativetim_bucket/products/99/original/opt_bd_vue_thumbnail.jpg?1539595932)

**[Vue Black Dashboard PRO](https://www.creative-tim.com/product/vue-black-dashboard-pro)** is a beautiful Bootstrap 4 and Vue.js Admin Dashboard that comes in 2 versions: Dark and Light Mode. If you are looking for a tool to manage and visualize data about your business, this dashboard is the thing for you. It combines colors that are easy on the eye, spacious cards, beautiful typography, and graphics.

Vue Black Dashboard Pro is the Vue.js ported version of the [Original Black Dashboard Pro](https://themes.getbootstrap.com/product/black-dashboard-pro-premium-bootstrap-4-admin/).

Using the Dashboard is pretty simple but requires basic knowledge of Javascript, [Vue](https://vuejs.org/v2/guide/) and [Vue-Router](https://router.vuejs.org/en/).
Vue Black Dashboard PRO was coded by [BinarCode](https://binarcode.com) and the design was made by [Creative Tim](https://www.creative-tim.com/).

The product represents a big suite of front-end developer tools that can help you jump start your project. We have created it thinking about things you actually need in a dashboard. Vue Black Dashboard PRO contains handpicked and optimised Vuejs plugins. Everything is designed to fit with one another. As you will be able to see, the dashboard you can access on Creative Tim is a customisation of this product.

We like consistency and design that blends into its purpose.
Vue Black Dashboard PRO is a perfect example of our most thoughtful work. It combines Vue.js components and plugins, while looking like everything fits together.
For an easy start or inspiration for you project, we have also create a set of example pages, like the user settings or usage graphics.

Let us know what you think and what we can improve below. And good luck with development!

## Links:

+ [Live Preview](http://demos.crea/vue-now-ui-dashboard-pro)

## Quick Start:

Quick start options:

+ [Download from Creative Tim](https://demos.creative-tim.com/vue-black-dashboard-pro).
+ Make sure you have [Node js](https://nodejs.org/en/) installed
+ Go to the downloaded folder and open a terminal
+ Type `npm install` or `yarn install` if you use [yarn](https://yarnpkg.com/en/)
+ Type `npm run dev` to start a development server

The repo uses [vue-cli](https://github.com/vuejs/vue-cli) scaffolding which takes care of the development setup with webpack and all the necessary modern tools to make web development faster and easier.

Other Products:

+ [Download FREE Vue Version](https://www.creative-tim.com/product/vue-black-dashboard).

### What's included

Within the download you'll find the following directories and files:
```
|-- vue-black-dashboard-pro
    |-- App.vue
    |-- config.js
    |-- i18n.js
    |-- main.js
    |-- polyfills.js
    |-- assets
    |   |-- css
    |   |   |-- nucleo-icons.css
    |   |-- fonts
    |   |-- sass
    |       |-- black-dashboard-pro.scss
    |-- components
    |   |-- AnimatedNumber.vue
    |   |-- Badge.vue
    |   |-- BaseAlert.vue
    |   |-- BaseButton.vue
    |   |-- BaseCheckbox.vue
    |   |-- BaseDropdown.vue
    |   |-- BaseNav.vue
    |   |-- BasePagination.vue
    |   |-- BaseProgress.vue
    |   |-- BaseRadio.vue
    |   |-- BaseSwitch.vue
    |   |-- BaseTable.vue
    |   |-- CloseButton.vue
    |   |-- ImageUpload.vue
    |   |-- LoadingPanel.vue
    |   |-- Modal.vue
    |   |-- NavbarToggleButton.vue
    |   |-- Slider.vue
    |   |-- index.js
    |   |-- Breadcrumb
    |   |   |-- Breadcrumb.vue
    |   |   |-- BreadcrumbItem.vue
    |   |   |-- RouteBreadcrumb.vue
    |   |-- Cards
    |   |   |-- Card.vue
    |   |   |-- StatsCard.vue
    |   |-- Charts
    |   |   |-- BarChart.js
    |   |   |-- LineChart.js
    |   |   |-- PieChart.js
    |   |   |-- config.js
    |   |   |-- utils.js
    |   |-- Collapse
    |   |   |-- Collapse.vue
    |   |   |-- CollapseItem.vue
    |   |-- Inputs
    |   |   |-- BaseCheckbox.vue
    |   |   |-- BaseInput.vue
    |   |   |-- BaseRadio.vue
    |   |   |-- IconCheckbox.vue
    |   |-- Navbar
    |   |   |-- Navbar.vue
    |   |   |-- NavbarToggleButton.vue
    |   |-- NotificationPlugin
    |   |   |-- Notification.vue
    |   |   |-- Notifications.vue
    |   |   |-- index.js
    |   |-- SidebarPlugin
    |   |   |-- SideBar.vue
    |   |   |-- SidebarItem.vue
    |   |   |-- index.js
    |   |-- Tabs
    |   |   |-- Tab.vue
    |   |   |-- Tabs.vue
    |   |-- Timeline
    |   |   |-- TimeLine.vue
    |   |   |-- TimeLineItem.vue
    |   |-- Wizard
    |   |   |-- Wizard.vue
    |   |   |-- WizardTab.vue
    |   |   |-- throttle.js
    |   |-- WorldMap
    |       |-- AsyncWorldMap.vue
    |       |-- WorldMap.vue
    |       |-- world_map.js
    |-- directives
    |   |-- click-ouside.js
    |-- locales
    |   |-- ar.json
    |   |-- en.json
    |-- pages
    |   |-- Charts.vue
    |   |-- DefaultHeader.vue
    |   |-- Widgets.vue
    |   |-- Calendar
    |   |   |-- Calendar.vue
    |   |   |-- CalendarHeader.vue
    |   |   |-- CalendarRoute.vue
    |   |-- Components
    |   |   |-- Buttons.vue
    |   |   |-- GridSystem.vue
    |   |   |-- Icons.vue
    |   |   |-- Notifications.vue
    |   |   |-- Panels.vue
    |   |   |-- SweetAlert.vue
    |   |   |-- Typography.vue
    |   |   |-- Headers
    |   |       |-- SweetAlertHeader.vue
    |   |-- Dashboard
    |   |   |-- CountryMapCard.vue
    |   |   |-- Dashboard.vue
    |   |   |-- DashboardHeader.vue
    |   |   |-- HeaderChart.js
    |   |   |-- TaskList.vue
    |   |   |-- UserTable.vue
    |   |-- Forms
    |   |   |-- ExtendedForms.vue
    |   |   |-- RegularForms.vue
    |   |   |-- ValidationForms.vue
    |   |   |-- Wizard.vue
    |   |   |-- ValidationForms
    |   |   |   |-- LoginForm.vue
    |   |   |   |-- RangeValidationForm.vue
    |   |   |   |-- RegisterForm.vue
    |   |   |   |-- TypeValidationForm.vue
    |   |   |-- Wizard
    |   |       |-- FirstStep.vue
    |   |       |-- SecondStep.vue
    |   |       |-- ThirdStep.vue
    |   |-- GeneralViews
    |   |   |-- NotFoundPage.vue
    |   |-- Layout
    |   |   |-- Content.vue
    |   |   |-- ContentFooter.vue
    |   |   |-- DashboardLayout.vue
    |   |   |-- DashboardNavbar.vue
    |   |   |-- LoadingMainPanel.vue
    |   |   |-- SidebarFixedToggleButton.vue
    |   |   |-- SidebarSharePlugin.vue
    |   |   |-- SidebarToggleButton.vue
    |   |-- Maps
    |   |   |-- API_KEY.js
    |   |   |-- FullScreenMap.vue
    |   |   |-- GoogleMaps.vue
    |   |   |-- VectorMaps.vue
    |   |   |-- VectorMapsHeader.vue
    |   |   |-- WorldMap.vue
    |   |   |-- world_map.js
    |   |-- Pages
    |   |   |-- AuthLayout.vue
    |   |   |-- Lock.vue
    |   |   |-- Login.vue
    |   |   |-- Pricing.vue
    |   |   |-- RTLPage.vue
    |   |   |-- Register.vue
    |   |   |-- TimeLinePage.vue
    |   |   |-- UserProfile.vue
    |   |   |-- UserProfile
    |   |       |-- EditProfileForm.vue
    |   |       |-- UserCard.vue
    |   |-- Tables
    |       |-- ExtendedTables.vue
    |       |-- PaginatedTables.vue
    |       |-- RegularTables.vue
    |       |-- users.js
    |       |-- ExtendedTables
    |           |-- ShoppingTable.vue
    |-- plugins
    |   |-- RTLPlugin.js
    |   |-- dashboard-plugin.js
    |   |-- globalComponents.js
    |   |-- globalDirectives.js
    |   |-- liveDemo.js
    |-- routes
        |-- router.js
        |-- routes.js
```

## Useful Links

More products from Creative Tim: <https://www.creative-tim.com/bootstrap-themes>

Tutorials: <https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w>

Freebies: <https://www.creative-tim.com/products>

Affiliate Program (earn money): <https://www.creative-tim.com/affiliates/new>

Social Media:

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Google+: <https://plus.google.com/+CreativetimPage>

Instagram: <https://instagram.com/creativetimofficial>

[CHANGELOG]: ./CHANGELOG.md
[version-badge]: https://img.shields.io/badge/version-1.0.0-blue.svg
