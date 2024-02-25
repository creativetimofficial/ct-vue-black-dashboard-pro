# [Vue Black Dashboard PRO](https://demos.creative-tim.com/paper-dashboard-pro-react/#/dashboard)

![version](https://img.shields.io/badge/version-1.4.1-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/ct-paper-dashboard-pro-react.svg?maxAge=2592000)](https://github.com/creativetimofficial/ct-paper-dashboard-pro-react/issues?q=is%3Aopen+is%3Aissue) [![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/creativetimofficial/ct-paper-dashboard-pro-react.svg?maxAge=2592000)](https://github.com/creativetimofficial/ct-paper-dashboard-pro/issues-react?q=is%3Aissue+is%3Aclosed) [![Chat](https://img.shields.io/badge/chat-on%20discord-7289da.svg)](https://discord.gg/E4aHAQy)

![Product Gif](./github-assets/vue-black-dashboard-pro.gif)

**[Vue Black Dashboard PRO](https://demos.creative-tim.com/vue-black-dashboard-pro)** is a beautiful Bootstrap 4 Admin Dashboard that comes in 2 versions: Dark and Light Mode. If you are looking for a tool to manage and visualize data about your business, this dashboard is the thing for you. It combines colors that are easy on the eye, spacious cards, beautiful typography, and graphics.

We made it our priority to not add things that you don't need, so the Vue Black Dashboard PRO comes with just enough features for you to easily use. It combines multiple components and plugins and features numerous example of how it can be used. Inside the archive, you will also find multiple example pages to get you started or provide inspiration.

**[Vue Black Dashboard PRO](https://demos.creative-tim.com/vue-black-dashboard-pro)** is the extended version of [Black Dashboard PRO](https://themes.getbootstrap.com/product/black-dashboard-pro-premium-bootstrap-4-admin/). Based on feedback from people that downloaded and used it, we have added needed components, and we have created multiple examples pages. We are curious to see how you want to use it and also improve it, so let us know any feedback you have.

**Bootstrap 4 support**

Vue Black Dashboard PRO is built on top of [Bootstrap 4](http://getbootstrap.com/) and [Vue.js](https://vuejs.org/) Most of the elements from the dashboard are re-designed to resemble popular dark themes such as Mac OS Mojave Dark mode.
Let us know what you think and what we can improve below. And good luck with development!

View example pages [here](https://demos.creative-tim.com/vue-black-dashboard-pro).

## Table of Contents

- [Versions](#versions)
- [Demo](#demo)
- [Quick Start](#quick-start)
- [Documentation](#documentation)
- [File Structure](#file-structure)
- [Browser Support](#browser-support)
- [Resources](#resources)
- [Reporting Issues](#reporting-issues)
- [Technical Support or Questions](#technical-support-or-questions)
- [Licensing](#licensing)
- [Useful Links](#useful-links)

## Versions

[<img src="./github-assets/html.png" width="60" height="60" />](https://themes.getbootstrap.com/product/black-dashboard-pro-premium-bootstrap-4-admin/)
[<img src="./github-assets/vuejs.png" width="60" height="60" />](https://www.creative-tim.com/product/vue-black-dashboard-pro)

| HTML                                                                                                                                                                                               | Vue                                                                                                                                                                                              |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [![Black Dashboard HTML](https://themes.getbootstrap.com/wp-content/uploads/2018/08/bb_bdp_thumbnail.jpg)](https://themes.getbootstrap.com/product/black-dashboard-pro-premium-bootstrap-4-admin/) | [![Vue Black Dashboard Pro](https://s3.amazonaws.com/creativetim_bucket/products/99/original/opt_bd_vue_thumbnail.jpg?1539595932)](https://www.creative-tim.com/product/vue-black-dashboard-pro) |

## Demo

- [Start page](https://demos.creative-tim.com/vue-black-dashboard-pro)
- [User profile page](https://demos.creative-tim.com/vue-black-dashboard-pro/#/pages/user)
- [Tables page ](https://demos.creative-tim.com/vue-black-dashboard-pro/#/table-list/extended)
- [Maps Page](https://demos.creative-tim.com/vue-black-dashboard-pro/#/maps/google)
- [Notifications page](https://demos.creative-tim.com/vue-black-dashboard-pro/#/components/notifications)

[View More](https://demos.creative-tim.com/vue-black-dashboard-pro).

## Quick start

Quick start options:

- Buy from [Creative Tim](https://www.creative-tim.com/product/vue-black-dashboard-pro)

## Documentation

The documentation for the Vue Black Dashboard Pro can be found [here](https://demos.creative-tim.com/vue-black-dashboard-pro/documentation/#/).

## File Structure

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

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="./github-assets/chrome.png" width="64" height="64"> <img src="./github-assets/firefox.png" width="64" height="64"> <img src="./github-assets/edge.png" width="64" height="64"> <img src="./github-assets/safari.png" width="64" height="64"> <img src="./github-assets/opera.png" width="64" height="64">

## Resources

- [Live Preview](https://demos.creative-tim.com/vue-black-dashboard-pro)
- Buy Page: https://www.creative-tim.com/product/vue-black-dashboard-pro
- Documentation is [here](https://demos.creative-tim.com/vue-black-dashboard-pro/documentation)
- License Agreement: https://www.creative-tim.com/license
- Support: https://www.creative-tim.com/contact-us
- Issues: [Github Issues Page](https://github.com/creativetimofficial/ct-vue-black-dashboard-pro/issues)
- Vue Black Dashboard FREE- [demo](https://www.creative-tim.com/product/vue-black-dashboard?ref=github-vue-black-dashboard-pro)

## Reporting Issues

We use GitHub Issues as the official bug tracker for the Vue Black Dashboard Pro. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Vue Black Dashboard Pro. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Technical Support or Questions

If you have questions or need help integrating the product please [contact us](https://www.creative-tim.com/contact-us) instead of opening an issue.

## Licensing

- Copyright 2024 Creative Tim (https://www.creative-tim.com)
- Creative Tim [license](https://www.creative-tim.com/license)

## Useful Links

- [More products](https://www.creative-tim.com/bootstrap-themes) from Creative Tim

- [Tutorials](https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w)

- [Freebies](https://www.creative-tim.com/bootstrap-themes/free) from Creative Tim

- [Affiliate Program](https://www.creative-tim.com/affiliates/new) (earn money)

##### Social Media

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Google+: <https://plus.google.com/+CreativetimPage>

Instagram: <https://instagram.com/creativetimofficial>
