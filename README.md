This repo demonstrates issue with Parcel bundler and "react-pdf-highlighter-extended" package (though same happens
with "react-pdf-highlighter").

When i run parcel build, it crashes with error:

```
thread '<unnamed>' panicked at src\values\color.rs:3225:12:
internal error: entered unreachable code
note: run with `RUST_BACKTRACE=1` environment variable to display a backtrace
```

Build crashes as soon as I add
`import {PdfLoader} from 'react-pdf-highlighter-extended';`






