# Microsoft.Workflow.Comiler.exe
Microsoft.Workflow.Comiler.exe执行未签名代码

## 修改：
1. test.txt中blah.foo的文件路径最好写成绝对路径
2. blah.foo中的shellcode可以直接在cobalt-strike中自己生成，别人的也用不了。

### 参考
[原理及POC](https://www.anquanke.com/post/id/157299)
[代码参考](https://www.fortynorthsecurity.com/microsoft-workflow-compiler-exe-veil-and-cobalt-strike/)
