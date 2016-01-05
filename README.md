# polymer-color-picker

This is a very simple Polymer color-picker that will allow you to choose one
of the Material Design colours.

Example:

```html
<polymer-color-picker></polymer-color-picker>
<polymer-color-picker color="{{selectedColor}}"></polymer-color-picker>
```

You can configure the color palette being used using the `colorList` array and
the `columnCount` property, which specifies how many "generic" colours (i.e. columns
in the picker) you want to display.

```html
<polymer-color-picker column-count=5 color-list='["#65a5f2", "#83be54", "#f0d551", "#e5943c", "#a96ddb", ]'></polymer-color-picker>
```

![color picker demo](https://cloud.githubusercontent.com/assets/1369170/12102286/accc1c00-b2ee-11e5-8d67-b7758ba9e1f3.gif)
