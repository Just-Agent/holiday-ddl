<div align="center">

# Holiday-DDL

法定节假日、二十四节气、考试周、寒暑假和日常倒计时。

[![GitHub Pages](https://img.shields.io/badge/Pages-live-EAB308?style=for-the-badge)](https://just-agent.github.io/holiday-ddl/)
[![Just-DDL](https://img.shields.io/badge/Just--DDL-network-101626?style=for-the-badge)](https://just-agent.github.io/just-ddl/)
[![Status](https://img.shields.io/badge/Demo-completed-059669?style=for-the-badge)](https://just-agent.github.io/holiday-ddl/)

[专题页面](https://just-agent.github.io/holiday-ddl/) · [Just-DDL Hub](https://just-agent.github.io/just-ddl/#/topic/holiday-ddl) · [GitHub 仓库](https://github.com/Just-Agent/holiday-ddl)

</div>

## Demo 已完善

这个仓库不再只是空 Pages 骨架。当前已经包含完整 demo DDL 列表、搜索筛选、状态统计、来源说明和统一 Just-DDL Network 导航。数据风格参考 AllConfs 的会议列表结构，以及 SinoConf 的国内会议/预告/回顾入口。

## Demo DDL Seed

| DDL | 阶段 | 截止日 | 地点 | 来源类型 |
| --- | --- | --- | --- | --- |
| 端午节 2026 | Holiday | 2026-06-19 | China | Gov-style seed |
| 中秋节 2026 | Holiday | 2026-09-25 | China | Gov-style seed |
| 国庆节 2026 | Holiday | 2026-10-01 | China | Gov-style seed |
| 冬至 2026 | Solar term | 2026-12-22 | China | Calendar seed |
| 元旦 2027 | Holiday | 2027-01-01 | Global | Gov-style seed |
| 春节 2027 | Holiday | 2027-02-17 | China | Gov-style seed |
| 高校春季学期选课截止 | Campus | 2026-09-10 | Campus | Demo seed |
| 考研报名提醒 2026 | Registration | 2026-10-25 | China | Official-style seed |

## 后续生产化

| 模块 | 当前 | 下一步 |
| --- | --- | --- |
| 页面 | 完整 demo 页面已上线 | 替换为真实数据源输出 |
| 数据 | seed 数据在 index.html 内置 | 拆出 JSON/YAML schema |
| Actions | Pages 自动部署 | 增加 crawler、validator、link-check |
| Hub 联动 | 已接入 Just-DDL Hub | 加入更新时间和数据健康状态 |
| 小程序 | 结构已预留 | 复用同一 schema 输出小程序专题页 |

## References

- AllConfs: https://www.allconfs.org/
- SinoConf: https://sinoconf.napstic.cn/index

## License

当前仓库处于产品孵化阶段。正式开源协议会在发布稳定版本前补齐。