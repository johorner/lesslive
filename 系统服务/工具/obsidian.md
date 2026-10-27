---
description: 仓库的基本操作工具
created: 2026-10-06 星期二 15:17
modified: 2026-10-25 星期日 19:19
published: false
tags: []
---

仓库操作的基本[[工具]]
## 基本操作
- 阅读[[文件夹笔记]] `点击右边的小箭头`，了解 LessLive 特有的内容管理方式。
- 阅读[[日志操作]]，作为每天开始与结束的仪式感。
- 阅读[[文件管理]]，了解内容创建，以及后续流转和使用规则。
- 在任何文档的 tags 属性里添加 `#todo` 标签，让 checklist 跟踪该文档里的 `-[ ]` 任务
## Callout CSS
**隐藏标题列写法**：`> [!blank-container]`

> [!multi-column]
>
>> [!tip] 这是第一个分栏
>> **嵌入一个无序列表**
>>>[!tip] 嵌套一个无序列表
>>> 	- 这是二级无序列表
>>> 		- 这是三级无序列表
>> 
>> **复选框语法**
>>>[!tip]  这里用的嵌套 callout
>>> - [ ] 新建任务 
>>>  - [/] 正在进行
>>>  - [x] 任务完成
>>>  - [-] 任务取消 
>> 
>>   **靠右签名**
>>>[!note|cite] 签名靠右
>>>  任意 callout 语法加 `|cite`，内容与作者之间加一个空行
>>>  
>>>  这里是签名
>>
> 
>> [!tip] 这是第二个分栏
>>**嵌入一篇笔记**
>>  ![[线下活动经验集]]
> 
>> [!tip] 这的第三个分栏
>> **仓库 Git 初始化**
>>> [!code] 内嵌代码快
>>>
>>> ```md
>>> # 1. 进入项目文件夹
>>> cd 到你的LessLive文件夹目录
>>> # 2. 【如果还没全局配置身份，执行一次，以后就不用了】
>>> git config --global user.name "nian"
>>> git config --global user.email "你的邮箱@xxx.com"
>>> # 3. 初始化仓库
>>> git init
>>> # 4. 创建 .gitignore
>>> touch .gitignore
>>> # 5. 添加文件、提交
>>> git add .
>>> git commit -m "初始化仓库"
>>> # 6.（可选）关联远程仓库
>>> git remote add origin git@github.com:xxx/xxx.git
>>> git push -u origin main
>>>  ```

---