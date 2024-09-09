# AmapTools - 高德地图扩展工具

AmapTools 是一款 Tampermonkey 用户脚本，用于拦截高德地图（驾车、公交、步行）路线规划接口数据，并将其转换为 GeoJSON 格式。该工具允许用户复制或下载规划的路线数据，方便用于地理信息处理或其它开发需求。

## 功能

- **路线数据拦截**：拦截高德地图的驾车、公交、步行路线规划请求。
- **支持多种交通方式**：包括驾车、公交、步行三种出行方式。
- **GeoJSON 转换**：将路线规划结果转换为 GeoJSON 格式，便于与 GIS 系统集成。
- **数据导出**：支持直接将 GeoJSON 路线数据复制到剪贴板或下载为文件。
- **拖拽面板**：可拖拽工具面板，提升用户体验。

## 安装

### 1. 安装 Tampermonkey

确保你已安装 [Tampermonkey](https://www.tampermonkey.net/) 浏览器插件，它支持脚本的安装和管理。

### 2. 安装 AmapTools

- 直接从 GreasyFork 安装：[AmapTools - GreasyFork]([https://greasyfork.org/](https://greasyfork.org/zh-CN/scripts/507634-amaptools))
- 或者从 GitHub 安装：[AmapTools - GitHub](https://github.com/10D24D/AmapTools)

### 3. 支持的网站

该脚本支持以下网站的自动加载：

- `https://www.amap.com/*`
- `https://ditu.amap.com/*`
- `https://www.gaode.com/*`

## 使用方法

1. **打开高德地图**：进入高德地图网站，并进行路线规划。当路线生成时，脚本会自动拦截路线数据并显示工具面板。
2. **查看路线数据**：在工具面板中选择路线将自动并复制 GeoJSON 数据，也可以另外下载数据文件。

## 脚本设置

- **驾车路线**：拦截驾车路线并转换为 GeoJSON。
- **公交路线**：处理公交路线的数据结构，支持常规公交和轨道交通。
- **步行路线**：将步行路线数据转换为 GeoJSON 格式。

## 贡献

欢迎大家提交 Issue 或 Pull Request 来帮助改进该脚本！请访问 [GitHub 仓库](https://github.com/10D24D/AmapTools) 提交反馈和贡献代码。

## 许可协议

MIT License. 你可以自由使用、修改和分发本项目的代码。

## 免责声明

此脚本仅供学习、研究和个人使用。请勿将其用于商业用途或其他可能违反高德地图服务条款的场景。

使用本脚本可能涉及高德地图的 API 使用规则和数据版权。请确保你在使用本脚本时遵守相关法律法规和高德地图的服务协议。如果因此脚本的使用导致法律纠纷或责任，脚本的开发者不承担任何责任，使用者需自行承担后果。

高德地图是其合法持有人的注册商标，本脚本与高德地图没有任何官方关联。


---

> 如果你喜欢这个工具，请在 GreasyFork 或 GitHub 上给个 ⭐️ Star！
