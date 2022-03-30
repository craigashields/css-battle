# [#14 - Web Maker Logo](https://cssbattle.dev/play/14)

## Challenge

![](https://cssbattle.dev/targets/14.png)


## Pretty Solution

Characters: 512

```HTML
<p></p>
<p></p>
<style>
  body{
	margin:0;    
    background:#F2F2B6;
  }
  p {
    position:absolute;
    margin-top:85px;
    margin-left:60px;
    width: 0;
    height: 0;
	border-style: solid;
	border-width: 130px 75px 0 75px;
	border-color: #FF6D00 #0000 #0000 #0000;
    filter: drop-shadow(20px 0 0 #FD4602);
  }
    p:nth-of-type(2) {
      margin-left:170px;
      transform:rotate(180deg);
	    border-color: #FD4602 #0000 #0000 #0000;
      filter: drop-shadow(-20px 0 0 #FF6D00);        
  }
</style>
```

## Optimised Solution

Characters: 370

```HTML
<p><p><style>body{margin:0;background:#F2F2B6}p{position:absolute;margin-top:85;margin-left:60;width:0;height:0;border-style:solid;border-width:130 75 0 75;border-color: #FF6D00 #0000 #0000 #0000;filter:drop-shadow(20px 0 0 #FD4602)}p:nth-of-type(2){margin-left:170;transform:rotate(180deg);border-color:#FD4602 #0000 #0000 #0000;filter: drop-shadow(-20px 0 0 #FF6D00)}
```