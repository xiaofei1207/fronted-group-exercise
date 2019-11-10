# 1.什么是DevOps ？
	1.一组过程方法与系统的统称，用于促进开发、运维和质量保障部门之间的沟通、协作与整合
	2.一种文化转变，或者说是一个鼓励很好的交流和协作，以便于更好的构建可靠性更高、质量
	更好的软件的运动
	3.一种能力，具备此能力的团队可以高质量，快速的交付软件产品 或服务
	解决的主要问题：按时、快速、高质量的交付软件产品和服务
				   通过流程的自动化，节约成本

*答案请使用斜体*

# 2.用原生JS实现传入CSS代码改变样式。

*答案请使用斜体*

**题目来源是前端面试题，不强制写答案，大家自己对自己负责，希望大家去了解。请求合并信息写明姓名。**

```javascript
//此处编写js代码
var div = document.getElmentById('div');
div.style.cssText="display:block;color:blue;background-color:#ccc";

//CSS传值样例
var style = {
	（多级）选择器:{
		display:block;
		color:blue;
		background-color:#ccc;
	}
}
```