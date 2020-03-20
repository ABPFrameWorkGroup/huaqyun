<!--
 * @Author: your name
 * @Date: 2020-03-20 12:37:25
 * @LastEditTime: 2020-03-20 14:43:35
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \Learing\huaqyun\docs\zh-cn\frontend\directory.md
 -->
 ### 目录架构
``` javascript
|-- project
    |-- .editorconfig
    |-- .env.development
    |-- .env.production
    |-- .env.staging
    |-- .eslintignore
    |-- .eslintrc.js
    |-- .gitignore
    |-- .travis.yml
    |-- babel.config.js
    |-- jest.config.js
    |-- jsconfig.json
    |-- LICENSE
    |-- package-lock.json
    |-- package.json
    |-- plopfile.js
    |-- README.es.md
    |-- README.ja.md
    |-- README.md
    |-- README.zh-CN.md
    |-- vue.config.js
    |-- build
    |-- dist
    |-- mock
    |-- plop-templates
    |-- public
    |-- src
    |   |-- App.vue
    |   |-- main.js
    |   |-- permission.js
    |   |-- settings.js
    |   |-- api
    |   |   |-- permissionService.js
    |   |   |-- userService.js
    |   |-- assets
    |   |-- components
    |   |   |-- BackToTop
    |   |   |   |-- index.vue
    |   |   |-- Breadcrumb
    |   |   |   |-- index.vue
    |   |   |-- Charts
    |   |   |   |-- Keyboard.vue
    |   |   |   |-- LineMarker.vue
    |   |   |   |-- MixChart.vue
    |   |   |   |-- mixins
    |   |-- directive
    |   |   |-- clipboard
    |   |   |   |-- clipboard.js
    |   |   |   |-- index.js
    |   |   |-- el-drag-dialog
    |   |   |   |-- drag.js
    |   |   |   |-- index.js
    |   |-- filters
    |   |   |-- index.js
    |   |-- icons
    |   |   |-- index.js
    |   |   |-- svgo.yml
    |   |   |-- svg
    |   |       |-- 404.svg
    |   |       |-- bug.svg
    |   |-- lang
    |   |   |-- en.js
    |   |   |-- es.js
    |   |   |-- index.js
    |   |   |-- ja.js
    |   |   |-- zh.js
    |   |-- layout
    |   |   |-- index.vue
    |   |   |-- components
    |   |   |   |-- AppMain.vue
    |   |   |   |-- index.js
    |   |   |   |-- Navbar.vue
    |   |   |   |-- Settings
    |   |   |   |   |-- index.vue
    |   |   |   |-- Sidebar
    |   |   |   |   |-- FixiOSBug.js
    |   |   |   |   |-- index.vue
    |   |   |   |   |-- Item.vue
    |   |   |   |   |-- Link.vue
    |   |   |   |   |-- Logo.vue
    |   |   |   |   |-- SidebarItem.vue
    |   |   |   |-- TagsView
    |   |   |       |-- index.vue
    |   |   |       |-- ScrollPane.vue
    |   |   |-- mixin
    |   |       |-- ResizeHandler.js
    |   |-- router
    |   |   |-- index.js
    |   |   |-- modules
    |   |       |-- admin.js
    |   |       |-- charts.js
    |   |       |-- components.js
    |   |       |-- dashboard.js
    |   |       |-- host.js
    |   |       |-- nested.js
    |   |       |-- table.js
    |   |-- store
    |   |   |-- getters.js
    |   |   |-- index.js
    |   |   |-- modules
    |   |       |-- app.js
    |   |       |-- errorLog.js
    |   |       |-- permission.js
    |   |       |-- session.js
    |   |       |-- settings.js
    |   |       |-- tagsView.js
    |   |       |-- user.js
    |   |       |-- userConfig.js
    |   |-- styles
    |   |   |-- btn.scss
    |   |   |-- element-ui.scss
    |   |   |-- element-variables.scss
    |   |   |-- index.scss
    |   |   |-- logo.scss
    |   |   |-- mixin.scss
    |   |   |-- navbar.scss
    |   |   |-- sidebar.scss
    |   |   |-- transition.scss
    |   |   |-- variables.scss
    |   |-- utils
    |   |   |-- auth.js
    |   |   |-- clipboard.js
    |   |   |-- error-log.js
    |   |   |-- get-page-title.js
    |   |   |-- i18n.js
    |   |   |-- index.js
    |   |   |-- localStore.js
    |   |   |-- menu.js
    |   |   |-- open-window.js
    |   |   |-- permission.js
    |   |   |-- request.js
    |   |   |-- scroll-to.js
    |   |   |-- treeData.js
    |   |   |-- treePermissions.js
    |   |   |-- validate.js
    |   |-- vendor
    |   |   |-- Export2Excel.js
    |   |   |-- Export2Zip.js
    |   |-- views
    |       |-- admin
    |       |   |-- auditlog
    |       |   |   |-- index.vue
    |       |   |-- edition
    |       |   |   |-- index.vue
    |       |   |-- language
    |       |   |   |-- index.vue
    |       |   |-- maintenance
    |       |   |   |-- index.vue
    |       |   |-- organization
    |       |   |   |-- index.vue
    |       |   |-- role
    |       |   |   |-- index.vue
    |       |   |-- settings
    |       |   |   |-- index.vue
    |       |   |-- tenant
    |       |   |   |-- index.vue
    |       |   |-- user
    |       |       |-- AdminUsers.vue
    |       |       |-- CreateOrEditUserDialog.vue
    |       |-- dashboard
    |       |   |-- index.vue
    |       |-- error-page
    |       |   |-- 401.vue
    |       |   |-- 404.vue
    |       |-- login
    |       |   |-- auth-redirect.vue
    |       |   |-- index.vue
    |       |   |-- components
    |       |       |-- SocialSignin.vue
    |       |-- theme
    |       |   |-- index.vue
    |-- tests
        |-- unit
            |-- .eslintrc.js
            |-- components
            |   |-- Hamburger.spec.js
            |   |-- SvgIcon.spec.js
            |-- utils
                |-- formatTime.spec.js
                |-- parseTime.spec.js
                |-- validate.spec.js

```