# Battle #1 - Pilot Battle

## #7 - Leafy Trail

![solution](./media/8-forking-crazy.png)

```html
<div class="w">
  <div class="s"></div>
  <div class="b"></div>
  <div class="cw">
    <div class="c"></div>
    <div class="c cr"></div>
    <div class="c"></div>
    <div class="c cr"></div>
    <div class="c"></div>
    <div class="c cr"></div>
    <div class="c"></div>
  </div>
</div>
<style>
  body {
    background: #6592CF;
    display: flex;
    justify-content: center;
  }
  .w {
    width: 140px;
    height: 260px;
    position: relative;
    background: #6592CF;
  }
  .s {
    width: 20px;
    height: 70px;
    position: absolute;
    bottom: -40px;
    background: #060F55;
    left: 60px;
  }
  .b {
    width: 140px;
    height: 100px;
    position: absolute;
    bottom: 18px;
    background: #060F55;
    border-radius: 0px 0px 80px 80px;
  }
  .cw {
    margin: 42px auto;
    width: 140px;
    height: 110px;
    display: flex;
    background: #6592CF;
  }
  .c {
    width: 20px;
    background: #060F55;
    border-radius: 20px 20px;
  }
  .cr {
    transform: scaleY(-1);
    background: #6592CF;
  }
</style>
```

