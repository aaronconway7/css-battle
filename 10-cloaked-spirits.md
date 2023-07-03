# [#10. Cloaked Spirits](https://cssbattle.dev/play/10)

## Target

![Target](https://cssbattle.dev/targets/10@2x.png)

## My solution

```html
<div></div>
<div></div>
<div></div>

<style>
  body {
    background: #62306D;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: flex-end;
  }
  div {
    width: 100px;
    height: 200px;
    background: #F7EC7D;
    position: relative;
  }
  div::after {
    content: '';
    position: absolute;
    width: 100%;
    height: 100px;
    background: #AA445F;
    border-radius: 50%;
    top: -50px;
    border: 20px solid #E38F66;
    box-sizing: border-box;
  }
  div:nth-child(2n+1) {
    height: 100px
  }
  div:nth-child(2n+1)::after {
    background: #E38F66;
    border-color: #AA445F;
  }
</style>
```

![Solution](/images/10-cloaked-spirits.png)
