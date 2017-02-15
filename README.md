# Resume
Daniel OLIVIER
Senior C++ Software Developer

Contact : 
dan_olivier@hotmail.com
+1-514-415-8595

# Primary activities
- Analysis, design and development (C++)
- System architecture, developer support and technical advisory roles

# Technical skills
- Langages:	C/C++, C#.NET, SQL, Bash, Python, Perl, Delphi, Lua, Power Shell
- C++ libraries:	STL, Boost (Serialization, ASIO), template, Win32, pthreads, OpenAL (audio) IHM (MFC, WxWidgets, Qt), Protobuf, Ace/Tao/Corba, OSG, VegaPrime
- Systems:	Windows, Linux (CentOS, Ubuntu, Red Hat, Fedora, Solaris) 
- Databases:	Oracle (SQL Developer), Toad, Sybase, Rogue Wave
- Methods :	UML, Rational Rose, Design Patterns
- Tools :	windbg, Multigen/Presagis Creator
- Configuration management:	git, CVS, SVN, make (gmake, cmake, nmake, vcbuild), Clearcase, Clearquest

- Primary technical aptitudes:	Grid computing, interoperability, optimisation, build systems/continuous integration

# Education
1989 - 1993 : Computer Engineering, École Polytechnique de Montréal (majored in software systems)

Availability: two weeks


# Work History 

## Senior C++ software developer, Ericsson Montreal, Montreal, QC
March, 2014 - present

### Trace project: 

Trace integrates the chosen tracing software (3rd-party provider LTTNg) into the rest of the Ericsson architecture (or component offering), 
making it available to software developers working with the Ericsson software stack, and 
simplifying deployment and activation for developers, users and operators.
The resulting traces are extremely lightweight, and provide cluster-wide visibility of application events and operations in a production setting.

### LM (Licence Manager) project: 

LM ensures license control of Ericsson applications at customer sites, 
integrated with both in-house and third-party backends (i.e. Sentinel RMS, Cloud).

Duties:
-	development of new features, maintain existing,
-	ensuring stability of test jobs,
-	observing and maintaining performance, in particular under saturated or overloaded conditions (CPU, memory, network, IO).

Contributions:
-	refactoring build, packaging and deployment scripts
-	partitioning the software to isolate the new licensing back-end from the rest of the product.
-	develop and integrate a new back-end (Sentinel Cloud) into the licensing infrastructure

Technical environment:

-	Linux: LDE (Linux Distribution Extension), LOTC (Linux Open Telecom Cluster), SLES (SUSE Linux Enterprise Server), OpenSuse, DRBD
-	C++, Java, Linux tool suite (bash, gmake, cmake, autotools, python, perl, awk, sed, RPM, etc),
-	Build pipeline: Jenkins (continuous integration), Gerrit (code review), JIRA (issue and project tracking)
-	C++: OpenSAF (high-availability framework), LTTNg, Poco, MAF (Middleware-Agnostic Framework), gtest, gmock
-	licensing: Sentinel RMS, Sentinel Cloud
-	Overload testing: perf, sar, stress, Linux Performance Observability Tools, Trace Compass
-	Additional context: clustering, availability/resilience, distributed systems
-	hardware: GEP-3, GEP-5 (multi-core, Xeon-based, Generic Ericsson Processor blades), Xen virtualisation

## Since July 2011 (18 months)
SGCIB (Société Générale Corporate Investment Bank), Paris, France
« Ingénieur Études et développement », C++
Development, maintenance, optimization and support of the primary risk analysis application covering derivative financial products

