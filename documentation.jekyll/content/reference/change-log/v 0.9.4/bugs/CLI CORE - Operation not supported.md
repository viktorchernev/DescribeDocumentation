---
layout: page
title: CLI CORE - Operation not supported
permalink: /language/reference/versioning/v094/bugs/bug-2/
exclude: true
---
<br>_BUG: CLI CORE - Operation not supported_

<span style="color:red">Presetting console buffer height is not supported in OS other then Windows, so we need to check if we are under windows.</span>

```
You may only use the Microsoft .NET Core Debugger (vsdbg) with
Visual Studio Code, Visual Studio or Visual Studio for Mac software
to help you develop and test your applications.
```

```
Loaded '/usr/share/dotnet/shared/Microsoft.NETCore.App/6.0.25/System.Private.CoreLib.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
Loaded '/app/bin/Debug/net6.0/DescribeCompiler.CLI.Core.dll'. Symbols loaded.
Loaded '/usr/share/dotnet/shared/Microsoft.NETCore.App/6.0.25/System.Runtime.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
Loaded '/usr/share/dotnet/shared/Microsoft.NETCore.App/6.0.25/System.Console.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
Loaded '/app/bin/Debug/net6.0/DescribeCompiler.API.Standard.dll'. Symbols loaded.
Loaded '/usr/share/dotnet/shared/Microsoft.NETCore.App/6.0.25/netstandard.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
Exception thrown: 'System.PlatformNotSupportedException' in System.Console.dll
Loaded '/usr/share/dotnet/shared/Microsoft.NETCore.App/6.0.25/System.Diagnostics.StackTrace.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
Loaded '/usr/share/dotnet/shared/Microsoft.NETCore.App/6.0.25/System.Reflection.Metadata.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
Loaded '/usr/share/dotnet/shared/Microsoft.NETCore.App/6.0.25/System.Collections.Immutable.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
Loaded '/usr/share/dotnet/shared/Microsoft.NETCore.App/6.0.25/System.Threading.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
Loaded '/usr/share/dotnet/shared/Microsoft.NETCore.App/6.0.25/System.Runtime.InteropServices.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
Loaded '/usr/share/dotnet/shared/Microsoft.NETCore.App/6.0.25/System.IO.MemoryMappedFiles.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
Loaded '/usr/share/dotnet/shared/Microsoft.NETCore.App/6.0.25/System.Text.Encoding.Extensions.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
Loaded '/usr/share/dotnet/shared/Microsoft.NETCore.App/6.0.25/Microsoft.Win32.Primitives.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
Fatal error: Operation is not supported on this platform. -    at System.ConsolePal.set_BufferHeight(Int32 value)
   at System.Console.set_BufferHeight(Int32 value)
   at DescribeCompilerCLI.Messages.presetConsole() in C:\Users\Viktor Chernev\Desktop\World-Describe\Language\DescribeLanguage\DescribeCompilerCLI.Core\FunctionsMessages.cs:line 79
   at DescribeCompilerCLI.Program.Main(String[] args) in C:\Users\Viktor Chernev\Desktop\World-Describe\Language\DescribeLanguage\DescribeCompilerCLI.Core\Program.cs:line 15
Press any key to exit.
```

<span style="color:green">Code has been added to fix the issue.</span>


<br>
### Links
[Back](/language/reference/versioning/v094/compiler094/)