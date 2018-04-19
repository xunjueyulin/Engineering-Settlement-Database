# Engineering-Settlement-Database
A database of engineering settlement data for GDCATV, use Python & SQLite.With this database， we can manage the imformation of the engineering settlement imformation from Web or .xls files .The other functions i have no plan now 
## Framework assumption 框架设想
1. 模具
-数据库模型
-数据写入模型
-数据查询模型
-页面生成模型
-服务器脚本
2. 视图
-页面布局
3. 连接器
-页面生成访问数据库语句模块
## Functional implementation 功能实现
1. 实现工程结算信息的数据库化
2. 可以通过页面与数据库互相访问，实现增删查改和报表导出
3. 对数据填入进行逻辑约束，减少不合理数据的存在
