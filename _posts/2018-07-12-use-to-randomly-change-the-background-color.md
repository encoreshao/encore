---
title: 如何使用CSS随机改变document的背景颜色
---

如何使用CSS随机改变body的背景颜色

```
body {
     background-color: #fff;
     -webkit-animation: random 5s infinite;
     animation: random 5s infinite;
}
@keyframes  random {
    15% { background-color: red; } 
    30% { background-color: yellow; } 
    45% { background-color: green; } 
    60% { background-color: blue; }
    75% { background-color: white; }  
}

/*
@keyframes mymove{
    form{background-color: #38dc58; }
    to{background-color: #9b40f1;}
}
YOU CAN USE LIKE IT TOO :d
*/

div
{
  background:#debe94;
  width:100px;
  height:100px;
  transition: all 0.3s ease-out;
}
```