# Y-System Static Files
Y-System Website Static Files

## Assets

|Category|File|Repository|Version|
|:--|:--|:--|:--|
|Basic|:page_facing_up: `jquery.min.js`|:package: [jquery/jquery](https://github.com/jquery/jquery)|[![UNPKG](https://img.shields.io/badge/unpkg-v3.3.1-blue.svg)](https://unpkg.com/jquery/dist/jquery.min.js)|
|Echarts|:page_facing_up: `echarts.min.js`|:package: [apache/incubator-echarts](https://github.com/apache/incubator-echarts)|[![UNPKG](https://img.shields.io/badge/unpkg-v4.1.0-blue.svg)](https://unpkg.com/echarts/dist/echarts.min.js)|
||:page_facing_up: `macarons.js`||[![UNPKG](https://img.shields.io/badge/unpkg-v4.1.0-blue.svg)](https://unpkg.com/echarts/theme/macarons.js)|
||:page_facing_up: `macarons.min.js`|||
||:page_facing_up: `world.js`||[![UNPKG](https://img.shields.io/badge/unpkg-v4.1.0-blue.svg)](https://unpkg.com/echarts/map/js/world.js)|
|Clipboard|:page_facing_up: `clipboard.min.js`|:package: [zenorocha/clipboard.js](https://github.com/zenorocha/clipboard.js)|[![UNPKG](https://img.shields.io/badge/unpkg-v2.0.1-blue.svg)](https://unpkg.com/clipboard/dist/clipboard.min.js)|
|Count Up/Down|:page_facing_up: `countUp.min.js`|:package: [inorganik/countUp.js](https://github.com/inorganik/countUp.js)|[![UNPKG](https://img.shields.io/badge/unpkg-v1.8.2-blue.svg)](https://unpkg.com/countup/dist/countUp.min.js)|
||:page_facing_up: `jquery.countdown.min.js`|:package: [hilios/jQuery.countdown](https://github.com/hilios/jQuery.countdown)|[![UNPKG](https://img.shields.io/badge/unpkg-v2.2.0-blue.svg)](https://unpkg.com/jquery-countdown/dist/jquery.countdown.min.js)|
|Rich Text Editor|:page_facing_up: `trix.js`|:package: [basecamp/trix](https://github.com/basecamp/trix)|[![UNPKG](https://img.shields.io/badge/unpkg-v0.12.0-blue.svg)](https://unpkg.com/trix/dist/trix.js)|
||:page_facing_up: `trix.css`||[![UNPKG](https://img.shields.io/badge/unpkg-v0.12.0-blue.svg)](https://unpkg.com/trix/dist/trix.css)|
||:page_facing_up: `trix.min.css`|||
|ID Validator|:page_facing_up: `IDValidator.min.js`|:package: [mc-zone/IDValidator](https://github.com/mc-zone/IDValidator)|[![UNPKG](https://img.shields.io/badge/unpkg-v1.3.0-blue.svg)](https://unpkg.com/id-validator/IDValidator.min.js)|
||:page_facing_up: `GB2260.min.js`||[![UNPKG](https://img.shields.io/badge/unpkg-v1.3.0-blue.svg)](https://unpkg.com/id-validator/GB2260.min.js)|
|Moment|:page_facing_up: `moment-with-locales.min.js`|:package: [moment/moment](https://github.com/moment/moment)|[![UNPKG](https://img.shields.io/badge/unpkg-v2.22.2-blue.svg)](https://unpkg.com/moment/min/moment-with-locales.min.js)|
|SVG|:page_facing_up: `svg.min.js`|:package: [svgdotjs/svg.js](https://github.com/svgdotjs/svg.js)|[![UNPKG](https://img.shields.io/badge/unpkg-v2.6.2-blue.svg)](https://unpkg.com/svgjs/dist/svg.min.js)|
|Fomantic UI|:file_folder: `*dir`|:package: [hammy2899/Fomantic-UI](https://github.com/hammy2899/Fomantic-UI)|[![UNPKG](https://img.shields.io/badge/unpkg-v2.4.4-blue.svg)](https://unpkg.com/fomantic-ui/dist/)|
||:page_facing_up: `tablesort.js`||[![Semantic UI JS Library](https://img.shields.io/badge/fomantic-v0.0.11-blue.svg)](https://fomantic-ui.com/javascript/library/tablesort.js)|
||:page_facing_up: `tablesort.min.js`|||
||:page_facing_up: `calendar.min.css`|:package: [mdehoog/Semantic-UI-Calendar](https://github.com/mdehoog/Semantic-UI-Calendar)|[![UNPKG](https://img.shields.io/badge/unpkg-v0.0.8-blue.svg)](https://unpkg.com/semantic-ui-calendar/dist/calendar.min.css)|
||:page_facing_up: `calendar.min.js`||[![UNPKG](https://img.shields.io/badge/unpkg-v0.0.8-blue.svg)](https://unpkg.com/semantic-ui-calendar/dist/calendar.min.js)|
|XSS|:page_facing_up: `xss.min.js`|:package: [leizongmin/js-xss](https://github.com/leizongmin/js-xss)|[![UNPKG](https://img.shields.io/badge/unpkg-v1.0.3-blue.svg)](https://unpkg.com/xss/dist/xss.min.js)|

## File Structure
```
├── basic\
│   └── js\
│       └── jquery.min.js
├── chart\
│   ├── echarts.min.js
│   ├── macarons.js
│   ├── macarons.min.js
│   └── world.js
├── clipboard\
│   └── clipboard.min.js
├── count\
│   ├── countUp.min.js
│   └── jquery.countdown.min.js
├── editor\
│   ├── trix.css
│   ├── trix.min.css
│   └── trix.js
├── id\
│   ├── GB2260.min.js
│   └── IDValidator.min.js
├── moment\
│   └── moment-with-locales.min.js
├── svg\
│   └── svg.min.js
├── ui\
│   ├── themes\
│   │   └── default\
│   │       └── assets\
│   │           ├── fonts\
│   │           │   ├── brand-icons.eot
│   │           │   ├── brand-icons.svg
│   │           │   ├── brand-icons.ttf
│   │           │   ├── brand-icons.woff
│   │           │   ├── brand-icons.woff2
│   │           │   ├── icons.eot
│   │           │   ├── icons.otf
│   │           │   ├── icons.svg
│   │           │   ├── icons.ttf
│   │           │   ├── icons.woff
│   │           │   ├── icons.woff2
│   │           │   ├── outline-icons.eot
│   │           │   ├── outline-icons.svg
│   │           │   ├── outline-icons.ttf
│   │           │   ├── outline-icons.woff
│   │           │   └── outline-icons.woff2
│   │           └── images\
│   │               └── flags.png
│   ├── calendar.min.css
│   ├── calendar.min.js
│   ├── semantic.min.css
│   ├── semantic.min.js
│   ├── tablesort.js
│   └── tablesort.min.js
└── xss\
    └── xss.min.js
```
