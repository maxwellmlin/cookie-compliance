# cookie-compliance
Using GitHub Pages to demo CMP behavior.

## AppConsent API Testing
```javascript
// Log changes to the tcString (TCF v2)
const callback = (tcData, success) => {
  console.log(tcData.tcString)
};
__tcfapi('addEventListener', 2, callback);

// Show Banner (unique to AppConsent API)
__tcfapi("show", 2, () => {});
```

## Helpful links
[Decode consent string](https://iabtcf.com/#/decode)

[TCF CMP list](https://iabeurope.eu/cmp-list/)

[TCF Vendor list](https://iabeurope.eu/vendor-list-tcf/)
