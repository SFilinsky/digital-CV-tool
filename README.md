# Digital CV

This is CV project of Siarhei Filinski ([Linked In](https://www.linkedin.com/in/sergey-filinsky/)).

To run local dev server run:

```bash
npm run dev
```

It will be available on http://localhost:8080 and hot reloaded whenever you change files in `/src`.

Also, `.pdf` version will be created and can be found in `/dist`.

Important note: transparency doesn't work well with PDF, including gradients. This means that all such
styles should be wrapped into `@media screen {}` and PDF alternative provided for each of them as default.
