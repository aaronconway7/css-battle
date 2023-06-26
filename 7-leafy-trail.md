# [#6. Leafy Trail](https://cssbattle.dev/play/7)

## Target

![Target](https://cssbattle.dev/targets/7@2x.png)

## My solution

```html
<div></div>

<style>
  body {
    background: #0B2429;
    display: grid;
    place-items: center;
  }
  div, div::before, div::after {
    width: 150px;
    height: 150px;
    background: #998235;
    border-radius: 100px 0 100px 0;
  }
  div::before, div::after {
    content: '';
    position: absolute;
  }
  div::before {
    background: #1A4341;
    margin-left: -50px;
    z-index: -1;
  }
  div::after {
    background: #F3AC3C;
    margin-left: 50px;
  }
</style>
```

![Solution](/images/7-leafy-trail.png)
