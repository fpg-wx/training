# Specification

> 注意：项目提交前进行检查，不符合规范退回修改，直到规范为止

## 通用

1. 拒绝dreamweaver
2. 拒绝bootstrap等css框架
3. 勤提交版本控制
4. 命名必须有意义（class，id，变量名，方法名，文件名） 
5. 去除不必要的注释，注释使用英文
6. 单词拼写必须正确有意义
7. 代码缩进
8. 善于使用视觉空行

## html

1. 命名规范：小写字母，名词形式，使用中划线分隔
2. 相同类型的元素使用同一个类名来标识，并使用『类名+序号』的方式来单独区分
3. 语义化
   1. 不要滥用div
   2. ul、ol的直接子级只能为li
   3. p，h1-h6的直接子级为a、span

## css

1. 字符串使用双引号
2. 使用预编译语言后缀引入第三方样式（改为less/scss后import）
3. mediaquery顺序：通用样式 &gt; 大尺寸到小尺寸区间 &gt; tablet &gt; 特殊tablet &gt; mobile &gt; 特殊mobile
4. 使用技巧布局，避免使用偏移或甚至手动计算
5. 不要手写前缀

## js

[风格指南](https://github.com/alivebao/clean-code-js/blob/master/README.md)

正式项目中将使用ESLint来规范代码，[查看具体规则](https://github.com/JoshuaYang/website-template/blob/master/.eslintrc)

## 动画

1. 优先使用css动画
2. 优先使用transform属性



