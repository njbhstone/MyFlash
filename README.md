### 一、简介
MyFlash是由美团点评公司技术工程部开发维护的一个回滚DML操作的工具。该工具通过解析v4版本的binlog，完成回滚操作。相对已有的回滚工具，其增加了更多的过滤选项，让回滚更加容易。
**该工具已经在美团点评内部使用**
### 二、详细说明
1. [安装](./doc/INSTALL.md)
2. [功能说明](./doc/Function.md)
2. [使用](./doc/how_to_use.md)
3. [测试用例](./doc/TestCase.md)
### 三、限制
1. binlog格式必须为row,且binlog_row_image=full
2. 仅支持5.6与5.7
### 四、联系方式
QQ群:645702809
