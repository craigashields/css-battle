# [#9 - Tesseract](https://cssbattle.dev/play/9)

## Challenge

![](https://cssbattle.dev/targets/9.png)


## Pretty Solution

Characters: 479

```HTML
<p></p>
<p></p>
<style>
 body {
   margin:0;
   background:linear-gradient(#222730 25%, #4CAAB3 25% 75% , #222730 50%);
   display:flex;
   justify-content:center;
   align-items:center;
  }
  p{
    position:absolute;
    width:150px;
    height:150px;
    background: #4caab3 padding-box;
    border: 50px solid #222730;
    transform: rotate(45deg);
  }
  p:nth-of-type(2) {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: #393E46;
    border:0;
  }
```

## Optimised Solution

Characters: 353

```HTML
<p></p><p></p><style>body{background:linear-gradient(#222730 25%,#4CAAB3 25% 75%,#222730 50%);display:flex;justify-content:center;align-items:center}p{position:absolute;width:150;height:150;background:#4caab3 padding-box;border:50px solid #222730;transform:rotate(45deg)}p:nth-of-type(2){width:50;height:50;border-radius:50%;background:#393E46;border:0}
```