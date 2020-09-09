
![](./doc/images/20200909_164504_utDQ2T.png)

Make sure `bottom-navigation` is defined before any footer plugin.

```json
{
  "plugins": [
    "bottom-navigation",
    "page-footer-ex"
  ]
}
```

You can also customize the hovered color with following properties:

```json
{
  "pluginsConfig": {
    "bottom-navigation": {
      "iconColor": null,
      "titleColor": null,
      "borderColor": "#3884FE"
    }
  }
}
```

Notice `borderColor` has the toppest priority which means if `iconColor` or `titleColor` is not defined, it will be the same color with `borderColor`.

If you think default width of `page-inner` is too narrow, you can change it with `pageInnerWidth` property like `"pageInnerWidth": "80%"`.
