# 阅读（Legado）书源合集

实测可用的「阅读」书源，每条都跑过 搜索 → 详情 → 目录 → 正文 全链路，规则坏掉的已就地修复后才写入这里。

| 文件 | 条数 | 说明 |
| --- | --- | --- |
| normal.json | 509 | 正常小说 |
| adult.json | 74 | 成人向 |
| others.json | 8 | 漫画 / 有声 |
| premium.json | 514 | 第 30 章仍可直读（无登录墙/付费提示） |

## 订阅地址（阅读 App → 书源管理 → 网络导入）

- `https://raw.githubusercontent.com/lebond2021/sources-own/main/normal.json`
- `https://raw.githubusercontent.com/lebond2021/sources-own/main/adult.json`
- `https://raw.githubusercontent.com/lebond2021/sources-own/main/others.json`
- `https://raw.githubusercontent.com/lebond2021/sources-own/main/premium.json`

清单与更新时间见 `https://raw.githubusercontent.com/lebond2021/sources-own/main/manifest.json`。

## 校验口径

1. 搜索命中书名，详情页有书名与作者；
2. 目录至少 5 章，章节正文 ≥200 字且汉字占比 ≥55%；
3. 不含「请登录 / VIP章节 / 购买本章 / 试读结束」等提示；
4. 额外抽查第 30 章，正文完整才算 premium；
5. 严格 TLS 复检：证书无效且不支持 http 的站点不进列表；
6. 分页章节按 nextContentUrl 拼回整章后统计字数。

更新时间：2026-11-24T11:12:30+08:00
