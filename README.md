# README

迭代记录Flink, OpenCL, DPDK技术学习报告。

## Commit Message格式

(type) : (subject)

### type

-------

用于说明commit的类别，使用下面**7**个标识。

|   type   | 含义                                          |
| :------: | :-------------------------------------------- |
|   feat   | 新功能(feature)                               |
|   fix    | 修补bug                                       |
|   docs   | 文档(documentation)                           |
|  style   | 格式(不影响代码运行的变动)                    |
| refactor | 重构(即不是新增功能，也不是修改bug的代码变动) |
|   test   | 增加测试                                      |
|  chore   | 构建过程或辅助工具的变动                      |

### subject

---------

subject是commit目标的简短描述，不超过50个字符，结尾不加句号(.)

> 例如：
>
> feat(单元测试) ： 完成环境搭建。
>
> fix(代码混淆) ： 修复混淆失败bug。
>
> ci(自动化) ： 自动触发测试脚本。