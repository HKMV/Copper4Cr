Copper for Chrome (Cu4Cr) CoAP 用户代理
====================================================

工具 [RFC7252](http://tools.ietf.org/html/rfc7252)

一种 Chrome app+extension 浏览物联网
-------------------------------------------------------

### 如何将铜源集成到 Chrome 中：

1. 克隆 [存储库](https://github.com/mkovatsc/Copper4Cr.git) (`git clone https://github.com/mkovatsc/Copper4Cr.git`)
2. 通过以下方式准备共享代码：
   * 将共享文件夹复制到应用程序的根目录或扩展程序的根目录中
   * 运行 `install.bat` (Windows) 或 `install.sh` (Linux) 以将共享文件夹链接到两个文件夹中
3. 在 Chrome 中安装应用程序和扩展程序：
   1. 启动 Chrome 并转到 [chrome://extensions/](chrome://extensions/)
   2. 确保选中右上角的开发人员模式复选框
   3. 单击“加载已解压的扩展程序...”并找到应用程序(app)文件夹
   4. 点击“加载已解压的扩展程序...”并找到扩展(extension)文件夹
4. 在文件 `extension/endpoint/ClientPortChrome.js` 中设置 "Copper (Cu4Cr) Application" 的 应用ID。您可以在"Copper (Cu4Cr) Application"应用程序条目中读取 ID [chrome://extensions/](chrome://extensions/)
5. 使用地址栏旁边的 Cu 图标打开 CoAP 资源
