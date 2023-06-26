# [#6. Missing Slice](https://cssbattle.dev/play/6)

## Target

![Target](https://cssbattle.dev/targets/6@2x.png)

## My solution

```html
<div></div>

<style>
  body {
    background: #E3516E;
  }
  div {
    width: 100px;
    height: 100px;
    background: #51B5A9;
    border-radius: 100vw 0 0 0;
    margin: 50px 0 0 92px;
    position: relative;
  }
  div::after, div::before {
    content: '';
    position: absolute;
    width: 100%;
    height: 100%;
    border-radius: inherit;
  }
  div::after {
    background: #FADE8B;
    left: 100%;
    rotate: 90deg;
  }
  div::before {
    background: #F7F3D7;
    top: 100%;
    rotate: -90deg;
  }
</style>
```

![Solution](/images/6-missing-slice.png)
