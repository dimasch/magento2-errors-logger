# magento2-errors-logger
Track magento2 javascript errors

TODO:
- Up service with winston endpoint https://github.com/vanthome/winston-elasticsearch
- We can use the Puppeteer for test without headless of Chrome

Send data to `Logstash` and analize it in `Kibana`
For more info use [ELK Article](http://dimasch.github.io/elk-stack-setup/)

Stack trace from js
```js
import StackTrace from 'stacktrace-js'
```
Capturing any `JS` errors with `onerror` event
https://www.sitepoint.com/capture-and-report-javascript-errors-with-window-onerror/
