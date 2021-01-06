SDL-Studio-Community-Toolkit
===========

SDL Studio社区工具包是帮助程序功能的集合。它简化并演示了构建SDL Studio插件的常见开发人员任务。
## 支持平台

* .NET 4.5 (Desktop / Server)
* Windows 7/8 / 8.1 / 10商店应用
* SDL Studio 2017或更高版本

## 入门

该库建立在SDL Studio API之上，因此使用它们还需要安装SDL Studio。

1. 安装Visual Studio 2013或2015。社区版可在[此处](https://www.visualstudio.com/)免费获得。

2. 为现有的SDL Studio插件打开解决方案或创建一个新的插件。

3. 在“解决方案资源管理器”面板中，右键单击您的项目名称，然后选择“**管理NuGet软件包”** 。搜索**Sdl.Community.Toolkit** ，然后从列表中选择所需的[NuGet软件包](https://www.nuget.org/packages?q=Sdl.Community.Toolkit)。

![管理Nuget软件包](https://github.com/sdl/SDL-Studio-Community-Toolkit/blob/master/Resources/ManageNugetPackages.png)

4. 在您的C＃类中，将名称空间添加到工具箱中，例如：

```C＃使用Sdl.Community.Toolkit.Integration ```

5. 对现有的API类使用扩展。

## Nuget软件包

NuGet是Visual Studio中内置的.NET应用程序的标准程序包管理器。从打开的解决方案中选择“*工具”*菜单，“ *NuGet软件包管理器”* ，“*为解决方案管理NuGet软件包...”*以打开UI。在下面输入软件包名称之一以在线搜索。

![社区工具包Nuget软件包](https://github.com/sdl/SDL-Studio-Community-Toolkit/blob/master/Resources/nuget-packages.png)

| NuGet软件包名称|说明| | --- | --- | | [Sdl.Community.Toolkit.Core](https://www.nuget.org/packages/Sdl.Community.Toolkit.Core/) | NuGet软件包包括Studio版本的帮助程序方法。 | | [Sdl.Community.Toolkit.FileType](https://www.nuget.org/packages/Sdl.Community.Toolkit.FileType/) | NuGet软件包，其中包括用于[FileType支持框架](http://producthelp.sdl.com/SDK/FileTypeSupport/4.0/html/1f5584af-9763-46ff-894b-08127a2421a7.htm)类的辅助方法，例如ISegment，ISegmentPairs或ITranslationOrigin。 | | [Sdl.Community.Toolkit.ProjectAutomation](https://www.nuget.org/packages/Sdl.Community.Toolkit.ProjectAutomation/) | NuGet软件包，其中包括[ProjectAutomation API](http://producthelp.sdl.com/SDK/ProjectAutomationApi/4.0/html/b986e77a-82d2-4049-8610-5159c55fddd3.htm)类的帮助方法，例如ProjectTemplateInfo。 | | [Sdl.Community.Toolkit.ProjectAutomation](https://www.nuget.org/packages/Sdl.Community.Toolkit.Integration/) | NuGet软件包，其中包括用于[Integration API](http://producthelp.sdl.com/SDK/StudioIntegrationApi/4.1/html/135dcb1c-535b-46a9-8063-b83be4a06d82.htm)类的辅助方法，例如DisplayFilterRowInfo或Document。 |

## 特征
* 用于FileTypeSupport框架的帮助程序功能
* 用于使用ProjectAutomation API的辅助函数
* 与Integration API配合使用的辅助函数
* 用于处理SDL Studio版本控制的帮助程序功能

## 反馈和要求

请使用[GitHub问题](https://github.com/sdl/SDL-Studio-Community-Toolkit/issues)来提问或发表评论。

## 贡献
你想做出贡献？这是我们的[贡献准则](https://github.com/sdl/SDL-Studio-Community-Toolkit/blob/master/contributing.md)。

## 原则

 - 原则1：该工具包将保持简单。
 - 原则2：一旦SDL Studio中提供了类似功能，它将被标记为已弃用。
 - 原则3：所有功能都将在最新的SDL Studio发布周期中得到支持，或者直到被其他原理取代为止。
