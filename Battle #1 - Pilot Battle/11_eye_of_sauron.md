# Battle #1 - Pilot Battle

## #11 - Eye of Sauron

![solution](./media/11-eye-of-sauron.png)

```html
<div class="c el"></div>
<div class="c m"></div>
<div class="hf l"></div>
<div class="hf r"></div>
<style>
  body{
    background: #191210;
  }
  .hf{
    position: absolute;
    width: 60px;
    height: 30px;
    top:100px;
    background: #191210;
    border-top-left-radius: 100px;  
    border-top-right-radius: 100px;
    border-left:20px solid #ECA03D;
    border-top:20px solid #ECA03D;
    border-right:20px solid #ECA03D;
  }
  .c{
    position: absolute;
    width: 60px;
    height: 60px;
    top:120px;
    background: #191210;
    border-radius: 50%;
    box-shadow: 0px 0px 0px 20px #ECA03D;
  }
  .el{
    width: 100px;
    height: 100px;
    top:100px;
    left:150px;
  }
  .m{
    left:175px;
    top:125;
    width: 50px;
    height: 50px;
    background: #84271C;
    box-shadow: 0px 0px 0px 25px #191210;
  }
  .l{
    top:150px;
    left:50px;
    transform: rotate(180deg);
  }
  .r{
    right:50px;
  }
</style>
```

