# [#5. Acid Rain](https://cssbattle.dev/play/5)

## Target

![Target](https://cssbattle.dev/targets/5@2x.png)

## My solution

```html
<div></div>

<style>
  body {
    background: #0B2429;
    display: grid;
    place-items: center;
  }
  div {
    width: 120px;
    height: 120px;
    background: #998235;
    border-radius: 50% 0 50% 50%;
    position: relative;
  }
  div::before, div::after {
    content: '';
    position: absolute;
    background: #F3AC3C;
    width: 100%;
    height: 100%;
  }
  div::before {
    border-radius: inherit;
    inset: 60px 0 0 -60px;
  }
  div::after {
    border-radius: 50%;
    inset: -60px 0 0 60px;
    z-index: -1;
  }
</style>
```

![Solution](/images/5-acid-rain.png)
