# GradeManagement 学生成绩管理系统
算法与数据结构小学期的任务  
python，tkinter可视化  
1 问题描述:   
利用python，通过可视化窗口，实现下面的功能：   
1）主窗口界面用来调用各个功能；   
2）添加功能，添加学生信息，课程信息，成绩信息，并保存到文件中；   
3）查询功能：a、能够根据学号/查询学生成绩信息   
             b、查询结果保存到指定文件   
4）修改成绩记录   
5）删除成绩记录   
2 需求分析   
1)借助python的tkinter实现可视化   
2)添加功能：在输入框输入相关信息，点击添加按钮，首先对输入信息进行相关验证。添加学生时要求学号为8位，且与当前文件中的信息不重复；添加课程时要求课程号不重复；添加成绩信息时要求输入的学号和课程号是有效的并且成绩信息唯一。   
3)查询功能：可以通过学号，课程号，班级号多个条件进行查询，查询结果以列表形式显示在下方。点击保存按钮可将查询到的结果保存，文件名和保存位置可自定。   
4)修改功能：在查询到成绩信息时，双击列表中某信息进入新的窗口，提供基本信息查看功能和修改删除成绩记录的功能   
