# [#14. Web Maker Logo](https://cssbattle.dev/play/14)

## Target

![Target](https://cssbattle.dev/targets/14@2x.png)

## My solution

```html
<div></div>
<div></div>

<style>
  body {
    background: #F2F2B6;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  div {
    width: 0px;
    border-left: 75px solid transparent;
    border-right: 75px solid transparent;
    border-top: 130px solid #FF6D00;
    margin: -10px;
    position: relative;
  }
  div::after {
    content: '';
    position: absolute;
    left: -55px;
    top: -130px;
    border-left: inherit;
    border-right: inherit;
    border-top: 130px solid #FD4602;
    z-index: -1;
  }
  div:nth-child(2) {
    scale: -1;
  }
</style>
```

![Solution](/images/14-web-maker-logo.png)
