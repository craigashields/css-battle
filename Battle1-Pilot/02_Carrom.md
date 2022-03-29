# [#2 - Carrom](https://cssbattle.dev/play/2)

## Challenge

![](https://cssbattle.dev/targets/2.png)


## Pretty Solution

Characters: 289

```HTML
<p></p>
<p></p>
<p></p>
<p></p>
<style>
  body {
    margin: 0;
    font-size: 0;
  }
  p {
    display: inline-block;
    border: 50px solid #62374e;
    background: #fdc57b;
    width: 50px;
    height: 50px;
  }
  p:nth-of-type(odd) {
    border-right: 150px solid #62374e;
  }
</style>
```

## Optimised Solution

Characters: 184

```HTML
<p><p><p><p><style>body{margin:0;font-size:0}p{display:inline-block;border:50px solid #62374e;background:#fdc57b;width:50;height:50}p:nth-of-type(odd){border-right:150px solid #62374e}
```