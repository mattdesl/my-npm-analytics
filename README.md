# my-npm-analytics

Boilerplate to set up [npm-install-analytics](https://github.com/mattdesl/npm-install-analytics).

Fork this repo and modify `index.html`, replacing `YOUR_TRACKING_ID` with the UA id code given by Google Analytics.

```js
...
  ga('create', 'YOUR_TRACKING_ID', 'auto');
  ga('send', 'pageview');
...
```

Push the changes to the `gh-pages` branch and you should be good to go.

# License

MIT.