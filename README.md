# hostwinds_issues
记录在使用hostwinds搭建梯子的过程中遇到的问题以及解决方案

---

搭梯子参考的教程：https://github.com/xiaoming2028/FreePAC

---

一些原教程中没提到的问题补充：

1. 在提交订单后，Hostwinds没有直接发送订单成功处理的邮件，而是先发了一个订单正在处理的邮件；从正在处理到处理完成，大约经历了20mins；

2. Xshell连接IP是老是failed？
  主要问题是该IP在国外是可行的，但是在国内被墙了...可以通过[ipchecker](https://www.vps234.com/ipchecker/)来查询IP的国内外访问情况；
  
3. 如果该IP真的被墙了，咋办？
  参考教程：https://www.vps234.com/hostwinds-ip-blocked-fix-isp/
  （大约换了5次ip才换到一个没被墙的/(ㄒoㄒ)/~~）

4. 如有任何其他问题，可以在Hostwinds里咨询右下角的客服，回复速度很快，大概1min之内会给你回复。都有点怀疑是机器人...
