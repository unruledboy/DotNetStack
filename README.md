# Overflow Stack
The overflow stack family (Web Front End Stack, Database Stack, .NET Stack etc.):
http://overflowstack.github.io

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

- [.NET](http://www.microsoft.com/net)
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
		- [C#](https://msdn.microsoft.com/en-us/library/67ef8sbd.aspx)
		- [VB.NET](https://msdn.microsoft.com/en-us/library/2x7h1hfk.aspx)
		- [F#](http://fsharp.org/)
		- [C++/CLI](https://en.wikipedia.org/wiki/C%2B%2B/CLI)
		- [ClojureCLR](https://github.com/clojure/clojure-clr)
		- [Fantom](http://fantom.org/)
		- [Visual COBOL](http://www.microfocus.com/products/micro-focus-developer/visual_cobol/)
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
				- HttpHandler
				- HttpModule
			- ASP.NET Web Pages
			- ASP.NET Web Forms
				- Core Objects / Concepts
					- Web Form
					- Web Controls
					- Postback
					- Session
					- View State
				- Ajax Control Toolkit
			- ASP.NET MVC
				- MVC
					- Model
					- View
					- Controller
				- View Engines
					- Razor
					- Web Forms
					- Custom
				- Core Objects / Concepts
					- Routing
					- Controller
					- Action
					- Filter
		- Silverlight
		- SharePoint
		- IIS
	- SOA
		- ASP.NET Web API
			- REST (Representational State Transfer)
			- CRUD
				- GET: SELECT
				- POST: CREATE
				- PUT: UPDATE
				- DELETE: DELETE
			- Consumers
				- HttpClient
				- RestSharp
			- Media Formatters
				- XML
				- JSON
				- BSON
				- Custom
			- Core Concepts
				- By Convention
				- Routing
				- Content Negotiation
				- Model Validation
				- Model Binding
				- Hosting
			- Core Objects
				- Api Controller
				- Action
				- HTTP Message Handler
				- Filter
		- ASP.NET Web Services
			- Core Objects
				- WebService
				- WebMethod
			- File Types
				- XML (Extensible Markup Language)
				- SOAP (Simple Object Access Protocol)
				- WSDL (Web Services Description Language)
				- UDDI (Universal Description, Discovery, and Integration)
		- Windows Communication Foundation (WCF)
			- ABC
				- Address
				- Binding
				- Contract
			- Bindings
				- BasicHttpBinding
				- WsHttpBinding
				- WsDualHttpBinding
				- WsFederationHttpBinding
				- NetNamedPipeBinding
				- NetTcpBinding
				- NetPeerTcpBinding
				- NetMsmqBinding
			- Contrats
				- Data Contract
				- Service Contract
				- Operation Contract
				- Message Contract
		- [AppFabric](https://en.wikipedia.org/wiki/AppFabric)
			- Persistence
			- Hosting
			- Monitoring
			- Caching
		- .NET Remoting
	- [Open Web Interface for .NET (OWIN)](http://owin.org/)
		- SignalR
		- Nancy
		- Katana
	- SDKs
		- [Windows Workflow Foundation (WWF)](https://msdn.microsoft.com/en-us/vstudio/jj684582.aspx)
		- [Managed Extensibility Framework (MEF)](https://msdn.microsoft.com/en-us/library/dd460648(v=vs.110).aspx)
		- [Reactive Extensions (Rx)](https://github.com/Reactive-Extensions)
		- Enterprise Library ;-)
	- Development
		- [Visual Studio](https://www.visualstudio.com/)
		- [Visual Studio Online](https://www.visualstudio.com/en-us/products/what-is-visual-studio-online-vs.aspx)
		- [Visual Studio Code](https://code.visualstudio.com/)
		- [Blend](https://msdn.microsoft.com/en-us/library/jj171012.aspx)
		- [LightSwitch](https://msdn.microsoft.com/en-us/library/lightswitch.aspx)
		- [MonoDevelop](http://www.monodevelop.com/)
		- [SharpDevelop](http://www.icsharpcode.net/OpenSource/SD/Default.aspx)
	- Platforms
		- [Windows Runtime (WinRT)](https://en.wikipedia.org/wiki/Windows_Runtime)
		- [Xamarin](http://xamarin.com/)
		- [Universal Apps](https://dev.windows.com/en-us/develop/build-apps-shared-code)
			- WinJS
		- [.NET Native](https://msdn.microsoft.com/en-us/vstudio/dotnetnative.aspx)
		- Windows Phone SDK
		- [Azure](https://azure.microsoft.com)
	- Productivity
		- [Team Foundation Server (TFS)](https://www.visualstudio.com/en-us/products/tfs-overview-vs.aspx)
			- Product Backlog Item
			- Task
		- [NuGet](https://www.nuget.org/)
		- [Chocolatey](https://chocolatey.org/)
		- [PowerShell](https://en.wikipedia.org/wiki/Windows_PowerShell)
	- Build
		- MSBuild
		- CodeDom
		- [Roslyn](https://github.com/dotnet/roslyn)
		- [CruiseControl.NET](http://cruisecontrol.net/)
		- csc/vbc/fsc
	- Testing
		- MSTest
			- TestClass
			- TestMethod
		- [NUnit](http://www.nunit.org/)
			- TestFixture
			- Test
		- Mock
			- [Moq](https://github.com/Moq/)
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
		- [FxCop](https://en.wikipedia.org/wiki/FxCop)
	- [Data](https://github.com/unruledboy/DatabaseStack)
		- ADO.NET
		- Object/Relationship Mapping (O/RM)
			- [Entity Framework (EF)](https://github.com/aspnet/EntityFramework)
			- [NHinbernate](http://nhibernate.info/)
			- [AutoMapper](http://automapper.org/)
		- NoSQL
			- [RavenDB](http://ravendb.net/)
			- [Azure Document DB](http://azure.microsoft.com/en-us/services/documentdb/)
		- Cache
			- [NCache](http://www.alachisoft.com/ncache/)
	- Components
		- IoC
			- [Autofac](http://autofac.org/)
			- [Unity](https://github.com/unitycontainer/unity)
			- [NInject](http://www.ninject.org/)
			- [Windsor](https://github.com/castleproject/Windsor/blob/master/docs/README.md)
		- Messaging/Queue
			- [NServieBus](http://particular.net/nservicebus)
			- [RabbitMQ](https://www.rabbitmq.com/)
			- [MassTransit](http://masstransit-project.com/)
			- [NetMQ](https://github.com/zeromq/netmq)
		- Schedule
			- [Quartz.NET](http://www.quartz-scheduler.net/)

<!--BUILD_END-->