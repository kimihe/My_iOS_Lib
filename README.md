###改进的带小数点的数字键盘

**规范用户输入，强化排错，主要说明如下：**

	1.小数点个数不能超过1个，已经有了小数点则再点击小数点，不会输入进去。
    2.若以小数点开头，责备自动前插一个0补全。
    3.小数点前如果有多个零，视为一个零，即000000.2视为0.2。
    4.以小数点结尾的数字，小数部分视为0，即2.视为2.0。
    5.默认小数精度为1位，可根据需要修改。
    6.demo中上方淡灰色为Label，用于反馈经处理的结果。下方的深灰色为textField，表示当前输入的字符串。
    7.实际运用中可以类似地用一个textField输入，一个Label来显示结果。
  
**欢迎更新~**
