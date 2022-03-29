# [#12 - Wiggly Moustache](https://cssbattle.dev/play/12)

## Challenge

![](https://cssbattle.dev/targets/12.png)


## Pretty Solution

Characters: 737

```HTML
<p></p>
<p></p>
<p l></p>
<style>
  * {
    margin: 0;
  }
  body{
    display:flex;
    justify-content:center;
    align-items:center;
    background:#F5D6B4;
  }
  p {
    width: 60px;
    height: 60px;
    border-radius:50%;
    border: 20px solid #D86F45;
    border-right-color: transparent;
    border-bottom-color: transparent;
    transform: rotate(45deg);
  }
  p:nth-of-type(odd) {
    transform: rotate(225deg);
    margin-left:-20px;
    margin-right:-20px;
  }
  p:nth-of-type(odd):after
	{
    content:'';
    width: 20px;
    height: 20px;
    background: #D86F45;
    border-radius: 50%;
    position: absolute;
    margin-left:49px;
    margin-top:-8;  
  }
  p[l]:after{
    bottom: -8px;
    left:-57px;
  }
</style>

```

## Optimised Solution

Characters: 507

```HTML
<p></p><p></p><p l></p><style>*{margin:0}body{display:flex;justify-content:center;align-items:center;background:#F5D6B4}p{width:60;height:60;border-radius:50%;border:20px solid #D86F45;border-right-color:#0000;border-bottom-color:#0000;transform:rotate(45deg)}p:nth-of-type(odd){transform:rotate(225deg);margin-left:-20;margin-right:-20;}p:nth-of-type(odd):after{content:'';width:20;height:20;background:#D86F45;border-radius:50%;position:absolute;margin-left:49;margin-top:-8}p[l]:after{bottom:-8;left:-57}
```