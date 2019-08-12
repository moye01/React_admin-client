## 开发环境与生产环境
    1.开发环境运行
     命令： npm start
     做了什么：
        1.在内存中打包，生成内存中的打包文件（html/js/css/img）
        2.启动服务器，运行内存中的打包文件 ===> 在浏览器中通过虚拟地址来访问得到相应的资源
    2.生产环境打包并运行
        命令:
            npm run build
            serve build
        做了什么：
        1.在内存中打包，生成内存中的打包文件（html/js/css/img）
        2.将内存中的打包文件保存到本地
        3.加载打包文件到内存
        4.启动服务器运行 ===> 在浏览器中通过虚拟地址来访问得到相应的资源.