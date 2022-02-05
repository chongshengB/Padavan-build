# Padavan-build说明

步骤

0.点击右上角的Fork按钮，进入自己fork后的仓库。

1.修改/workflows/build-padavan.yml里的插件与机型。修改TNAME: K2P 中的K2P为需要编译的型号，注意名称要与configs/templates/目录下的名字
相同。若需编译超频1000MHZ版，将第35行的https://github.com/MeIsReallyBa/padavan-4.4 替换为 https://github.com/padavanonly/padavan-4.4 。修改后commit changes保存。

2.点击页面上部的Actions按钮，点击I understand my workflows，go ahead and enable them绿色按钮启用action。

3.点击右上角的 Star 星星按钮即可开始自动编译（自己点击才会编译）。修改配置后若需再次编译，先点击Star取消Star后，再点击Star即可重新编译。

编译完成后在Actions页面底部下载固件。
