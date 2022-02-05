# Padavan-build说明
步骤

1.修改/workflows/build-padavan.yml里的插件与机型。修改TNAME: K2P 中的K2P为需要编译的型号，注意名称要与configs/templates/目录下的名字
相同。修改后commit changes保存。

2.点击action，点击I understand my workflows，go ahead and enable them启用action

3.点击右上角的 Star 星星按钮即可开始自动编译（自己点击才会编译）。修改配置后若需再次编译，先点击star取消star后，再重新star即可再次重新编译。

编译完成后在action页面可下载固件。
