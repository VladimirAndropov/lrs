примеры скриптов компонента аналитики
===================

Live Demo: "http://vladimirandropov.github.io/lrs/"

###config.js
config.js is used to configure the LRS endpoint and user information. This file needs created. To do this, edit config.js.template

example:
```javascript
Config.endpoint = "http://localhost:8000/xapi/";
Config.user = "Andropov";
Config.password = "1234";
Config.actor = { "mbox": "andropov@example.com", "name": "vladimir andropov" };
```
