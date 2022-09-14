# Battle #1 - Pilot Battle

## #6 - Missing Slice

![solution](./media/6-missing-slice.png)

```html
<div class="slice green"></div>
<div class="slice yellow"></div>
<div class="slice white"></div>
<style>
  body{
    background:#E3516E;
  }
  .slice {
    position:relative;
    margin: 0 auto;
    width: 100px;
    height: 100px;
  }
  .white{
    background:#F7F3D7;
    border-radius: 0px 0px 0px 100px;
    bottom:58px;
    right:50px
  }
  .green{
    border-radius: 100px 0px 0px 0px;
    background: #51B5A9;
    top:42px;
    right:50px
  }
  .yellow{
    border-radius: 0px 100px 0px 0px;
    background:#FADE8B;
    bottom:58px;
    left:50px
  }
</style>
```

