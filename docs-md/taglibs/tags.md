# tags标签
|功能| 描述|
| :------------- |:-------------|
| 作用      | 读取文档标签, 读取包含`tags`属性的文档, 并生成标签HTML, 在文档标签和详情页面均可使用 |
| 属性      | `limit`: 读取条数, 返回对应的的HTML |  
| 备注 | 数据来源: `每个模型数据表`  |   


### 实例说明 

### 获取所有热搜词
```jettemplatelanguage
{{ yield tags() }}
```