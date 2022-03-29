# [#11 - Eye of Sauron](https://cssbattle.dev/play/11)

## Challenge

![](https://cssbattle.dev/targets/11.png)


## Pretty Solution

Characters: 604

```HTML
<p>
<style>
  body{
	display:flex;
    justify-content: center;
    align-items: center;
    background: #191210;
  }
  p {
    width: 50px;
    height: 50px;
    background:#84271C;
	border-radius: 50%;
    box-shadow: 0 0 0 25px #191210,0 0 0 45px #ECA03D;
  }
  p:before,p:after{
    content:'';
    position:absolute;
	bottom:100px;
    left:50px;
    height:60px;
    width:60px;
    border-radius:50%;
    border: 20px solid #ECA03D;
    border-top-color: #0000;
    border-left-color: #0000;
    transform:rotate(45deg);
  }
  p:after{
    left:250px;
    transform:rotate(225deg);
  }
  </style>
```

## Optimised Solution

Characters: 438

```HTML
<p><style>body{display:flex;justify-content:center;align-items:center;background:#191210}p{width:50;height:50;background:#84271C;border-radius:50%;box-shadow:0 0 0 25px #191210,0 0 0 45px #ECA03D}p:before,p:after{content:'';position:absolute;bottom:100;left:50;height:60;width:60;border-radius:50%;border:20px solid #ECA03D;border-top-color:#0000;border-left-color:#0000;transform:rotate(45deg)}p:after{left:250;transform:rotate(225deg)}
```