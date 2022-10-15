# Battle #1 - Pilot Battle

## #9 - Tesseract

![solution](./media/9-tesseract.png)

```html
<div class="box"></div>
<div class="square"></div>
<div class="circle"></div>
<style>
  body {
    background: #222730;
  }
  div{
    margin: 67px auto;
  }
  .box{
    position: absolute;
    left: 0px;
    width: 400px;
    height: 150px;
    background: #4CAAB3;
  }
  .circle{
    position: absolute;
	left:175px;
    top: 58px;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: #393E46;
  }
  .square{
    position: absolute;
	transform: rotate(45deg);
	box-shadow: 0px 0px 0px 50px #222730;
    left:125px;
    width: 150px;
    height: 150px;
    background: #4CAAB3;
  }
</style>
```

