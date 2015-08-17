# Localization
中文: 
http://www.cnblogs.com/unruledboy/p/NetStack.html


# DotNetStack
.NET technology stack, including frameworks, SDKs, tools etc

![Image of The Dot NET Stack](https://raw.githubusercontent.com/unruledboy/DotNetStack/master/preview.png)

# What and why?
Have you ever wondered:
* what technologies .NET really includes? 
* how many do I possess?


I could not find a really comprehensive diagram that shows the .NET technology stack, so I come up with my own version.

There might be issues here and there, like the category, the individual ones, but the beautity is you can modify it as you want.


You can have a graphical preview here (use mouse to move / zoom): 

https://rawgit.com/unruledboy/DotNetStack/master/ux/DotNetStack.htm 


# The .NET Stack

<!--BUILD_START-->

- .NET
	- Common Language Infrastructure (CLI)
	- Common Language Runtime (CLR)
		- Just-In-Time (JIT)
		- Garbage Collector (GC)
			- Object Pinning
			- Generations
				- Gen 0
				- Gen 1
				- Gen 2
		- Memeory Management
			- Stack
			- Managed Heap
				- Large Object Heap
				- Fragmentation
				- Compaction
		- Security
	- Common Type System (CTS)
	- Common Language Specification (CLS)
	- Common Intermediate Language (CIL)
	- .NET Frameworks
		- .NET Framework
			- 1.0
			- 2.0
				- Generics
			- 3.0
				- WPF
				- WCF
				- WF
			- 3.5
				- LINQ
			- 4.0
				- PLINQ
				- TPL
			- 4.5
				- Modern UI
				- async/await
			- 4.6
		- .NET Core
		- Mono
		- DNX (.NET Execution Environment)
		- .NET Micro Framework (MF)
		- .NET Compact Framework (CF)
	- Base Class Library (BCL)
		- System Types
		- Collections
		- Diagnostics
		- Globalization
		- IO
		- Security
		- Threading
		- Text
	- Runtime Infrastructure Library (RIL)
		- System
			- App Domain
			- Pointers
			- Handles
		- Reflection
	- Framework Class Library (FCL)
		- ADO.NET
		- XML
		- Net
		- Drawing
		- LINQ
			- Parallel LINQ (PLINQ)
		- Interoperability (InterOp)
			- Platform Invoke (P/Invoke)
		- Task Parallel Library (TPL)
		- Serialization
	- Core Concepts
		- App Domain
		- Assembly
		- Namespace
		- Code Access Security (CAS)
		- Generics
		- Global Assembly Cache (GAC)
		- Strong Name
		- Weak Reference
		- Event Model
		- Tasked Based Async Model
			- async/await
	- Core Features
		- Language independence
		- Interoperability
		- Portability
	- Core Objects
		- Class
		- Function
		- Property
		- Field
		- Event
		- Types
			- Reference Types
			- Values Types
	- CLI Languages
		- C#
		- VB.NET
		- F#
		- C++/CLI
		- ClojureCLR
		- Fantom
	- Dynamic Language Runtime (DLR)
		- DLR Languages
			- IronPython
			- IronRuby
			- IronScheme
			- IronLisp
	- Desktop
		- GUI
			- Windows Forms
			- Windows Presentation Foundation(WPF)
				- XAML
		- CUI
			- Console
		- Windows Service
	- Web
		- ASP.NET
			- ASP.NET Runtime
			- ASP.NET Web Pages
			- ASP.NET Web Forms
				- Ajax Control Toolkit
			- ASP.NET MVC
				- Razor
				- Routing
		- Silverlight
		- SharePoint
		- IIS
	- SOA
		- ASP.NET Web API
		- ASP.NET Web Services
		- Windows Communication Foundation(WCF)
		- .NET Remoting
	- Open Web Interface for .NET (OWIN)
		- SignalR
		- Nancy
		- Katana
	- SDKs
		- Windows Workflow Foundation (WWF)
		- Managed Extensibility Framework (MEF)
		- Reactive Extensions (Rx)
		- Enterprise Library
	- Development
		- Visual Studio
		- Visual Studio Online
		- Visual Studio Code
		- Blend
		- LightSwitch
		- MonoDevelop
		- SharpDevelop
	- Platforms
		- Windows Runtime (WinRT)
		- Xamarin
		- Universal Apps
			- WinJS
		- .NET Native
		- Windows Phone SDK
		- Azure
	- Productivity
		- Team Foundation Server (TFS)
		- NuGet
		- Chocolatey
		- PowerShell
	- Build
		- MSBuild
		- CodeDom
		- Roslyn
		- CruiseControl.NET
		- csc/vbc/fsc
	- Testing
		- MSTest
		- NUnit
		- Mock
			- Moq
		- Fakes
		- Microsoft Test Manager
	- Deploy/Publish
		- ClickOnce
		- Web/FTP
		- Cloud
		- File
	- Framework (Fx) Tools
		- Ildasm (MSIL Disassembler)
		- NGen (Native Generation, Ahead-Of-Time)
		- sn (Strong Name)
		- gacutil
		- FxCop
	- Data
		- ADO.NET
			- SQL Server
			- Oracle
			- MySQL
			- Sqlite
		- Object/Relationship Mapping (O/RM)
			- Entity Framework
			- NHinbernate
			- AutoMapper
		- NoSQL
			- RavenDB
			- Azure Document DB
		- Cache
			- NCache
	- Components
		- IoC
			- Autofac
			- Unity
			- NInject
			- Windsor
		- Messaging/Queue
			- NServieBus
			- RabbitMQ
			- MassTransit
		- Schedule
			- Quartz.NET

<!--BUILD_END-->