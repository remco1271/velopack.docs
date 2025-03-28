﻿<!--  
  <auto-generated>   
    The contents of this file were generated by a tool.  
    Changes to this file may be list if the file is regenerated  
  </auto-generated>   
-->

# Runtimes.DotnetInfo.GetLatestDotNetVersion Method

**Declaring Type:** [Runtimes.DotnetInfo](../index.md)  
**Namespace:** [Velopack.Windows](../../../index.md)  
**Assembly:** Velopack  
**Assembly Version:** 0.0.1053+0cec039

Get latest available version of dotnet. Channel can be 'LTS', 'current', or a two part version  (eg. '6.0') to get the latest minor release.

```csharp
[AsyncStateMachine(Velopack.Windows.Runtimes/DotnetInfo/<GetLatestDotNetVersion>d__28)]
public static Task<string> GetLatestDotNetVersion(Runtimes.DotnetRuntimeType runtimeType, string channel, IFileDownloader downloader = null);
```

## Parameters

`runtimeType`  [Runtimes.DotnetRuntimeType](../../DotnetRuntimeType/index.md)

`channel`  string

`downloader`  [IFileDownloader](../../../../Sources/IFileDownloader/index.md)

## Returns

Task\<string\>

___

*Documentation generated by [MdDocs](https://github.com/ap0llo/mddocs)*
