---
title: 文章demo
date: 2020-04-09
sidebar: false
tags:
 - Vuepress
 - Blog
categories:
 - Vue
publish: false
---

### Badge <Badge text="beta" type="warning"/> <Badge text="默认主题"/>

::: tip
This is a tip
:::

::: warning
This is a warning
:::

::: danger
This is a dangerous warning
:::

::: theorem 牛顿第一定律
假若施加于某物体的外力为零，则该物体的运动速度不变。
::: right
来自 [维基百科](https://zh.wikipedia.org/wiki/%E7%89%9B%E9%A1%BF%E8%BF%90%E5%8A%A8%E5%AE%9A%E5%BE%8B)
:::

@flowstart
st=>start: Start|past:>https://flowchart.vuepress.ulivz.com/[blank]
e=>end: End|future:>https://flowchart.vuepress.ulivz.com/
op1=>operation: My Operation|past
op2=>operation: Stuff|current
sub1=>subroutine: My Subroutine|invalid
cond=>condition: Yes
or No?|approved:>https://flowchart.vuepress.ulivz.com/
c2=>condition: Good idea|rejected
io=>inputoutput: catch something...|future

st->op1(right)->cond
cond(yes, right)->c2
cond(no)->sub1(left)->op1
c2(yes)->io->e
c2(no)->op2->e
@flowend