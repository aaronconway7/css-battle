# [#8. Forking Crazy](https://cssbattle.dev/play/8)

## Target

![Target](https://cssbattle.dev/targets/8@2x.png)

## My solution

```html
<div class='base'>
  <div class='prong'></div>
  <div class='prong'></div>
  <div class='prong'></div>
  <div class='prong'></div>
</div>
<div class='handle'></div>

<style>
  body {
    background: #6592CF;
    margin: 0;  
  }
  div {
    background: #060F55;
  }
  .base {
    width: 140px;
    height: 100px;
    border-radius: 0 0 100vw 100vw;
    margin: 150px auto 0;
    display: flex;
    justify-content: space-between;
    gap: 10px;
  }
  .handle, .prong {
    width: 20px;
    height: 110px;
    margin: -10px auto;
    border-radius: 100vw;
  }
  .prong {
    margin: -100px 0;
    position: relative;
  }
  .prong::after {
    content: '';
    position: absolute;
    height: 100%;
    width: 100%;
    background: #6592CF;
    border-radius: inherit;
    left: 100%;
  }
</style>
```

![Solution](/images/8-forking-crazy.png)
