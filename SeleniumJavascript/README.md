```
npm install chromedriver
npm install selenium-webdriver
```

```
require('chromedriver');

var webdriver = require('selenium-webdriver');
var driver = new webdriver.Builder()
  .forBrowser('chrome')
  .build();

driver.get("http://www.google.com")
```
