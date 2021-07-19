# 	Docs

说明：本SIG的内容遵循OpenHarmony的PMC管理章程 [README](/zh/pmc.md)中描述的约定

## SIG组工作目标和范围

### 工作目标

为SIG仓提供文档、会议纪要及其他文档提供仓库，同时作为各SIG组的索引页

### 工作范围

* 存放各SIG组每次例会后产生的会议纪要、会议材料，其中会议纪要模板请参考[链接](https://gitee.com/openharmony/community/tree/master/sig/sig-template/meetings)
* 提供各SIG组链接索引
* 为社区宣传提供可用的素材

## 本SIG组成员

### Leader

- [minglonghuang ](https://gitee.com/minglonghuang)

### Committers列表

- [kevenNO1](https://gitee.com/kevenNO1)

- [jony_code](https://gitee.com/jony_code)

- [zhao_xiuxiu](https://gitee.com/zhao_xiuxiu)

- [yu_jia_geng](https://gitee.com/yu_jia_geng)

- [nicolaswang](https://gitee.com/nicolaswang)

- [duzc2](https://gitee.com/duzc2)

###  各SIG组列表

|No|SIG name|Responsibilities|SIG Leader|
| :----- | :----- | :----- |:----|
|1|[sig-devboard](https://gitee.com/openharmony/community/blob/master/sig/sig-devboard/sig_devboard.md)|To increase the number of third-party boards of the OpenHarmony OS, the device SIG provides easy porting guide that board manufacturers could follow to contribute their codes to the community easily. The more important thing is actively cooperating with board manufacturers to enhance the OpenHarmony ecosystem|[@likailong](https://gitee.com/kkup180)|
|2|[sig-dllite-micro](https://gitee.com/openharmony/community/blob/master/sig/sig-dllite-micro/sig_dllite_micro.md)|To enable AI models to implement inference on IoT devices, IoT devices have AI capabilities.|[@chenxiaoliang](https://gitee.com/SilenChen)|
|3|[sig-openblock](https://gitee.com/openharmony/community/blob/master/sig/sig-openblock/sig_openblock.md)|In order to extend OpenHarmony OS's use in youth programming and STEM education, OpenBlock SIG will port the runtime of the Blockly based graphical programming language to OpenHarmony OS. And support soft bus, distributed and other OpenHarmony OS capabilities.|[@dutianwei](https://gitee.com/duzc2)|
|4|[sig-riscv](https://gitee.com/openharmony/community/blob/master/sig/sig-riscv/sig-riscv.md)|RISC-V SIG aims to build a RISC-V ecosystem for OpenHarmony, provide instructions to build software, maintain supports for RISC-V devices, and enable security capabilities like TEE on RISC-V. RISC-V SIG will promote more developers to involve in developing OpenHarmony on RISC-V.|[@yujiageng](https://gitee.com/yu_jia_geng)|

### SIG数据存放和管理方式
* 代码的管理
  1. 代码在[sig-manifest仓](https://gitee.com/openharmony-sig/manifest)下统一管理。
  2. 需要各leader维护本组内对应仓的 .xml 文件。
  3. 多个单位参与，可向leader提出建仓需求，由leader向社区提建仓pr。
* sig 独立目录下各文件夹的使用

  【docs文件夹】

  1. 用来存放sig组日常产生的公共文件，例如开发板资料、芯片手册等，leader 可根据情况增加文件夹对文件进行分类管理。

  【docs/task文件夹】

  1. 存放本sig组的任务分解明细。

  【docs/meetings文件夹】
  
  1. 存放本sig组的会议纪要文件

  【其他文件夹】

  1. leader可根据需要添加新的文件夹对其他文件进行分类管理。

* 任务进度

  1. 任务进度以在对应任务仓下提issue形式更新。
  1. 作为跟踪进度的issue需要打上特定的标签，标签暂定为 **sig_taskprogress**。

* 开源协议的选择
  1. 建议开发者使用Apache 2.0 开源协议。

### 联系方式(可选)

- 欢迎[订阅](https://lists.openatom.io/postorius/lists/dev.openharmony.io/)邮件列表：dev@openharmony.io
- Slack群组：NONE
- 微信群：NONE
