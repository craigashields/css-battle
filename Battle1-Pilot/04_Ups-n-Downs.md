# [#4 - Ups n Downs](https://cssbattle.dev/play/4)

## Challenge

![](https://cssbattle.dev/targets/4.png)


## Pretty Solution

Characters: 347

```HTML
<div id="f"></div>
<div></div>
<div id="f"></div>
<style>
  body {
    background: #62306d;
    display: flex;
    justify-content: center;
  }
  div {
    margin-top: 42px;
    width: 100px;
    height: 100px;
    background: #f7ec7d;
    border-radius: 10rem 10rem 0 0;
  }
  #f {
    transform: scale(1, -1);
    margin-top: 142px;
  }
</style>
```

## Optimised Solution

Characters: 238

```HTML
<div f></div><div></div><div f></div><style>body{background:#62306d;display:flex;justify-content:center}div{margin-top:42;width:100;height:100;background:#f7ec7d;border-radius:10rem 10rem 0 0}div[f]{transform:scale(1, -1);margin-top: 142}
```