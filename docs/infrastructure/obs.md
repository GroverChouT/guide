# openSUSE 编译服务

> **注意**：这里所说的是 [openSUSE Build Service](https://build.opensuse.org/)，不是广义上的 [Open Build Service](http://openbuildservice.org/)。

### 什么是编译服务

openSUSE 编译服务是一个自动构建软件包的平台，openSUSE 即就构建在 [openSUSE:Factory](https://build.opensuse.org/project/show/openSUSE:Factory) 项目中。构建完成的包会自动发布到 [software.opensuse.org](https://software.opensuse.org/)。

### 对于普通用户

不是你需要的所有软件包都包含在 openSUSE 官方软件源中，你可以在 software.opensuse.org 搜索到不包含在官方软件源中的包。这些包可能来自于编译服务中其他的项目或是业余打包者。

### 对于开发者

它可以自动解决与其他软件包的依赖关系。如一个软件包依赖另一个软件包，当它所依赖的软件包变更时，这个软件包也将被自动重新编译。

