# edu-objection-response-classifier

- 产品名称：`edu-objection-response-classifier`
- 产品编号：`JLZ-EDU-SK-019`
- 产品类型：Skill
- 所属业务板块：02 销售转化中心
- 作者/维护方：广州金励泽科技服务有限公司
- 研发版本：1.0.1
- 当前状态：**G9_PRE_RELEASE_ACCEPTED / NOT_RUNTIME_VERIFIED**
- 产品规格书：[PRODUCT_SPEC.md](PRODUCT_SPEC.md)
- 使用说明：[USAGE.md](USAGE.md)
- 安装包：[`dist/edu-objection-response-classifier-v1.0.1.zip`](dist/edu-objection-response-classifier-v1.0.1.zip)

## 产品功能

价格、时间、效果和信任等销售异议分类。

- 主要输入：家长原话、异议场景、课程与价格、已提供证据、决策阶段
- 主要输出：异议类型、真实顾虑假设、回应要点、证据需求、可验证话术和不可承诺项

## 本地验证

- 测试案例：[tests/TEST_CASES.md](tests/TEST_CASES.md)
- 结构测试：[tests/validate_package.ps1](tests/validate_package.ps1)
- 测试结果：[test-results/v1.0.1.json](test-results/v1.0.1.json)

本地通过证明文件结构、产品契约、分层测试、确定性脚本和安装包完整性通过；生成式模型行为仍为 NOT_RUNTIME_VERIFIED，不代表 WorkBuddy 解析、安装、调用或审核通过。

## 依赖与数据

- 第三方运行依赖：无。
- 默认外部API：无。
- 不要求用户提供API Key。
- 仅处理用户主动提供或明确授权的数据。

## 开源许可证

License: Apache-2.0.

本仓库为免费开放的开源项目。任何人均可依照 Apache License 2.0 使用、修改和分发本项目内容。完整法律条款见 [LICENSE](LICENSE)。
