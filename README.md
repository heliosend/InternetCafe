# InternetCafe
使用了数据库的网吧系统<br>
-------------------------------------<br>
更新日志：2023/6/26 16：04 by helio <br>
1.基于现有的网吧管理系统进行重构和改进<br>
2.根重新构建了一个数据库，这个数据库包含三个张表<br>
  a.用户表    users     {ID,password,balance,discount,computer_ID}<br>
  b.管理员表  admi      {ID,name,number,password}<br>
  c.电脑      computer  {ID,price,CPU,GPU,working,Under repair}<br>

  
更新日志：2023/6/26 21：52 by helio <br>
完成了基本的页面布局；<br>
  将界面分成三个部分：侧边栏Aside，横幅Header以及主要显示界面Main<br>
  最后使用一个Index将其引用起来<br>
  现在已经可以自定义界面内容了，只需要更改按钮文本内容即可<br>


更新日志：2023/6/27 18：57 后端 by wayu <br>
1.根据需求重构数据库，与前端一同确定命名标准<br>
2.根据数据库开发后端代码，实现增删改查接口，并全部测试完毕，与数据库连接正确<br>
3.配置前端环境，准备交互。<br>
