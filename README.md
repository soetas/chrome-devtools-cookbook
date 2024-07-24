# chrome-devtools-cookbook

命令菜单快捷键: `shift + ctrl + p`

> 截图(screenshot)

命令行启动chrome浏览器:

```sh
start chrome --auto-open-devtools-for-tabs

```

## Elements

快速选择元素：`shift + ctrl + c`

快速隐藏选择的DOM节点: `H`

自动化脚本的元素定位： 

- 文本查询

- CSS选择器

- XPath表达式（绝对路径和相对路径）

快速定位元素: `ctrl + f`

> DOM元素断点调试类型：__子树节点修改__、__节点属性修改__ 和 __节点移除__

```css
@container body {

}

@supports {
  
}

```

## Console

启动快捷键: `shift + ctrl + j`

存储所选择的DOM元素为全局变量

定位元素:

```
> inspect(document.getElementById(''))

> $_ 

> $0 | $1 | $2 | $3 | $4

> $("selector")

> $$("selector")

> console.dir()

> console.table()

> console.group()
> console.groupEnd()

> console.debug()

> console.trace()

> console.assert()

> console.time()
> console.timeEnd()

> document.cookie

> copy()

> console.log('%c Chrome Devtools', 'background-color:#000; color:#ff0; padding:5px;')

> navigator.onLine

> getEventListeners()

> monitorEvents()

> queryObjects()

```

日志级别(log level): Verbose、Warnings、Errors和Info

Javascript错误类型:

- `TypeError`
- `RangeError`
- `ReferenceError`
- `SyntaxError`

node调试:

```sh
node --inspect-brk ***.js

```

> 实时表达式(live expression)

Chrome浏览器扩展插件: **console importer**


## Sources

> 断点调试(debugger)：单步跳过、单步执行和单步进入

函数调用栈(call stack)

> 编辑源文件并同步到本地文件

快速打开指定文件: `ctrl + p`

### source map

```json
{
  "version": 3,
  "file":"",
  "mappings":"",
  "sources":[],
  "sourcesContent":[],
  "x_google_ignoreList":[]
}

```

> 代码片段(javascript snippets)

断点类型: 

1. 条件断点
2. 单行断点
3. 日志断点
4. DOM断点
5. xhr/fetch断点
6. 事件监听器断点
7. 未捕获/捕获异常断点

## Performance

监控网页的各项性能指标生成性能报告

_FPS_

> 内存模型和内存分配


## Network

可用选项: 阻塞请求、持续记录、保留日志、禁用缓存和网速模式

URLs过滤语法：

- url:`url`

- status-code:`statusCode`

- method:`method`

- domain:`hostname:port`

- mime-type:`mimeType`

接口测试功能演示图:

![](https://img.picui.cn/free/2024/06/21/6674f0839280d.png)

_HAR文件_

> 离线和弱网测试、覆盖和新添HTTP响应头字段


## Memory

## Application 

> manifest & service workers

```json
{
  "name":"",
  "short_name""",
  "start_url":"",
  "description":"",
  "icons":[
    {
      "type":"",
      "sizes":""
    }

  ]

}

```

### Local Storage

### Session Storage

### IndexedDB

```js


```

### WebSQL

### Cookies

## Lighthouse

## Recorder(🆕)

> 录制和回放

## Rendering

监控页面重绘

- [ ]  Emulate a focused page

## Coverage 

## Animations

## Network conditions 

- Caching
- Network throttling
- User Agent

## Network request blocking

## Search

## Sensors

## Security



