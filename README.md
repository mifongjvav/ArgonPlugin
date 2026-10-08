# ArgonPlugin

解决KN的限制，并扩展功能

## 安装

```bash
git clone https://github.com/mifongjvav/ArgonPlugin.git
```

在 `kn.codemao.cn` 上打开 `DevTools`

转到 `源代码/来源`

点击 `替换` ，并添加 `ArgonPlugin` 文件夹

## 功能列表

### 优化

- 解除三角函数限制
- 提升递归限制到100000
- 略微提升一步执行速度
- 修复数学运算的tanh
- 移除音频导入限制
- Linux 不会在创作环境检测中显示为不支持的操作系统

### 功能

- 基于atan的eval（使用 `atan(转字符串("JS代码"))` 触发）
- 基于复制列表的排序（使用 `复制 [同一个列表] 到 [同一个列表]` 触发）
- 基于复制列表的快速插入n个列表项（使用 `复制 (数值) 到 [任意列表]` 触发）
- 基于数学运算的eval（在数学运算积木中像JS那样调用eval即可，如果返回值为字符串，将返回1）
- 内置CUE插件支持，使用定制版CUELite

## 许可证

不清楚

## 贡献要求

使用Preitter格式化

使用MarkdownLint检测README
