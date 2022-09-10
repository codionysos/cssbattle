# Battle #1 - Pilot Battle

## #4 - Ups n Downs

![solution](./media/4-ups-n-downs.png)

```html
<div class="el up"></div>
<div class="el down right"></div>
<div class="el down left"></div>
<style>
  body{
    background:#62306D;
  }
  .el {
    width: 100px;
    height: 100px;
    background: #F7EC7D;
    position: absolute;
  }
  .up{
    top:50;
    border-radius: 50px 50px 0px 0px;
    left:150px;
  }
  .down {
    bottom: 50px;
    border-radius: 0px 0px 50px 50px;
  }
  .right {
    right: 50px;
  }
  .left {
    left:50px;
  }
</style>
```

