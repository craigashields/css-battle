# [#16 - Eye of the Tiger](https://cssbattle.dev/play/16)

## Challenge

![](https://cssbattle.dev/targets/16.png)


## Pretty Solution

Characters: 509

```HTML
<p></p>
<p></p>
  <style>
  body{
	display:flex;
    justify-content: center;
    align-items: center;
    background: #0B2429;
  }
  p {
    position:absolute;
    background:#0B2429;
    width: 50px;
    height: 50px;
	border-radius:50%;
    box-shadow: 0 0 0 45px #F3AC3C,0 0 0 65px #0B2429;
  }
    p:nth-of-type(2) {  
    width: 200px;
    height: 200px;
    background: #998235;
    z-index:-1;
    box-shadow: 0 0 0 0;
    border-radius:50% 0 50% 0;
    transform:rotate(45deg);
    }   
</style>
```

## Optimised Solution

Characters: 354

```HTML
<p><p><style>body{display:flex;justify-content:center;align-items:center;background:#0B2429}p{position:absolute;background:#0B2429;width:50;height:50;border-radius:50%;box-shadow:0 0 0 45px #F3AC3C,0 0 0 65px #0B2429}p:nth-of-type(2){width:200;height:200;background:#998235;z-index:-1;box-shadow:0 0 0 0;border-radius:50% 0 50% 0;transform:rotate(45deg)}  
```