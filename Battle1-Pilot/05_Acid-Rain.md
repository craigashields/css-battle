# [#5 - Acid Rain](https://cssbattle.dev/play/5)

## Challenge

![](https://cssbattle.dev/targets/5.png)


## Pretty Solution

Characters: 402

```HTML
<p></p>
<p></p>
<style>
* {
  background: #0B2429;
}
  p {
    width:120px;
    height:120px;
    background: #F3AC3C;
    border-radius: 11rem 0 11rem 11rem;
    margin-left: 72px;
    margin-top: 150px;
    box-shadow: 60px -60px #998235;
  }
  p:nth-of-type(2) {
  position: relative;
  z-index:-1;
  bottom: 390px;
  left: 120px;
  box-shadow: 0 0 0 0;
  border-radius: 50% 50% 50% 50%;
}
</style>
```

## Optimised Solution

Characters: 297

```HTML
<p></p><p></p><style>*{background:#0B2429}p{width:120;height:120;background:#F3AC3C;border-radius:11rem 0 11rem 11rem;margin-left:72px;margin-top:150px;box-shadow:60px -60px #998235}p:nth-of-type(2){position:relative;z-index:-1;bottom:390px;left:120px;box-shadow:0 0;border-radius:50% 50% 50% 50%}
```