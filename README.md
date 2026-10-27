# 个人项目源码索引

GitHub 是各项目的源码权威；生产服务器只保留运行环境、密钥和业务数据。所有列出的仓库均为公开仓库。

| 项目 | 仓库 | 端口 | 源码状态 |
|---|---|---|---|
| K线之王 | [kline-master](https://github.com/XiaotianXuJoe/kline-master) | 3100 | 完整源码 |
| StockShape 股票形态选股 | [stockshape](https://github.com/XiaotianXuJoe/stockshape) | 3000 | 完整源码 |
| 学习计划管理系统 | [learning-plan](https://github.com/XiaotianXuJoe/learning-plan) | 80 / 3001 | 完整源码 |
| EasyCV 简历辅导平台 | [resume-coach](https://github.com/XiaotianXuJoe/resume-coach) | 3200 | 完整源码 |
| OD 题解工具站 | [od-toolkit](https://github.com/XiaotianXuJoe/od-toolkit) | 4000 / 4001 | 完整源码 |
| 方块对照实验俄罗斯方块 | [tetris-web](https://github.com/XiaotianXuJoe/tetris-web) | 8100 | 完整源码 |
| 幸运熊猫·注意力训练 | [lucky-panda](https://github.com/XiaotianXuJoe/lucky-panda) | 8200 | 完整源码 |
| 二维码生成管理工具 | [qrtool](https://github.com/XiaotianXuJoe/qrtool) | 8443 | 完整源码 |
| 闭眼笔记工厂 | [notefactory](https://github.com/XiaotianXuJoe/notefactory) | 8300 | 已从 v18 备份恢复完整源码 |
| 个股深度研究站 | [research-site](https://github.com/XiaotianXuJoe/research-site) | 3002 | 生成器、报告源码与监控脚本 |
| 服务器监控看板 | [server-dashboard](https://github.com/XiaotianXuJoe/server-dashboard) | 5000 | 静态看板与采集器 |
| 红白喜报生成工具 | [xibao-tool](https://github.com/XiaotianXuJoe/xibao-tool) | 3400 | 完整源码 |
| 小红书同步历史服务 | [xhs-sync](https://github.com/XiaotianXuJoe/xhs-sync) | 已停用 | 历史源码存档 |

## Agent 使用方式

1. 先读取 `projects.json`，按名称定位目标仓库。
2. 克隆目标仓库后，依次阅读 `README.md`、`AGENTS.md` 和 `docs/PRODUCTION.md`。
3. 在任务分支修改和测试，不要直接在生产服务器手工修改后不回写仓库。
4. 公开仓库中不得提交密码、API Key、Cookie、真实配置、用户数据、数据库、上传文件或日志。
5. 部署只同步源码；生产数据库和运行时文件必须独立备份并保留。

## 特别注意

- `notefactory`：源码来自服务器上的 v18 恢复备份。
- `xhs-sync`：历史存档，已停用，不要重新启动轮询。
- `project-index` 只保存索引，不是 monorepo；每个项目仍独立维护。
