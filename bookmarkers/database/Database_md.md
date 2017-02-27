## DataBase_BookMarks<br>
记录一些数据库相关的内容书签，涉及一些常见数据库的使用技巧、坑。<br>

### MySQL
  * MySql中查询树形节点所有子节点:<br>
    在Oracle 中我们知道有一个 Hierarchical Queries 通过CONNECT BY 我们可以方便的查了所有当前节点下的所有子节点。但很遗憾，在MySQL的目前版本中还没有对应的功能。该篇文章介绍了如何通过查询mysql数据表中具有树形层级结构表的所有子节点。[详情1](http://blog.csdn.net/ACMAIN_CHM/article/details/4142971) [详情2](http://www.jb51.net/article/87318.htm) <br>
    
---
### Oracle
  * Oracle中connect by prior递归树形查询：<br>
 Oracle中start with...connect by prior子句用法 connect by 是结构化查询中用到的,可以查询Oracle表中某个树形节点的所有子节点。具体用法，[参考](http://xxciof.blog.163.com/blog/static/7978132720095193113752/)。
