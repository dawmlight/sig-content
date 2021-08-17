# 	Content

简体中文|[English](./README.en.md)

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

- [@minglonghuang ](https://gitee.com/minglonghuang)

### Committers列表

- [@kevenNO1](https://gitee.com/kevenNO1)
- [@jony_code](https://gitee.com/jony_code)
- [@zhao_xiuxiu](https://gitee.com/zhao_xiuxiu)
- [@yu_jia_geng](https://gitee.com/yu_jia_geng)
- [@nicolaswang](https://gitee.com/nicolaswang)
- [@duzc2](https://gitee.com/duzc2)

###  各SIG组列表

1. [sig-devboard](https://gitee.com/openharmony/community/blob/master/sig/sig-devboard/sig_devboard.md)
2. [sig-dllite-micro](https://gitee.com/openharmony/community/blob/master/sig/sig-dllite-micro/sig_dllite_micro.md)
3. [sig-openblock](https://gitee.com/openharmony/community/blob/master/sig/sig-openblock/sig_openblock.md)
4. [sig-riscv](https://gitee.com/openharmony/community/blob/master/sig/sig-riscv/sig-riscv.md)
5. [sig-python](https://gitee.com/openharmony/community/blob/master/sig/sig-python/sig-python_cn.md)
6. [sig-linkboy](https://gitee.com/openharmony/community/blob/master/sig/sig-linkboy/sig_linkboy_cn.md)
7. [sig-systemapplication]( https://gitee.com/openharmony/community/blob/master/sig/sig-systemapplications/sig_systemapplications_cn.md)

### SIG数据存放和管理方式
* 代码的管理
  1. 代码在[sig-manifest仓](https://gitee.com/openharmony-sig/manifest)下统一管理。
  
* 各SIG组代码上仓流程

  在SIG组下新建仓库的过程，简单描述就是向 [openharmony 组织](https://gitee.com/openharmony)下的community仓提建仓的PR(pull request)，然后向[openharmony-sig组织](https://gitee.com/openharmony-sig)下新建的仓提交代码，相关的gitee操作请参考此[链接](https://gitee.com/help/articles/4128#article-header0)。

  1. 首先需要保证提PR的gitee账号已经在[链接](https://dco.openharmony.io/sign/Z2l0ZWUlMkZvcGVuX2hhcm1vbnk=)中签署DCO
  2. fork [openharmony 组织](https://gitee.com/openharmony)下的community仓

    * 在sig/sig-xxxx文件夹下的sig_xxxx.md和sig_xxxx_cn.md中添加将要新建的仓库地址
    * 在sig/sigs.json文件中找到对应的sig组名称，将需要新建的仓库地址添加到对应的sig组下
  3. 在fork过来的仓下向community仓提PR
    * 注意： git commit的时候要加-s参数，添加signed-off 信息，例：git commit - s  -m " xxxxxx"
  4. 等待后台审核

    * 通过则会在[openharmony-sig](https://gitee.com/openharmony-sig)组织下新增要建的仓库

    * 未通过则需要检查提交PR的gitee账号是否签署DCO,git commit  的时候是否添加signed-off信息，或者提交的PR是否存在冲突。

  5. 向[openharmony-sig](https://gitee.com/openharmony-sig)组织下新增的指定代码仓以提PR的形式提交代码

    * 提交以后，后台会进行自动化的法务合规、cicd的扫描，扫描结果会在提交的PR下以评论的形式展现出来
    * 如果扫描有问题，需要根据反馈进行整改，然后再重新提交，直到审核通过
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
  1. 作为跟踪进度的issue需要打上特定的标签，标签暂定为 **milestone**。

* 开源协议的选择
  1. 建议开发者使用Apache 2.0 开源协议。

### 联系方式(可选)

- 欢迎[订阅](https://lists.openatom.io/postorius/lists/dev.openharmony.io/)邮件列表：dev@openharmony.io
- Slack群组：NONE
- 微信群：NONE
