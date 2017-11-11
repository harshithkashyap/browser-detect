## Browser Detect

This is a simple javascript module based on [detectmobilebrowsers](http://detectmobilebrowsers.com) with readable regular expression blocks to extend it.

### Installation
```bash
$ npm install hk-browser-detect --save
```

### Usage

```javascript
import { BrowserDetect } from 'browser-detect';
const browserDetect = new browserDetect();
browserDetect.isMobile()
```


### API
Instance methods:

1. isMobile(): boolean
2. isTablet(): boolean
3. isMobileOrTablet(): boolean

### License

[License](LICENSE.md)