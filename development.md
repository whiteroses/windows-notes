# Windows development

## To-do

* [Windows desktop applications > Get started](https://developer.microsoft.com/en-us/windows/desktop/getstarted)
* [Windows dev center - desktop](https://msdn.microsoft.com/en-us/library/windows/desktop/aa906039.aspx)
* [Windows API](https://msdn.microsoft.com/en-us/library/windows/desktop/ff818516(v=vs.85).aspx)
* [Parameter passing convention](https://msdn.microsoft.com/en-us/library/zthk2dkh.aspx)
* [Developer Command Prompt for Visual Studio](https://msdn.microsoft.com/en-us/library/f35ctcxw.aspx)
* [C/C++ Building Reference](https://msdn.microsoft.com/en-us/library/91621w01.aspx)


## Developer Command Prompt for Visual Studio
`"c:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\vcvarsall.bat" x64`
to have environment variables in place for building?


## WinDbg

`?` in "Command" window for help; debugger.chm for more.

`bp $exentry` to get near start of executable,
or `bp {name of entry function, e.g. that specified with /entry to ml64}`


## Binary editor

There is a binary editor in Visual Studio. Find it with Open > File... > , then
the down arrow on the Open button.
