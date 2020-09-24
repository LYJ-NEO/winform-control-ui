---
title:custom-control-painting-and-rendering
---

Custom painting of controls is one of the many complicated tasks made easy by the .NET Framework. When authoring a custom control, you have many options regarding your control's graphical appearance. If you are authoring a control that inherits from the Control, you must provide code that allows your control to render its graphical representation. If you are creating a user control by inheriting from the UserControl, or are inheriting from one of the Windows Forms controls, you may override the standard graphical representation and provide your own graphics code. If you want to provide custom rendering for the constituent controls of a UserControl you are authoring, your options become more limited, but still allow a wide range of graphical possibilities for your controls and applications

控件的自定义绘制是 .NET Framework 轻松完成的许多复杂任务之一。创作自定义控件时，有关控件的图形外观有许多选项。如果要创作从 继承的控件，则必须提供允许控件呈现其图形表示的代码。如果要通过继承 来创建用户控件，或者从 Windows 窗体控件之一继承用户控件，可以重写标准图形表示形式并提供自己的图形代码。如果要为正在创作的组成部分控件提供自定义呈现，则您的选项将变得更加有限，但仍允许控件和应用程序具有广泛的图形可能性。
