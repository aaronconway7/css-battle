# [#9. Tesseract](https://cssbattle.dev/play/9)

## Target

![Target](https://cssbattle.dev/targets/9@2x.png)

## My solution

```html
<div class="banner">
  <div class="square">
    <div class="circle"></div>
  </div>
</div>

<style>
  body {
    background: #222730;
    margin: 0;
    display: grid;
    place-items: center;
  }
  .banner,
  .square {
    background: #4caab3;
  }
  .banner {
    width: 100%;
    height: 150px;
  }
  .square {
    width: 150px;
    height: 150px;
    rotate: 45deg;
    margin: 0 auto;
    outline: 50px solid #222730;
    display: grid;
    place-items: center;
  }
  .circle {
    width: 50px;
    height: 50px;
    background-color: #393e46;
    border-radius: 50%;
  }
</style>
```

![Solution](/images/9-tesseract.png)
