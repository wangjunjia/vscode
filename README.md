# vscode

记录 vscode 相关的工具和使用方式

相关分类文件夹名称修改为 **.vscode**， 放到 vscode 打开的根目录下  
相关分类文件夹名称修改为 **.vscode**， 放到 vscode 打开的根目录下  
相关分类文件夹名称修改为 **.vscode**， 放到 vscode 打开的根目录下  


### vscode 配置中预定义变量

如: /path/to/projectname/folder/file.txt 使用 vscode 打开 projectname 目录  

- ${workspaceFolder} - 当前工作目录(根目录) /path/to/projectname
- ${workspaceFolderBasename} - vscode 打开目录的根目录名称 projectname
- ${file} - 当前打开的文件名(完整路径) /path/to/projectname/folder/file.txt
- ${relativeFile} - 当前根目录到当前打开文件的相对路径(包括文件名) folder/file.txt
- ${relativeFileDirname} - 当前根目录到当前打开文件的相对路径(不包括文件名) folder
- ${fileBasename} - 当前打开的文件名(包括扩展名) file.txt
- ${fileBasenameNoExtension} - 当前打开的文件名(不包括扩展名) file
- ${fileDirname} - 当前打开文件的目录 /path/to/projectname/folder
- ${fileExtname} - 当前打开文件的扩展名 .txt
- ${cwd} - 启动时task工作的目录 
- ${lineNumber} - 当前激活文件所选行 光标所在行
- ${selectedText} - 当前激活文件中所选择的文本 编辑器中所选择的文本
- ${execPath} - vscode执行文件所在的目录 
- ${defaultBuildTask} - 默认编译任务(build task)的名字

[参考自：雾色](https://zhuanlan.zhihu.com/p/92175757)