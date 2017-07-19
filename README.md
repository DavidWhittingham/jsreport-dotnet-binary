# jsreport-dotnet-binary
[![Build status](https://ci.appveyor.com/api/projects/status/o2xkoca4gtloxayx?svg=true)](https://ci.appveyor.com/project/pofider/jsreport-dotnet-binary)

This package includes the raw [jsreport.exe binary](https://jsreport.net/learn/single-file-executable) embedded in the manifest stream. This allows very easy attaching of jsreport into .net projects. The binary can be used directly but it is recommended to use another package [jsreport-local](https://github.com/jsreport/jsreport-dotnet-local) which adds simple to use wrapper around.

The releases of this package should match the release number of jsreport itself and always include the particular binary. This means you can choose which version of jsreport you want to use, because the sdk it self is agnostic to it.

You can find link to docs and further navigation across the .net repositories here
https://github.com/jsreport/jsreport-dotnet
