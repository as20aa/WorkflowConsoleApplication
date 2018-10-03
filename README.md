# c# workflow sample
一个使用c# workflow fundation 创建的一个工作流程序。
# Tips
按照官方教程进行创建，其中在填写和设置workflow时，出现了部分的bug，这里提醒注意一下
* workflow designer中需要对prompt中的几个输入变量进行初始化，具体的做法是在workflow中右键点击prompt，选择属性，并在属性窗口对几个输入参数进行初始化
* 结束时会输出turns，这个需要在整个的flowchart中设定参数，并且设置turns为输出类型，int32数据类型。