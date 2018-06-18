# PDFViewer 

# 注意 : 
* 运行 PDFViewer 需要 自己搭建 运行环境
* PDFViewer 需要 http/https 开头的路径才能运行,也就是说需要运行在 服务器端,所以在使用方法中的 XAMMP 相当于服务器
* 项目成功运行后 可在地址栏中 viewer.html 后直接拼参数 PDFurl 就可以显示pdf文件了
* 例如: 服务器地址/web/viewer.html?file="你的pdf地址"

# 使用方法
* 1.下载 并 安装xmapp 启动Apache Web server
* 2.将 xmapp 目录中 htdos 目录下所有文件删除
* 3.将 PDFViewer 解压到 到 htdos 目录下
* 4.打开浏览器 输出 127.0.0.1 回车
* 5.择选PDFViewer/web/viewer.html

# 如何 替换 pdf 文件
* 1.在 viewer.js 文件中 搜索 DEFAULT_URL 
* 2.将 DEFAULT_URL 后面地址 URL 替换成自己的 

# 如何将 PDFViewer 融入到自己的项目中
* 1.可将 PDFViewer 解压后放到项目服务器根目录下(注意: 项目服务器的根目录) 
* 2.在项目中可以通过 <iframe src="服务器地址/web/index.html?file='你的PDF文件地址'"></ifrmae>

# 联系我
bianliuzhu@gmail.com

