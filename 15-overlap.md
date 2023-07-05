# [#15. Overlap](https://cssbattle.dev/play/15)

## Target

![Target](https://cssbattle.dev/targets/15@2x.png)

## My solution

```html
<div></div>
<div></div>

<style>
  body {
    background: #09042A;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  div {
    width: 150px;
    height: 150px;
    background: #7B3F61;
    border-radius: 50%;
    margin: -25px;
    position: relative;
  }
  div:nth-child(2) {
    background: #E78481;
    overflow: hidden;
  }
  div:nth-child(2)::after {
    content: '';
    position: absolute;
    left: -100;
    top: 0;
    height: 100%;
    width: 100%;
    background: #09042A;
    border-radius: 50%;
  } 
</style>
```

![Solution](/images/15-overlay.png)
