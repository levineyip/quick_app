用于浏览新闻的快应用
====


一、快应用功能
-------
1.频道列表展示  
2.频道列表编辑  
3.新闻列表展示  
4.新闻详情展示  


二、快应用调试
-------
1.hap-toolkit工具  
  hap-toolkit是快应用的开发者工具，帮助开发者通过命令行工具辅助开发工作的完成，主要包括创建模板工程，升级工程，编译，调试等功能。可以通过 npm install -g hap-toolkit 安装hap-toolkit。  
2.快应用调试器(下载地址：https://statres.quickapp.cn/quickapp/quickapp/201806/file/quickapp_debugger.apk)  
    为了方便调试程序，您可以使用快应用调试器，这是一个Android应用程序，主要包含以下功能：  
      a.扫码安装：配置HTTP服务器地址，下载rpk包，并唤起平台运行rpk包  
      b.本地安装：选择手机文件系统中的rpk包，并唤起平台运行rpk包  
      c.在线更新：重新发送HTTP请求，更新rpk包，并唤起平台运行rpk包  
      d.开始调试：唤起平台运行rpk包，并启动远程调试工具  
    快应用调试器可以连接到手机系统内的快应用执行环境（需要将系统升级到最新的正式版本），或者您可以单独下载安装快应用平台预览版来提供执行环境。  
3.快应用预览版(最新版本下载地址:https://statres.quickapp.cn/quickapp/quickapp/201806/file/quickapp_platform_preview_release_v1060.apk)  
    当您的手机系统尚未内置快应用运行平台，或您想在开发过程中体验快应用尚未正式发布的新功能、新特性，您可以安装 快应用预览版。  
    这是一个包含了快应用基础功能的 Android 应用程序。下载安装成功后，通过快应用调试器可以选择在快应用预览版运行 rpk 包，开发测试对应平台的 api 和功能。  
    注意：如果您之前已经安装过较高版本的快应用预览版，则安装低版本时，需要先卸载之前的预览版。  
	
	
三、快应用rpk试用
-------
地址：https://github.com/levineyip/quick_app/blob/master/com.levine.quick.demo.release.rpk
