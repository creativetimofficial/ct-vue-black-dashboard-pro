# Change Log

## [1.4.1] 2024-02-25

- Minor Updates
- Fix Dev server issue

## [1.4.0] 2022-12-05

- Update dependencies and dev-dependencies
- Fix the installation issue when running `npm i`
- Migration from node-sass to sass

## [1.3.0] 2021-07-30

### Updates

- All dependencies were update
- FullCalendar new syntax update
- FullCalendar white mode fix
- When the server is opening a Bootstrap warning will appear on the console, but this will not affect your development
- Before npm install be sure that you have the latest npm and node installed
- When you npm install some warnings will appear like deprecated modules and some vulnerabilities. None of them will affect your development

## [1.2.3] 2020-06-03

- Package updates
- Sweetalert2, Vee-Validate, Google Maps plugins updated to new syntax

## [1.2.2] 2019-08-27

- Improve notification plugin to allow different order of notifications (last on top/bottom always)
- Improve css for element ui tags
- Update full calendar to use latest full calendar packages and api as well as full calendar Vue component
- Remove unused `assets` webpack alias
- Warning fixes for charts on Dashboard page
- Package updates

### How to upgrade

- Copy over `components`, `assets`, `vue.config.js` folder/files into your project.
- Add/update the following packages:  
  "@fullcalendar/core": "^4.3.1",
  "@fullcalendar/daygrid": "^4.3.0",
  "@fullcalendar/interaction": "^4.3.0",
  "@fullcalendar/timegrid": "^4.3.0",
  "@fullcalendar/vue": "^4.3.1",
  "element-ui": "^2.11.1",
  "vue": "^2.6.10",
  "vue-router": "^3.1.2",
  "@vue/cli-plugin-babel": "^3.11.0",
  "@vue/cli-plugin-eslint": "^3.11.0",
  "@vue/cli-plugin-pwa": "^3.11.0",
  "@vue/cli-service": "^3.11.0",
  "node-sass": "^4.12.0",
  "sass-loader": "^7.3.1",
  "vue-template-compiler": "^2.6.10"

## [1.2.1] 2019-07-19

- Improve addon icon support (addon right icon)
- Package updates

## [1.2.0] 2019-05-07

- Improve RTL plugin for Safari (bring scss locally in project)
- Convert `.babelrc` to `babel.config.js` to avoid hidden file issues on Mac OS
- Add Sidebar share plugin (many requested it), where you can change sidebar colors, dark mode etc
- Minor router scrollBehavior to scroll on top of the page on each page

## [1.1.2] 2019-02-12

- UI fixes & adjustments (footer, sidebar scroll, modals, performance chart responsiveness)
- Update bootstrap and remove local bootstrap code in favor of imports from node_modules

## [1.1.1] 2019-02-09

- IE bug fixes
- Fix perfect scrollbar issues on windows
- Package updates
- Improve base input component and add validations on Login/Register pages

## [1.1.0] 2019-01-05

### Breaking changes

- Update full calendar to latest alpha version
- Update world map to use DataMaps instead of jquery vector maps
- Remove jquery

### Updates & improvements

- Add starter template option as suggested in docs for easier use when starting out a project
- Add documentation on how to change from dark to light mode
- 1. Fix UI bug of horizontal scrolls appearing on tables.

## [1.0.0] 2018-12-04

### Stable Original Release
