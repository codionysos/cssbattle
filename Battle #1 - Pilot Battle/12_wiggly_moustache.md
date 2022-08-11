# Battle #1 - Pilot Battle

## #12 - Wiggly Moustache

![solution](./media/12-wiggly-moustache.png)

```html
<div class="c l"></div>
<div class="c r"></div>
<div class="hf m"></div>
<div class="hf l"></div>
<div class="hf r"></div>
<style>
  body{
    background: #F5D6B4;
  }
  .hf{
    position: absolute;
    width: 60px;
    height: 30px;
    top:100px;
    background: #F5D6B4;
    border-bottom-left-radius: 100px;  
    border-bottom-right-radius: 100px;
    border-left:20px solid #D86F45;
    border-bottom:20px solid #D86F45;
    border-right:20px solid #D86F45;
  }
  .m{
	  left:150px;
    transform: rotate(180deg);
  }
  .l{
    left:70px;
 	  top:150px;
  }
  .r{
    right:70px;
    top:150px;
  }
  .c{
    position: absolute;
    top: 140px;
    width: 20px;
    height: 20px;
    border-radius:50%;
    background: #D86F45;
  }
</style>
```

