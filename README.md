# 爱普特csi例程库
# 概述
CSI例程库是爱普特AE团队基于平头哥的IDE软件CDK，针对爱普特不同系列芯片开发的。用户可以直接在该库上进行二次开发。其代码文件结构如下：

<code>
├─board                                       //board组件，集合了用户可能需要修改的代码
├─components                                    
│  ├─chip                                      //chip组件，驱动代码主体  
│  ├─components                                //demo组件，IP使用的示例代码，实际工程中可以删除  
│  ├─console                                  //console组件，用来打印调试信息（UART）  
│  ├─csi                                      //csi组件，声明了所有chip组件实现的csi接口函数  
│  ├─gui                                      //gui组件，用来进行图形化配置  
│  └─sdk_103x                                 //SDK是一个组件集合，包括chip组件，demo组件，console组件，csi组件和gui组件  
├─Demo                                        //cdk工程文件目录  
└─DOC                                         //文档目录，包含quickstart 和csi代码结构说明等文档，帮助用户快速上手  
</code>

# 说明
本仓库是爱普特芯片csi 例程的入口，所有的csi例程都可以在此找到。目前提供csi代码的芯片有APT32F110X , APT32F103X , APT32F171X , APT32F173X。更多芯片及其csi代码持续更新中，敬请期待~

# 内容
## csi 例程代码最新release版
该部分用于显示最新发布的csi demo程序包，便于用户下载使用。
|csi demo最新release版|说明|
|:----------|:-----------|
[APT32F110X_latest_release_version](https://github.com/APT-AEteam/APT32F110X/releases/latest) |APT32F110X芯片的csi demo最新发布版本程序包
[APT32F103X_latest_release_version](https://github.com/APT-AEteam/APT32F103X/releases/latest) |APT32F103X芯片的csi demo最新发布版本程序包
[APT32F171X_latest_release_version](https://github.com/APT-AEteam/APT32F171X/releases/latest) |APT32F171X芯片的csi demo最新发布版本程序包
[APT32F173X_latest_release_version](https://github.com/APT-AEteam/APT32F173X/releases/latest) |APT32F173X芯片的csi demo最新发布版本程序包

## csi例程代码库
该部分用于显示各芯片csi demo代码仓库。由于该库持续更新中，建议用户下载使用最新release版本。
|csi demo|说明|
|:----------|:-----------|
[APT32F110X](https://github.com/APT-AEteam/APT32F110X.git) |APT32F110X芯片的csi demo程序包
[APT32F103X](https://github.com/APT-AEteam/APT32F103X.git) |APT32F103X芯片的csi demo程序包
[APT32F171X](https://github.com/APT-AEteam/APT32F171X.git) |APT32F171X芯片的csi demo程序包
[APT32F173X](https://github.com/APT-AEteam/APT32F173X.git) |APT32F173X芯片的csi demo程序包
