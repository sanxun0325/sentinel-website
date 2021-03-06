# Sentinel Go 0.5.0 发布，支持 Consul/Nacos 动态数据源

[Sentinel Go 0.5.0](https://github.com/alibaba/sentinel-golang/releases/tag/v0.5.0) 正式发布，该版本对一些核心功能及部分场景下的性能进行了优化，同时也带来了 Consul 和 Nacos 数据源扩展支持，欢迎社区关注使用！主要特性/改进如下：

- 新增 Consul 和 Nacos 数据源支持
- 热点参数流控支持任意的参数类型，如自定义的 struct
- Sentinel 初始化方式完善，支持直接传入 config.Entity 进行初始化
- 优化加载大量规则场景下的性能

Sentinel Go 版本正在快速演进中，我们非常欢迎感兴趣的开发者参与贡献，一起来主导未来版本的演进。Sentinel Go 版本的演进离不开社区的贡献。若您有意愿参与贡献，欢迎联系我们加入 Sentinel 贡献小组一起成长（Sentinel 开源讨论钉钉群：30150716）。我们会定期给活跃贡献者寄送小礼品，核心贡献者会提名为 committer，一起主导社区的演进。同时，也欢迎大家通过 [AHAS Sentinel 控制台](https://help.aliyun.com/document_detail/101132.html) 来快速体验 Sentinel 的能力。Now let's start hacking!
