# [#10 - Cloaked Spirits](https://cssbattle.dev/play/10)

## Challenge

![](https://cssbattle.dev/targets/10.png)


## Pretty Solution

Characters: 705

```HTML
<div></div>
<div></div>
<p></p>
<p></p>
<p></p>
<style>
  * {
    margin:0;    
  }
  body{
	background:#62306D;
    display:flex;
    justify-content: center;
  }
  div{
    position:absolute;
    width: 6.25rem;
    height: 12.5rem;
    background: #F7EC7D;
    align-self:flex-end;   
    z-index:-1;
  }
	div:nth-of-type(2) {
	position: absolute;
    width: 18.75rem;
    height: 6rem;
    background: #F7EC7D;
	align-self: flex-end;  }  
  p {
    width: 60px;
    height: 60px;
    background:#E38F66;
    border-radius:50%;
    border: 20px solid #AA445F;
    margin-top:150px;
  }
	p:nth-of-type(even) {
    background:#AA445F;   
    border: 20px solid #E38F66;
    margin-top:50px;
  }
</style>
```

## Optimised Solution

Characters: 492

```HTML
<div></div><div></div><p><p><p><style>*{margin:0}body{background:#62306D;display:flex;justify-content:center}div{position:absolute;width:6.25rem;height:12.5rem;background:#F7EC7D;align-self:flex-end;z-index:-1}div:nth-of-type(2){position:absolute;width:18.75rem;height:6rem;background:#F7EC7D;align-self:flex-end}p{width:60;height:60;background:#E38F66;border-radius:50%;border: 20px solid #AA445F;margin-top:150}p:nth-of-type(even){background:#AA445F;border:20px solid #E38F66;margin-top:50}
```