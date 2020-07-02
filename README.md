# Padavan-build说明
1. fork本仓库
2. 修改.github/workflows/build-padavan.yml文件内容
- 修改编译的型号，修改TNAME对应的值    
```YAML
    - name: Build Firmware
      env:
        TNAME: RM2100
```
- 修改需要的插件，请按需修改需要集成哪些插件，文件中都有注释，定义你需要的功能（y=集成,n=忽略）
3. 创建Release（可选）
4. 点击右上角的 Star 星星按钮即可开始自动编译（自己点击才会编译）

# [固件说明](https://github.com/chongshengB/rt-n56u)
- 默认登陆IP:192.168.2.1
- 默认用户名/密码:admin/admin
- 默认wifi密码:1234567890
- 集成/取消新增插件请修改此文件: trunk/build_firmware_modify

## 已适配除官方适配外的以下机型
- MI-R3P(感谢群里emmmm适配,可能led控制有点问题,其它功能正常)
- 京东云路由(文件来自Lintel) 编译代码: JDC-1
- 歌华链(感谢群里Heaven适配与测试）编译代码: GHL
- NEWIFI-D1
- B70(感谢Untitled提供荒野无灯的适配文件)
- JCG-AC856M(感谢群里的旅途中的我适配和测试,gpio值还未完全适配，但不影响使用)
- JCG-AC836M(感谢群里的碧霄客修改和测试)
- YK-L1(L1、L1C、L1W通刷)
- PSG712
- PSG1208
- PSG1218
- 5K-W20 (USB)
- OYE-001 (USB)
- NEWIFI-MINI (USB)
- MI-MINI (USB)
- MI-3 (USB)
- MI-R3G (USB)
- HC5661A
- HC5761A (USB)
- HC5861B
- 360P2 (USB)
- MI-NANO
- MZ-R13
- MZ-R13P
- RT-AC1200GU (USB)
- XY-C1 (USB)
- WR1200JS (USB)
- NEWIFI3 (USB)
- B70 (USB)
- A3004NS (USB)
- K2P
- K2P-USB (USB)
- JCG-836PRO (USB)
- JCG-AC860M (USB)
- DIR-882 (USB)
- DIR-878
- MR2600 (USB)
- WDR7300
- RM2100
- R2100


