# Coding Specification

> 注意：项目提交前进行检查，不符合规范退回修改，直到规范为止



## 通用

1. 名称必须有意义（class，id，变量名，方法名，文件名）
2. 连字符统一标准（中划线/下划线/骆驼命名法）
3. 代码缩进
4. 去除不必要的注释
5. 善于使用视觉空行

## html

1. 相同类型的元素使用同一个类名来标注，并使用『类名+序号』的方式来单独区分
2. ul、ol的直接子级只能为li
3. p，h1-h6的直接子级为a、span

## css

1. 字符串使用单引号
2. 使用预编译语言引入第三方样式（改为less/scss后import）
3. mediaquery顺序：通用样式 > 大尺寸到小尺寸区间 > tablet > 特殊tablet > mobile > 特殊mobile
4. 尽量使用技巧布局，避免使用偏移或甚至手动计算
5. 尽量使用方法调用，不要手写前缀（不确定的自己查看文档）

## js

[查看详情](https://github.com/JoshuaYang/website-template/blob/master/.eslintrc)