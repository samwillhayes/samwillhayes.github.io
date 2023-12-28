## Subresource Integrity

If you are loading Highlight.js via CDN you may wish to use [Subresource Integrity](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity) to guarantee that you are using a legimitate build of the library.

To do this you simply need to add the `integrity` attribute for each JavaScript file you download via CDN. These digests are used by the browser to confirm the files downloaded have not been modified.

```html
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/highlight.min.js"
  integrity="sha384-xBsHBR6BS/LSlO3cOyY2D/4KkmaHjlNn3NnXUMFFc14HLZD7vwVgS3+6U/WkHAra"></script>
<!-- including any other grammars you might need to load -->
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/languages/go.min.js"
  integrity="sha384-WmGkHEmwSI19EhTfO1nrSk3RziUQKRWg3vO0Ur3VYZjWvJRdRnX4/scQg+S2w1fI"></script>
```

The full list of digests for every file can be found below.

### Digests

```
sha384-Wjwd1YEG/PYlkLHTWIx+RlPK6XboMN3bEpveERJ8D8Z4RaNE02Ho19ZFrSRPGi0j /es/languages/cpp.js
sha384-Q4zTNH8WsDVdSZbiZtzWS1HmAUcvMSdTmth9Uqgfjmx7Qzw6B8E3lC9ieUbE/9u4 /es/languages/cpp.min.js
sha384-DA5ii4oN8R2fsamNkHOanSjuN4v7j5RIuheQqnxMQ4cFnfekeuhwu4IdNXiCf+UU /es/languages/css.js
sha384-OBugjfIr093hFCxTRdVfKH8Oe3yiBrS58bhyYYTUQJVobk6SUEjD7pnV8BPwsr8a /es/languages/css.min.js
sha384-WCznKe2n87QvV/L1MlXN+S8R6NPUQGU34+AqogMuWGZJswSD6rt3Mgih+xuKlDgm /es/languages/javascript.js
sha384-eGsBtetyKPDKaLiTnxTzhSzTFM6A/yjHBQIj4rAMVaLPKW5tJb8U6XLr/AikCPd+ /es/languages/javascript.min.js
sha384-J4Ge+xXjXgzbK2FP+OyzIGHLfKU/RR0+cH4JJCaczeLETtVIvJdvqfikWlDuQ66e /languages/cpp.js
sha384-LMyrRAiUz6we2SGvYrwDd4TJoJZ+m/5c+4n4E64KVkfWFcZdlrs4Wabr0crMesyy /languages/cpp.min.js
sha384-r9czyL17/ovexTOK33dRiTbHrtaMDzpUXW4iRpetdu1OhhckHXiFzpgZyni2t1PM /languages/css.js
sha384-HpHXnyEqHVbcY+nua3h7/ajfIrakWJxA3fmIZ9X9kbY45N6V+DPfMtfnLBeYEdCx /languages/css.min.js
sha384-vJxw3XlwaqOQr8IlRPVIBO6DMML5W978fR21/GRI5PAF7yYi2WstLYNG1lXk6j9u /languages/javascript.js
sha384-44q2s9jxk8W5N9gAB0yn7UYLi9E2oVw8eHyaTZLkDS3WuZM/AttkAiVj6JoZuGS4 /languages/javascript.min.js
sha384-GTv+XlCrUf8auxgL/L9rqgXJtqJgBBY31RD324kcztIoB8Yy/KupDdDP5fcpkp/+ /highlight.js
sha384-ED36pj8NIw0ft4Gn22MJ2Q2U8+3y5M3cBUAvIHNa2xW0kxTQ19phs0BzVLz8bZPF /highlight.min.js
```

