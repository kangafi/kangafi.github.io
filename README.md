# Eave Network Website

To run locally

`python3 -m http.server`

or

`python -m SimpleHTTPServer`

Note docs are built using docusarus in a separate repository which needs to be a directory at the same level
```
cd ../docs/docs
yarn build
cd ../../eavenetwork.github.io
cp -rf ../docs/docs/build docs
```

