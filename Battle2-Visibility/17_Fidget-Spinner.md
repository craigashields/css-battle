# [#17 - Fidget Spinner](https://cssbattle.dev/play/17)

## Challenge

![](https://cssbattle.dev/targets/17.png)


## Pretty Solution

Characters: 449 (excluding the comments as I needed these to keep track!)

Started experimenting with radial gradients, it was immensely useful and I may go back and try it with some other challenges. 

```HTML
<p></p>
<style>
  body {
    	background:radial-gradient(#E78481 45px,0,#09042A);
	  }
  p {
    position:absolute;
    margin:112 0 0 102;
    border-radius:50%;
    height:60px;
    width:60px;
    color:#09042A;
    box-shadow:inset 0 96px, /* Left inner circle */
               0 0 0 10px #E78481, /* Left outer circle */
      		     60px 53px #F5BB9C, /* Bottom inner circle */
		           60px 53px 0 10px, /* Bottom outer circle */
		           60px -53px #F5BB9C, /* Top inner circle */
      		     60px -53px 0 10px, /* Top outer circle */
		           120px 0, /* Right inner circle */
		  	       120px 0 0 10px #E78481 /* Right outer circle */       
      		   
  }
```

## Optimised Solution

Characters: 306

```HTML
<p><style>body{background:radial-gradient(#E78481 45px,0,#09042A)}p{position:absolute;margin:112 0 0 102;border-radius:50%;height:60px;width:60px;color:#09042A;box-shadow:inset 0 96px,0 0 0 10px #E78481,60px 53px #F5BB9C,60px 53px 0 10px,60px -53px #F5BB9C,60px -53px 0 10px,120px 0,120px 0 0 10px #E78481}
```