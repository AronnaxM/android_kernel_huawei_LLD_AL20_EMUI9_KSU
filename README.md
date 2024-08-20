# android_kernel_huawei_LLD_EMUI9_KernelSU

荣耀9i（LLD-AL20和LLD-AL30）的emui9内核支持KernelSU

从zhz8951那里~~剽窃~~抄来的

Actions一遍跑过，实测KSU管理器1.0.1显示GKI模式生效，但是Wi-Fi模块出现故障，无法正常连接，具体表现为Wi-Fi密码输入正确但显示密码错误无法连接
已确定此问题由于机型不同导致，此内核在LLD-AL30上工作无误但LLD-AL20存在上述问题
