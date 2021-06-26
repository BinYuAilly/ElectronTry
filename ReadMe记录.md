## Electron

git clone https://github.com/electron/electron-quick-start



淘宝镜像：

 npm config set ELECTRON_MIRROR https://npm.taobao.org/mirrors/electron/



命令行开关：(可在浏览器打开 chrome://inspect --- Configure --->配置端口)

--inspect=[port]

例如：electron --inspect=5858 your/app



### app常用事件：

ready:当Electron完成初始化时被触发

window-all-closed:所有被关闭

before-quit:在应用程序开始关闭窗口之前触发

will-quit: 当所有窗口都已关闭并且应用程序将退出时触发

quit: 在应用程序退出时发出。



### webContents常用事件

did-finish-load：导航完成时触发，即选项卡的旋转器将停止旋转，并指派onload事件后。

dom-ready: 一个框架中的中文加载完成后触发该事件。