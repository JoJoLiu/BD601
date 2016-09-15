BD601 APP 开发文档
===
## 20160914
### 开发规定
- 采用驼峰命名法，即类似于MainActivity的方式来命名类名及方法名

### 开发准备
- 安装.ignore（配合git使用） codeglance（代码预览） markdown surport（md文件支持）这三款插件
- 记录开发中的各种问题




# **MARKDOWN** 语法说明

---

## 下面是**列表**的方法
> * 整理知识，学习笔记
> * 发布日记，杂文，所见所想
> * 撰写发布技术文稿（代码支持）
> * 撰写发布学术论文（LaTeX 公式支持）

## 图片*链接*的写法
![cmd-markdown-logo](https://www.zybuluo.com/static/img/logo.png)


## 待办事宜 [Todo 列表](https://www.zybuluo.com/mdeditor?url=https://www.zybuluo.com/static/editor/md-help.markdown#13-待办事宜-todo-列表)

- [ ] 支持以 'PDF' 格式导出文稿
- [ ] 改进 Cmd 渲染算法，使用局部渲染技术提高渲染效率
- [x] 新增 Todo 列表功能
- [x] 修复 LaTex 公式渲染问题
- [x] 新增 LaTex 公式编号功能

## 高亮一段代码[^code]

```python
@requires_authorization
class SomeClass:
    pass

if __name__ == '__main__':
    # A comment
    print 'hello world'
```

## 绘制表格

| 项目        | 价格   |  数量  |
| --------   | -----:  | :----:  |
| 计算机     | \$1600 |   5     |
| 手机        |   \$12   |   12   |
| 管线        |    \$1    |  234  |