Maintenance and development of the (Gigaspace) cache support system (market data + static data) :
- Incorporation of new fields and structures into cache schema, and supporting changes in the code (C++, Java, C#), ensuring backwards and forward compatibility
- Maintenance and evolution of the changes to configuration management. 
i.e. compile Gigaspace in debug mode, allowing for the deployment into the developer environment (and ensuring symmetry between developer, testing and production environments)
- Deployment of cache proxy onto testing and development compute grids
- Production debugging (remote desktop, remote debug, WMI, Powershell) + crash dump capture and analysis
- Study and use of surveillance applications, grid management, and distributed computation frameworks (internal and OTS)
- Assessment of feasibility of cache invalidation notifications (emanating from a DB service)
- Developer support

Development of a C++ LoadService (specialized DB front-end service) :
- Development of a generic “access module” (to hide the details of our use of Google protobuf packets and library)
- Census of all target database (common market and static data) entry points and conversion to new LoadService interface
- Connection management and optimization (socket lifecycle)
- Adaptation of LoadService to a second target DB, and extending the flexibility of the protocol and the supported types (i.e. input vectors)
- Migration of hardcoded SQL queries to stored procedures
- Massive legacy code refactoring. Suppression of 150 KLOC (over 1.5 MLOC initial)
- Support, diagnoses, bug management
- Validation of results (DB queries) through instrumentation of access functions (and use of Boost serialization to produce reports)
- Reconciliation of divergent reports
- Unit and performance tests
- Developer support
- Results : impact on database divided by 5

Technical environment : C++ (VS 2008, 2010), Boost, C++/CLI, Rogue Wave, Xerces XML, OCI (Oracle Call Interface) + OCCI, Google Protobuf, Log4Net, DOxygen, Git, Symphony, Gigaspace, C#.Net, Java


## February 2010 – March 2011 (1 year 1 month)
IFCS, Paris
Freelance C++ developer
- IFP project (Institut Français du Pétrole) : maintenance and development (internal structure and GUI) of a legacy lithographic modeling framework and application suite (sub-surface 3D cartography for petroleum and mining applications)
- inux (RH9, EL5), C++ (Eclipse + CDT), Ilog Views + internal libraries 
- Trophy project : development and optimization of a dental imagery visualization application
Visual C++, wxWidgets, VTK (graphics engine)

## September 2004 - August 2009 (5 years)
CM Labs, Montreal, QC
Senior Software Developer C++, build automation + release engineer
Context : Physics middleware (Vortex C++ SDK), robotics, simulation, serious games
The Vortex C++ SDK is a software library intended for mechanical simulation and is subdivided into the following categories or problems domains:
- physics: collision detection (volumes, contacts), dynamics (friction, constraints, control, motors), 
- graphics and visualization, animation, special effects,
- vehicles (wheeled, tracked), including the complete modeling of suspension, transmission, differentials, wheel traction, etc.
- articulated robots (undersea, de-mining), 
- particle systems, fluids, cables,
- simulated sensors (i.e. depth camera, sonar), ray-casting, graphical display
- 3rd party integration:
- Vortex for VegaPrime (Multigen/Presagis), LynxPrime integration module (vpVx, vpVxVehicle)
- OpenSceneGraph, OpenGL
- Virtools, etc.
- Support modules: i.e. persistence, data-flow programming, encryption/decryption of resources

Developed and maintained the Vortex library and supporting framework:
- entire development life-cycle : analysis, architecture, development, re-factoring, debugging, and support (internal or external/client)
- bug tracking and resolution, performance, 
- developed and enhanced SDK samples/tutorials (all categories), user documentation
- persistence + physics file format (using Boost)

Crane simulator prototypes (mobile, tower), software development, initial productization and support: 
- graphics (tuning, debugging, frame rate, shadows), 
- networking (DTK, Ace/TAO), GUI (wxWidgets, Qt), sound (OpenAL)
- physics parameterization and scripting (core), 
- head-tracker (Ascension), 
- devices and controls (National Instruments, NI-DAQmx C APIs), 
- scripting (Lua + tolua++),
- simulator configuration, scenario development, 
- integration issues
- build system/process, construction, scripts, installation/deployment,
- hardware inventory, assembly, machine installation/management,
- on-site field support

Maintain and extend the build system, which includes:
- configuration management, source control
- makefiles, scripting, native projects, build matrix, packaging, deployment
- multi-platform (Linux, Windows)
- QA, runtime issues, licensing (FlexLM), developer support (internal, external), deployment and installation
- testing and support of 3rd party integration modules
- planning and evolution

Special tasks:
- DRDC project (Gaming Tools and Serious Games survey)

## June 2003 - November 2003 (6 months)
TimeSpring Software, Montreal, QC (purchased by Double-Take in 2008)
(Storage management, backup, file-system drivers, continuous data protection)
Senior C++ Developer, build support
Development of an incremental and continuous backup application.
- Deployment maintenance (InstallShield, MSI) 
- Build script maintenance (make, bash, perl, VBScript, C#, NAnt)
- Reporting (C#, DotNet, XML, XSLT, HTML, CVS) 
- Incorporation of new tools to build process (ex. Purify, Quantify)
- Installation/deployment module (SCM, C++)
C++ (VC7), Boost, STL, ACE, cygwin (make, bash, sed, awk, cvs)
File-system drivers: DDK, SoftICE

## April 2002 - April 2003 (1 year)
VisualMED, Montreal, QC (Healthcare management software)
Development, developer support, configuration management
- Analysis and debugging, developer support (30+ developers), software build procedure (including deployment), integration and regression testing
Special projects: 
- Translation management infrastructure (studio and runtime)
- Citrix compatibility with fingerprint scanning peripheral device (virtual channel driver)
Delphi v6, COM+, Oracle, Toad, VC7, Wise, Express QuantumGrid

## August 2000 - July 2001
Rational Software (Rose Business Unit), Redmond, WA
(Visual software modeling and design tools)
- Build script and integration test maintenance
- Integration testing, oversight, reporting
- Version control, bug and feature management, distribution, user support
- Technical documentation (internal APIs)
- Performance analysis
Rose, UML, XDE, ClearCase, ClearQuest
MSDev 6, Visual Studio 7, VB, COM (MIDL), Perl (ActiveState), Websphere Studio, Visual J++, Jbuilder, JSDK, JIntegra, cygwin

## July 1999 - July 2000
Microsoft, Redmond, WA (Application Compatibility)
Software Design Engineer (SDE)
- Developer support (bug-tracking)
- Identify and correct applications with compatibility issues
- Analysis, diagnosis, triage and dispatch of compatibility bugs
- Performance analysis and documentation of API interception strategies in Win2K
- Exploratory testing of selected target applications
- Kernel/Base (Win32 API category) developer support
Debuggers: VC6, Windbg (cdb, ntsd, kd), Boundschecker, Bugtrapper, IDA (Interactive Disassembler), Detours, API hooking (IAT thunking)
Full range of Microsoft development tools: VC6, VC7, Win32, Platform SDK, RAID (bug management), SourceDepot (source code control), build process

## March 1997 - June 1999 (2 years 3 months)
SR Telecom, Ville St-Laurent, QC (Fixed-point telecommunications)
C++ Developer
Design and implementation of a network management system
- PC Workstation environment (Visual C++, Win32, MFC, STL, Corba, ACE,OOP, patterns)
- Design, development and unit testing of client (marshaling, distributed networking)
- Maintenance of communication server (bridge)
- Evaluation of development tools and operating environments 
- Research into ITU network management standards and distributed systems (TMN, CORBA, JIDM)
- Maintenance/development of the communication sub-system of the SR-500 system (custom embedded OS) : Borland C++ tools, Checkmate ICE, UART 
- Technical lead for control panel (Compact Central Station) : Microchip PIC processor supported by simple C++/MFC application

## July 1996 - February 1997 (8 months)
- anSer Technologies, Westmount, QC
Narrowband wireless local loop bypass network (POS transactions, automated meter reading, alarm systems, etc.)
Software maintenance and testing of network management protocol conversion application (proxy agent)
C/C++, QNX, Solaris, Sparcworks, SunNet Manager
November 1993 - July 1996 (2 years 8 months)
NBS Technologies, Mount-Royal, QC
Point of Sale (POS) Terminals
Embedded Systems Software Developer
Develop, support and maintain embedded software for POS Terminals 
- Port the proprietary OS and (client) applications from an 80x86 platform to a 68000 platform (C, 68K asm, MC68302, 80x86 asm, Microtec tools, XRAY debugger)
- Design and implementation of master-slave network (BASE-32 financial protocol)
- Design and implementation of a network management system (Windows NT, VC++ v2.0, MFC, IPX/SPX)
- Maintenance of a 1st generation management system 
- Evaluation of multi-platform GUI development tools (zApp, XVT, MFC, OWL, …)
- Design and implementation of a class library (OOP) for client/server communications

## Summer 1992
Hôpital Sainte Justine, Laboratoire d’Étude du Mouvement, Montreal, QC
Kinesiology, gait analysis, prosthetics
Programmer
Design, implementation and optimization of a program to visualize the 3-D rendering of the human spine in motion
C, Xlib, Sun workstations, XWindows


