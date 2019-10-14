##

```
1. MVVM
   Model      业务领域的对象和数据操作，KO通常是使用Ajax向服务器请求数据读写这个数据模型
   ViewModel  纯粹用于描述数据内容和页面操作的数据模型
              用户当前使用的为保存的数据
              KO时，ViewModel数据模型是纯粹的不包含HTML知识的js对象
   View       代表ViewModel状态的一个可见，互动的UI界面
              主要用于显示ViewModel的数据信息，发送用户命令
              KO，将HTML文档声明式的绑定到ViewModel，将它们关联起来
              js一个对象

2.一般数据绑定有三种
  One-Time 绑定模式 从viewModel绑定至UI这一层只进行一次绑定，不会追踪两者之间任何一方的变化
  一般用于报表，数据仅仅会加载一次
 
  One-Way绑定模式即单向绑定object-UI，viewModel中的数据发生变化，UI中的数据也将会发生变化
  在knockout不存在单向绑定

  Two-Way 双向绑定，数据Object或者UI中发生变化，应用程序将会更新另一方
  ko.observable定义的说明是双向绑定
  
************************************************************


```
