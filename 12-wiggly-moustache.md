# [#12. Wiggly Moustache](https://cssbattle.dev/play/12)

## Target

![Target](https://cssbattle.dev/targets/12@2x.png)

## My solution

```html
<div></div>
<div></div>
<div></div>

<style>
  body {
    background: #F5D6B4;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  div {
    width: 60px;
    height: 30px;
    border-radius: 100px 100px 0 0;
    border: 20px solid #D86F45;
    border-bottom: 0;
  }
  div:nth-of-type(odd) {
    scale: -1;
  }
  div:nth-of-type(odd)::after {
    content: '';
    position: absolute;
    top: 100%;
    height: 10px;
    width: 20px;
    background: #D86F45;
    border-radius: 100vw 100vw 0 0;
    scale: -1;
  }
  div:nth-of-type(1) {
    translate: 20px 25px;
  }
  div:nth-of-type(1)::after {
    left: 100%;
  }
  div:nth-of-type(2) {
    margin-top: -50px;
  }
  div:nth-of-type(3) {
    translate: -20px 25px;
  }
  div:nth-of-type(3)::after {
    right: 100%;
  }
</style>
```

![Solution](/images/12-wiggly-moustache.png)
