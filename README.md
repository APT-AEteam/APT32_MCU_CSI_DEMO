# 爱普特csi例程库
# 概述
CSI例程库是基于平头哥的IDE软件CDK开发的，用户可以直接在该库上进行二次开发。其代码文件结构如下：

<code>
├─board                                       //board组件，集合了用户可能需要修改的代码
├─components                                    
│  ├─chip                                      //chip组件，驱动代码主体  
│  ├─components                                //demo组件，IP使用的示例代码，实际工程中可以删除  
│  ├─console                                  //console组件，用来打印调试信息（UART）  
│  ├─csi                                      //csi组件，声明了所有chip组件实现的csi接口函数  
│  ├─gui                                      //gui组件，用来进行图形化配置  
│  └─sdk_103x                                 //SDK组件，是一个组件集合，包括chip组件，demo组件，console组件，csi组件和gui组件  
├─Demo                                        //cdk工程文件目录  
└─DOC                                         //文档目录，包含quickstart 和csi代码结构说明等文档，帮助用户快速上手  
</code>

# 说明
本仓库是爱普特芯片csi 例程的入口，涉及到的芯片目前有APT32F110X , APT32F103X , APT32F171X , APT32F173。芯片持续更新中，敬请期待~

# 内容
|csi demo|说明|
|:----------|:-----------|
[APT32F110X](https://github.com/APT-AEteam/APT32F110X.git) |APT32F110X芯片的csi demo程序包
[APT32F103X](https://github.com/APT-AEteam/APT32F103X.git) |APT32F103X芯片的csi demo程序包
[APT32F171X](https://github.com/APT-AEteam/APT32F171X.git) |APT32F171X芯片的csi demo程序包
[APT32F173X](https://github.com/APT-AEteam/APT32F173X.git) |APT32F173X芯片的csi demo程序包
