# [#9 - Tesseract](https://cssbattle.dev/play/9)

## Challenge

![](https://cssbattle.dev/targets/9.png)


## Pretty Solution

Characters: 690

```HTML
<div id="r">
  <div id="s"><div id="c"></div></div>
</div>
<style>
  body {
    margin: 0;
    background: #222730;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  #r {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 50%;
    background: #4caab3;
  }
  #s {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 150;
    height: 150px;
    background: #4caab3 padding-box;
    border: 50px solid #222730;
    transform: rotate(45deg);
  }
  #c {
    width: 33%;
    height: 33%;
    border-radius: 50%;
    background: #393e46;
  }
</style>
```

## Optimised Solution

Characters: 470

```HTML
<div id="r"><div id="s"><div id="c"></div></div></div><style>
body{margin:0;background:#222730;display:flex;justify-content:center;align-items:center}#r{display:flex;justify-content:center;align-items:center;width:100%;height:50%;background:#4caab3}#s{display:flex;justify-content:center;align-items:center;width:150;height:150;background:#4caab3 padding-box;border:50px solid #222730;transform:rotate(45deg)}#c{width:33%;height:33%;border-radius:50%;background:#393e46}
```