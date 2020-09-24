---
title:编写使用Winform控件流程
---

 Inherit from Existing Windows Forms Controls 
 从现有的WinFrom控件中进行集成，具体的操作步骤如下：

### 基本步骤

*  In Visual Studio, create a new **Windows Forms Application project** or **Windows Form Control Library Project**
    创建Winform应用工程或创建Winform控件库工程
* From the Project menu, choose Add New Item  -- 打开 Project 菜单，选择 Add New Item
* In the Add New Item dialog box, double-click Custom Control -- 在Add New Item窗口中，选择Custom Control
* Locate the class declaration, which inherits from Control  -- 在类定义文件中，可以发现是从Control继承的
* Change the base class to the control that you want to inherit from -- 改变继承基类，从现有控件中继承（如Button）
>>public partial class CustomControl1 : System.Windows.Forms.Button
* Implement any custom methods or properties that your control will incorporate  -- 在继承的类中实现方法和属性
* If you want to modify the graphical appearance of your control, override the OnPaint method -- 需要的话在OnPaint中实现重绘

操作的步骤如下图所示:


### 测试方法



