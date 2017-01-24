# Tab-..dom-
1.js切换不同tab显示不同页面的原理是:
 （1）点击时将所有tab的style样式切换成默认，再将点击的tab样式变为高亮<tab1>style1</tab1><tab2>style_default</tab2><tab3>style_default</tab3>
  （2）同时将所有的table内容设为hide，将此tab对应的table设为显示
其实，所有的内容内都在一个html中，由上往下写就行了,<table>show</table><table>hidden</table><table>hidden</table><table>hidden</table>

2.js增加dom节点原理是:
(1)将<span style="cursor:pointer">+</span> ,点击增加时候，用append函数增加节点，只不过把+号改为-号
（2）当删除时候，将此节点remove即可
  