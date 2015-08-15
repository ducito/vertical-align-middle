#Vertical Align Middle

![](imgs/img.jpg?raw=true)

```
.selector{
   position: relative;
   top: 50%;
   transform: translateY(-50%);
}
```

Anything vertical align middle using only just three line css code. There are many methods for vertical middle, but that all some limitation. For example, if we use text for line-height this work, but only for one line text to sets vertical center. Also one is top 50% and minus half margin of element height, but here element height fixed.
But only three line css code thought set element vertical middle and not need to define element height. Here first set the element position relative so we can set its position thought top and left. Then set top 50% so element position set his parent  height of 50%. Now we only need to minus element half height as defined above minus margin but in margin method we need to define height of the element.
But if set transform to translateY(-50%) it’s auto detect element height and set his position to his half height above actual position. If you say it’s get minus half margin of his height it’s not wrong.