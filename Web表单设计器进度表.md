# Web表单设计器进度表

**问题** 

> 一、表单保存后竖排变横排
> 雷劈模板保存之后，重新修改保存，会出现竖排变横排的现象，现在的解决办法是每次修改保存之前都要把需要竖排的设置为竖排再保存。
> 二、选择雷劈表单控件编写控件内容（单选，多选、文本框、输入框），编辑完成点击确定，编辑的内容没有显示。
> 解决的办法的再编辑一遍，直到页面显示为止。
> 三、雷劈编辑的过程中在A行进行改动，结果显示在B行
> 现在的解决办法是继续添加，直到对为止。
> 四、表单保存后内容错乱
> 在雷劈编辑一个网页的时候好好的，保存之后再次查看发现内容错乱，比如单选框变为多选框，位置不对。
> 五、雷劈设计的表单保存之后内容没有问题，但是回显有问题
> 比如单选变成多选，多选选择对个只显示其中一两个，甚至不显示。现在的解决办法是删除回显有错误的行，重新增加行添加控件，直到ok为止。
> 六、回显问题：模板中多选选项出现“&”特殊符号，则该选项回显必有问题；
> 现在的解决办法是把&替换为空格获取文字，估计跟正则表达式有关。   

- 12.19周一

  > - 下午：规划工作进度
  > - 夜：阅读addTVTemplet和updataTVTemplet.jsp的源码，了解页面结构

- 12.20周二

  > - 源码阅读：leipi.form.TVTemplet.js和radio_checkbox_select.js
  > - 明确表单所存在问题的源码位置，规划如何修改各种问题，出一个更详细的推进表

- 12.21周三

  > - 发现问题二，打算花一天处理这两个问题
  > - 继续探明其他问题的原因

- 12.22周四

  > - 问题二和问题六的解决
ok

- 12.23周五

  > - 问题六解决

- 12.24周六

  > - 问题一解决
  > - 开会，发现问题所在，继续努力

- 12.26-12.31

  > - 剩余三个bug，根据前一个星期的进度，来修订新的进度表

  > 存在问题，解决不出，需要时间debug
  >
  > ​

- 12.26
  > vue解决
  
 
  
  
