<p align="center">
  <img src="https://raw.githubusercontent.com/siddharthkp/lazyfetch/master/art.jpg" height="200px"/>
  <br><br>
  <b>Load stuff lazily on the browser.</b>
  <br><br>

</p>

&nbsp;

- only 403 bytes (gzip)
- starts after the page load event
- ignored on the server (relevant for server side rendering)

&nbsp;

### Usage

`npm install lazyfetch --save`

```js
import lazyfetch from 'lazyfetch'

lazyfetch(
  /* list of urls to load */
  [
    'https://example.com/script.js',
    'https://example.com/styles.css'
  ],
  /* callback to execute after all of the urls have been fetched */
  () => {
    // ...
  }
)
```

&nbsp;

### like it?

:star: this repo

&nbsp;

### license

MIT © [siddharthkp](https://github.com/siddharthkp)

Logo credits to [Chris Lau](https://dribbble.com/chrislau)
