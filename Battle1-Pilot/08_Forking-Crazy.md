# [#8 - Forking Crazy](https://cssbattle.dev/play/8)

## Challenge

![](https://cssbattle.dev/targets/8.png)


## Pretty Solution

Characters: 651

```HTML
<p a></p>
<p b></p>
<p c></p>
<style>
  body {
    background:#6592CF;
    display:flex;
    justify-content:center;
  }
  p{
    position:absolute;
    background:#060F55;
  }
  p[a]{
    margin-top:42px;
    margin-left:-120px;
    width:20px;
    height:110px;
    border-radius:100px;
    box-shadow:20px 0 #6592CF,
                40px 0 #060F55,
                60px 0 #6592CF,
      			80px 0 #060F55,
    			100px 0 #6592CF,
      			120px 0 #060F55
}
  p[b]{
	width:140px;
    height:100px;
    margin-top:142px;
    z-index:-2;
	border-radius: 0px 0px 70px 70px;
  }
  p[c]{
	width:20px;
    height:120px;
    margin-top:180px;
  }
</style>
```

## Optimised Solution

Characters: 424

```HTML
<p a><p b><p c><style>body{background:#6592CF;display:flex;justify-content:center}p{position:absolute;background:#060F55}p[a]{margin-top:42;margin-left:-120;width:20;height:110;border-radius:100px;box-shadow:20px 0 #6592CF,40px 0 #060F55,60px 0 #6592CF,80px 0 #060F55,100px 0 #6592CF,120px 0 #060F55}p[b]{width:140;height:100;margin-top:142;z-index:-2;border-radius:0px 0px 70px 70px}p[c]{width:20;height:120;margin-top:180}
```