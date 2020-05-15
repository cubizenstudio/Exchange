# Exchange
一个用于软件版本更新的仓库

## 用法/Usage
* 1.fork本仓库，运行`Exchanger.Scanner.exe`，根据提示输入要发布的软件的release目录。
同时还需要提供该软件的名字，版本。
`Exchanger.Scanner.exe`会复制所有文件到该仓库，并为其建立文件索引。

**最终成品索引文件**：
```
{
  "Version": "1.0",
  "Files": [
    {
      "FileName": "Drops.exe",
      "Hash": "d379f2386f48cc3824b395691ccd41b6",
      "Url": "vers/1.0/Drops.exe"
    },
    {
      "FileName": "Drops.Plugins.dll",
      "Hash": "cefe9e96699eac1f40ab867fc9d43a3",
      "Url": "vers/1.0/Drops.Plugins.dll"
    },
    {
      "FileName": "GalaSoft.MvvmLight.dll",
      "Hash": "a4297a9b2d89c4c4dc3975dc17ccd2",
      "Url": "vers/1.0/GalaSoft.MvvmLight.dll"
    },
    {
      "FileName": "GalaSoft.MvvmLight.Extras.dll",
      "Hash": "99f85ec0e471bb3d3639dc5056eff4",
      "Url": "vers/1.0/GalaSoft.MvvmLight.Extras.dll"
    },
    {
      "FileName": "GalaSoft.MvvmLight.Platform.dll",
      "Hash": "e74e1e65c32dafe45cdada1f5defc67",
      "Url": "vers/1.0/GalaSoft.MvvmLight.Platform.dll"
    },
    {
      "FileName": "Microsoft.Practices.ServiceLocation.dll",
      "Hash": "92a533be83b7fa43a1b18f09a7d45b",
      "Url": "vers/1.0/Microsoft.Practices.ServiceLocation.dll"
    },
    {
      "FileName": "Newtonsoft.Json.dll",
      "Hash": "c53737821b861d454d524834c3c97c",
      "Url": "vers/1.0/Newtonsoft.Json.dll"
    }
  ]
}
```

* 2.在软件本地使用`Exchanger.Updater.exe`或其他具有UI的，同类程序更新版本。
