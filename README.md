# lazyfetch

Load stuff lazily on the browser.

&nbsp;

- only 358 bytes (gzip)
- ignored on the server (relevant for server side rendering)

&nbsp;

### Usage

`npm install lazyfetch --save`

```
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

or load in the browser

```
<script async src="https://unpkg.com/lazyfetch/lib.js"></script>
```

&nbsp;

### like it?

:star: this repo

&nbsp;

### license

MIT © [siddharthkp](https://github.com/siddharthkp)
