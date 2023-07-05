# [#16. Eye of the Tiger](https://cssbattle.dev/play/16)

## Target

![Target](https://cssbattle.dev/targets/16@2x.png)

## My solution

```html
<div class="eye">
  <div class="pupil"></div>
</div>

<style>
  body {
    background: #0b2429;
    display: grid;
    place-items: center;
  }
  .eye {
    width: 200px;
    height: 200px;
    background: #998235;
    border-radius: 50% 0;
    rotate: 45deg;
    display: grid;
    place-items: center;
  }
  .pupil {
    height: 50px;
    width: 50px;
    background: #0b2429;
    border-radius: 50%;
    border: 45px solid #f3ac3c;
    outline: 20px solid #0b2429;
  }
</style>
```

![Solution](/images/16-eye-of-the-tiger.png)
