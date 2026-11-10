<div align="center">

# Hi，我是小锅盖 👋

**Java 后端开发 · 自由职业 · [baomidou 苞米豆](https://github.com/baomidou) 组织成员 · [MyBatis-Plus](https://github.com/baomidou/mybatis-plus) 长期贡献者**

📍 成都 &nbsp;·&nbsp; 🗓️ GitHub since 2016 &nbsp;·&nbsp; 💬 欢迎聊 ORM、SQL 和开源协作

[![Followers](https://img.shields.io/github/followers/huayanYu?style=flat-square&logo=github&label=Followers&color=2f81f7)](https://github.com/huayanYu?tab=followers)
[![Java](https://img.shields.io/badge/Java-%23ED8B00?style=flat-square&logo=openjdk&logoColor=white)](https://github.com/baomidou/mybatis-plus)
[![Chengdu](https://img.shields.io/badge/Location-Chengdu-181717?style=flat-square)](https://github.com/huayanYu)
[![Mail](https://img.shields.io/badge/Email-Contact-2f81f7?style=flat-square&logo=gmail&logoColor=white)](mailto:tracy5546@gmail.com)

</div>

---

## 👋 关于我

- `@huayanYu`，朋友们叫我**小锅盖**，坐标成都，一名自由职业的 Java 后端开发；行业侧长期做**城市级智慧停车**的生产系统。
- 从 2017 年起给 [MyBatis-Plus](https://github.com/baomidou/mybatis-plus) 提交代码，现在是 [苞米豆（baomidou）](https://github.com/baomidou) 组织成员，也参与 [dynamic-datasource](https://github.com/baomidou/dynamic-datasource) 及其文档、示例仓库。
- 日常在 ORM 内核、SQL 解析、多版本兼容和构建/测试体系之间来回切换：写功能、修 bug、review PR、折腾 CI。
- 习惯用可复现的用例和回归测试来讨论问题。

## 🔭 最近在忙

| 方向 | 在做的事 |
| --- | --- |
| 🌿 GraalVM Native Image | 反射/资源注册收敛为「静态 json + Spring AOT」单轨，XML 资源跟随 `mapper-locations`，补扫 lambda 捕获类，补上 native image 冒烟测试 |
| 🧩 兼容性 | Spring Boot 3/4 适配、JDK 17/21/25 CI 矩阵、Lombok 与依赖升级、字节码兼容基线校验 |
| 🧪 工程质量 | 测试分层（`@Tag`）、用例去重与规范化、GitHub Actions 升级、Gradle 并行构建 |
| ⚙️ ORM 内核 | 分页 count SQL 的 JSqlParser 截断防护、多列 `IN` / `NOT IN`、`MybatisEnumTypeHandler` 缓存优化、代码生成器 jspecify 注解 |

## 🛠️ 常用技术栈

**开源 / 内核**：`Java` · `Spring Boot` · `MyBatis / MyBatis-Plus` · `Maven / Gradle` · `SQL / JSqlParser` · `GraalVM Native Image` · `JUnit 5` · `GitHub Actions`

**生产系统**：`Spring Cloud` · `Redis / MQ` · `MySQL / PostgreSQL` · `Elasticsearch` · `Vue / 小程序` · `Nacos / 容器化` · `日志 · 链路 · 监控`

## 🏙 行业背景与工程习惯

从设备接入、进出场与计费，到支付 / 开票 / 对账与运营值守，后台、小程序、H5、岗亭与手持端都要协同；既有长期维护的 Java 8 / Spring Cloud 存量系统，也有 Java 21 / Spring Boot 3.5 的新一代服务。

| 维度 | 我的习惯 |
| --- | --- |
| 🧱 代码风格 | 分层与命名统一，参数校验 + 全局异常 + 统一返回体；日志用占位符、带 traceId、每笔业务只留必要 INFO；码值收敛到枚举，格式交给 Spotless / Prettier；注释写「约束与为什么」，不复述代码 |
| 🔁 正确性优先 | 支付回调按「验签 → 分布式锁 → 条件更新 → 事务 → 提交后动作」处理，重复通知、并发竞态、补单与对账都有兜底；新逻辑默认带开关、留兼容垫片，随时可回滚 |
| 📋 变更留痕 | 提交说明写清根因、方案、验证结论与发布顺序 / 回滚；发版前先跑等价 SELECT、DDL 先行，编译、构建与冒烟结果落档；TODO 是带优先级、观察期和复核结论的活台账 |
| 🛡️ 边界感 | 凭据、权限、PII 与注入风险是红线；文档里明确区分「代码能做的 / 需要运维配合的 / 代码做不到的」，不拿「应该没问题」当结论 |
| 🧭 协作方式 | 文档先行、小步提交、可回滚可暂停；把排障路径和领域知识沉淀成 SOP 与检查清单，让下一个人（或 AI）能直接接手 |

一句话概括：**先想清楚怎么验证和回滚，再动手改代码。**

## 🌱 关注方向

ORM 内核与 SQL 解析的正确性、多版本 JDK / Spring Boot 的长期兼容、测试可维护性，以及 Java 原生镜像在真实项目里的落地。

## 🤝 一起交流

- MyBatis-Plus、dynamic-datasource 相关的 issue / PR，尤其是能稳定复现的问题和回归用例，随时 @ 我。
- 也欢迎聊 Java 后端、ORM 设计、开源协作与技术选型；消息我会尽量回复，偶尔会被 CI 耽误一会儿 😄

## 📫 找到我

- GitHub：[@huayanYu](https://github.com/huayanYu)
- Email：[tracy5546@gmail.com](mailto:tracy5546@gmail.com)

## 📊 一点数据

- 2026 年至今：**224 次提交 · 18 个 PR · 9 个 issue**（统计至 2026-11-10）
- 主要贡献仓库：[baomidou/mybatis-plus](https://github.com/baomidou/mybatis-plus)、[baomidou/dynamic-datasource](https://github.com/baomidou/dynamic-datasource) 及其文档/示例仓库
- 2017 年第一次给 MyBatis-Plus 提交代码，到现在还在和 ORM、CI 打交道

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=huayanYu&theme=github-dark-blue&hide_border=true" alt="GitHub streak" />
</div>

---

<div align="center"><sub>由 ☕ 和 <code>./gradlew test</code> 维护 · 发现错别字欢迎提 PR</sub></div>

<!---
huayanYu/huayanYu is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
