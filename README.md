# Hi There

## Changes from original code?

- We don't have to add the whole chunk of `SVG` right in the `HTML`. Instead, we can get it externally, which keeps the `HTML` clean _and_ lets the browser cache the `SVG`.

```html
<use
  xlink:href="undraw_Ride_a_bicycle_2yok 1.svg#undraw_Ride_a_bicycle_2yok 1"
></use>
```

- Make the `SVG` responsive, because that's the default these days.

Have a look [here](https://antibland.github.io/bikeboy/).
