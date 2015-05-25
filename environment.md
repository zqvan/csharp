# C\# 环境

在这一章中，我们将讨论创建 C\# 编程所需要的工具。我们已经提到过 C\# 是 .Net 框架的一部分，
且用于编写 .Net 应用程序。因此，在讨论运行一个 C\# 程序的可用工具之前，让我们先了解一下 C# 与 .Net 框架之间的关系。

## .Net 框架
.Net 框架是一个革命性的平台，能帮您编写出下面类型的应用程序：

- Windows 应用程序
- Web 应用程序
- Web 服务

.Net 框架应用程是多平台的应用程序。框架的设计方式使它适用于下列各种语言：C# 、C++ 、Visual Basic 、Jscript 、COBOL 等等。所有这些语言可以访问框架，并且彼此之间可以互相交互。

.Net 框架由一个巨大的代码库组成，用于 C# 等客户端语言。下面列出一些 .Net 框架的组件：

- 公共语言运行库（Common Language Runtime - CLR）
- .Net 框架类库（.Net Framework Class Library）
- 公共语言规范（Common Language Specification）
- 通用类型系统（Common Type System）
- 元数据（Metadata）和组件（Assemblies）
- Windows 窗体（Windows Forms）
- ASP.Net 和 ASP.Net AJAX
- ADO.Net
- Windows 工作流基础（Windows Workflow Foundation - WF）
- Windows 显示基础（Windows Presentation Foundation）
- Windows 通信基础（Windows Communication Foundation - WCF）
- LINQ

如需了解每个组件的功能，请参阅 [ASP.Net - Introduction](http://www.tutorialspoint.com/asp.net/asp.net_introduction.htm) ，更详细的信息，请参阅微软（Microsoft）的文档。

## C\# 的集成开发环境 ( IDE )

微软提供了下列用于 C# 编程的开发工具：

- Visual Studio 2010 (VS)
- Visual C# 2010 Express (VCE)
- Visual Web Developer

后面两个是免费使用的，可从微软官方网址下载。使用这些工具，您可以编写各种 C# 程序，
从简单的命令行应用程序到更复杂的应用程序。您也可以使用基本的文本编辑器编写 C# 源代码文件，比如 Notepad ，并使用命令行编译器（.NET 框架的一部分），编译代码成组件。

Visual C# Express 和 Visual Web Developer Express 版本是 Visual Studio 的定制版本，且具有相同的外观和感观。它们保留 Visual Studio 的大部分功能。
在本教程中，我们使用的是 Visual C# 2010 Express。

您可以从 [Microsoft Visual Studio](http://www.microsoft.com/visualstudio/eng/downloads) 上进行下载。它会自动安装在您的机器上。请注意，您在完成速成版的安装时需要提供一个可用的网络连接。

## 在 Linux 或 Mac OS 上编写 C# 程序

虽然 .NET 框架是运行在 Windows 操作系统上，但是也有一些运行于其它操作系统上的版本可供选择。 **Mono** 是 .NET 框架的一个开源版本，
它包含了一个 C# 编译器，且可运行于多种操作系统上，比如各种版本对 Linux 和 Mac OS 的支持。如需了解更多详情，请访问 [Go Mono](http://www.go-mono.com/mono-downloads/download.html) 。

Mono 的目的不仅仅是跨平台地运行微软 .NET 应用程序，而且也为 Linux 开发者提供了更好的开发工具。
Mono 可运行在多种操作系统上，包括 Android、BSD、iOS、Linux、OS X、Windows、Solaris 和 UNIX。
