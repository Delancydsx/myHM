//打开VS选择“克隆存储库”
//“存储库位置”为该页面的位置
//“路径”为本地任意空文件夹
//点击“克隆”
//参考网站：https://blog.csdn.net/qingttqing/article/details/135347595
//在该文件夹下新建文件夹“build”
//进入“build”用命令行输入指令
cmake .. -DCMAKE_BUILD_TYPE=Debug
//camke完成之后生成.sln文件
//参考网站：https://zhuanlan.zhihu.com/p/580945545
//把TAppEncoder设为启动项并生成
//生成结果可能会报错“使用简体中文 gb2312 编码加载文件”
//此时需要在“高级保存选项”中进行设置
//参考网站：https://blog.csdn.net/sjskbxiqznkqk/article/details/135564227
//设置好后重新生成 发现成功
//对TAppEncoder的属性配置后即可正常编码
//切换分支change即可看到改写后的代码
