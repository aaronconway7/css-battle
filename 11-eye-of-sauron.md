# [#11. Eye of Sauron](https://cssbattle.dev/play/11)

## Target

![Target](https://cssbattle.dev/targets/11@2x.png)

## My solution

```html
<div></div>
<div></div>
<div></div>

<style>
  body {
    background: #191210;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
  }
  div {
    width: 50px;
    height: 50px;
    background: #84271C;
    border-radius: 50%;
    border: 25px solid #191210;
    outline: 20px solid #ECA03D;
  }
  div:nth-child(2n+1) {
    width: 60px;
    height: 30px;
    background: #191210;
    z-index: -1;
    border: none;
    border-radius: 0 0 100vw 100vw;
    margin-top: 30px;
    outline-color: #ECA03D;
  }
  div:nth-child(2n+1):before {
    content: '';
    display: block;
    position: relative;
    width: 90px;
    height: 20px;
    background: #191210;
    margin: -20px;
  }
  div:nth-child(3) {
    border-radius: 100vw 100vw 0 0;
    margin-top: -30px;
  }
  div:nth-child(3):before {
    margin: 30px 0 0 -10px;
  }
</style>
```

![Solution](/images/11-eye-of-sauron.png)
