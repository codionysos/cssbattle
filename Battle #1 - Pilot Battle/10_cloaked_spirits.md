# Battle #1 - Pilot Battle

## #10 - Cloaked Spirits

![solution](./media/10-cloaked-spirits.png)

```html
<div class="body1"></div>
<div class="body2"></div>
<div class="circle up"></div>
<div class="circle left"></div>
<div class="circle right"></div>
<style>
  body{
    background: #62306D;
  }
  .body1{
    position:absolute;
    width: 300px;
    height: 100px;
    background: #F7EC7D;
    bottom:0px;
    left:50px;
  }
  .body2{
    position:absolute;
    width: 100px;
    height: 200px;
    background: #F7EC7D;
    bottom:0px;
    left:150px
  }
  .circle{
    position: absolute;
    width: 60px;
    height: 60px;
    border-radius: 50%;
  }
  .up{
    left:170px;
    top: 70px;
    background: #AA445F;
    box-shadow: 0px 0px 0px 20px #E38F66;
  }
  .left{
    left:70px;
    bottom:70px;
    background: #E38F66;
    box-shadow: 0px 0px 0px 20px #AA445F;
  }
  .right{
    right:70px;
    bottom:70px;
    background: #E38F66;
    box-shadow: 0px 0px 0px 20px #AA445F;
  }
</style>
```

