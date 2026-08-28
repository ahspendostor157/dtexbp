最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计服务优雅停机完整流程
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：www.read.shengquanyk.cn/Article/details/442217.sHtML

原标题：golang 静态编译缩小镜像体积
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：www.read.shengquanyk.cn/Article/details/056483.sHtML

原标题：K8s 镜像拉取网络故障修复
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：www.read.shengquanyk.cn/Article/details/425103.sHtML

原标题：新手指南：本地多版本环境共存配置
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：www.read.shengquanyk.cn/Article/details/451342.sHtML

原标题：设计思考：分布式锁选型、风险、业务约束
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：www.read.shengquanyk.cn/Article/details/602414.sHtML

原标题：后端分页查询逻辑代码实现
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：www.read.shengquanyk.cn/Article/details/220692.sHtML

原标题：golang websocket 消息广播实现
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：www.read.shengquanyk.cn/Article/details/669051.sHtML

原标题：实践：数据库备份脚本自动化编写实践
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：www.read.shengquanyk.cn/Article/details/073039.sHtML

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：www.read.shengquanyk.cn/Article/details/337361.sHtML

原标题：golang 系统设计业务指标系统指标定义思路
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：www.read.shengquanyk.cn/Article/details/602147.sHtML

原标题：部署实践：服务器时间同步chrony配置
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：www.read.shengquanyk.cn/Article/details/930562.sHtML

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：www.read.shengquanyk.cn/Article/details/497244.sHtML

原标题：golang http grpc 全链路埋点示例
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：www.read.shengquanyk.cn/Article/details/086024.sHtML

原标题：包管理器依赖冲突解决方案
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：www.read.shengquanyk.cn/Article/details/351068.sHtML

原标题：记一次升级操作系统内核引发服务不稳定
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：www.read.shengquanyk.cn/Article/details/264697.sHtML

原标题：golang 分布式 ID 雪花算法实现
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：www.read.shengquanyk.cn/Article/details/300489.sHtML

原标题：golang docker 部署 kafka 本地调试
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：www.read.shengquanyk.cn/Article/details/641330.sHtML

原标题：实战项目：GitHubAction自动测试构建实践
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：www.read.shengquanyk.cn/Article/details/013523.sHtML

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：www.read.shengquanyk.cn/Article/details/872716.sHtML

原标题：golang es 批量 bulk 操作性能调优
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：www.read.shengquanyk.cn/Article/details/191020.sHtML

原标题：提交第一个开源 PR 完整流程
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：www.read.shengquanyk.cn/Article/details/785417.sHtML

原标题：网关超时时间调优后端等待
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：www.read.shengquanyk.cn/Article/details/208407.sHtML

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：www.read.shengquanyk.cn/Article/details/140364.sHtML

原标题：golang 系统设计数据库死锁分析规避
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：www.read.shengquanyk.cn/Article/details/226273.sHtML

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：www.read.shengquanyk.cn/Article/details/759179.sHtML

原标题：ORM 隐式慢查询问题规避
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：www.read.shengquanyk.cn/Article/details/237615.sHtML

原标题：程序日志分级输出规范实践
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：www.read.shengquanyk.cn/Article/details/489306.sHtML

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：www.read.shengquanyk.cn/Article/details/627894.sHtML

原标题：golang 系统设计 commit 提交规范约定
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：www.read.shengquanyk.cn/Article/details/048202.sHtML

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：www.read.shengquanyk.cn/Article/details/271780.sHtML

原标题：golang jwt 过期刷新 token 实现
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：www.read.shengquanyk.cn/Article/details/560990.sHtML

原标题：golang 优雅处理数据库事务
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：www.read.shengquanyk.cn/Article/details/848469.sHtML

原标题：nodejs 单元测试 jest 实操教程
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：www.read.shengquanyk.cn/Article/details/263819.sHtML

原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：www.read.shengquanyk.cn/Article/details/880381.sHtML

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：www.read.shengquanyk.cn/Article/details/237432.sHtML

原标题：nodejs 单元测试 jest 实操教程
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：www.read.shengquanyk.cn/Article/details/257270.sHtML

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：www.read.shengquanyk.cn/Article/details/935060.sHtML

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：www.read.shengquanyk.cn/Article/details/948964.sHtML

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：www.read.shengquanyk.cn/Article/details/795746.sHtML

原标题：golang 系统设计技术方案评审关注点清单参考
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：www.read.shengquanyk.cn/Article/details/537834.sHtML


二、踩坑排错｜Troubleshooting
原标题：Git 标签版本标记发布管理
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：www.read.shengquanyk.cn/Article/details/345432.sHtML

原标题：开发记录：分布式ID生成器实现与压力测试
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：www.read.shengquanyk.cn/Article/details/058095.sHtML

原标题：开发记录：跨域中间件完整配置与边界处理
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：www.read.shengquanyk.cn/Article/details/188874.sHtML

原标题：golang 系统设计 json 解析性能优化实操
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：www.read.shengquanyk.cn/Article/details/256533.sHtML

原标题：golang 系统设计分布式锁不同场景选型对比
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：www.read.shengquanyk.cn/Article/details/866212.sHtML

原标题：golang 系统设计大文件上传架构
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：www.read.shengquanyk.cn/Article/details/238848.sHtML

原标题：请求工具封装统一异常处理
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：www.read.shengquanyk.cn/Article/details/182204.sHtML

原标题：golang 系统设计读写分离架构示例
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：www.read.shengquanyk.cn/Article/details/905037.sHtML

原标题：多套环境灵活切换配置方案
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：www.read.shengquanyk.cn/Article/details/767975.sHtML

原标题：Practice：实现业务唯一流水号生成组件实践
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：www.read.shengquanyk.cn/Article/details/529436.sHtML

原标题：入门实践：简单图片上传预览本地demo
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：www.read.shengquanyk.cn/Article/details/003843.sHtML

原标题：golang 系统设计数据库慢请求排查流程
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：www.read.shengquanyk.cn/Article/details/423950.sHtML

原标题：分布式锁失效问题排查修复
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：www.read.shengquanyk.cn/Article/details/597229.sHtML

原标题：golang minio 对象存储接口开发
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：www.read.shengquanyk.cn/Article/details/606489.sHtML

原标题：开源实践：维护开源项目Issue管理经验总结
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：www.read.shengquanyk.cn/Article/details/905324.sHtML

原标题：入门实践：Git分支创建切换合并完整演示
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：www.read.shengquanyk.cn/Article/details/377523.sHtML

原标题：golang 系统设计 protobuf json 性能对比
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：www.read.shengquanyk.cn/Article/details/260521.sHtML

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：www.read.shengquanyk.cn/Article/details/561253.sHtML

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：www.read.shengquanyk.cn/Article/details/001981.sHtML

原标题：golang redis 缓存预热实现思路
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：www.read.shengquanyk.cn/Article/details/771538.sHtML

原标题：golang kafka 死信队列业务落地
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：www.read.shengquanyk.cn/Article/details/950833.sHtML

原标题：前后端会话登录状态持久化
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：www.read.shengquanyk.cn/Article/details/919199.sHtML

原标题：golang 系统设计告警规则阈值设置方法论
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：www.read.shengquanyk.cn/Article/details/872719.sHtML

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：www.read.shengquanyk.cn/Article/details/636651.sHtML

原标题：零基础理解内存溢出基础现象与表现
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：www.read.shengquanyk.cn/Article/details/694346.sHtML

原标题：运维笔记：服务器日志轮转logrotate配置
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：www.read.shengquanyk.cn/Article/details/203660.sHtML

原标题：实战：GraphQL服务搭建与CRUD实操
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：www.read.shengquanyk.cn/Article/details/704613.sHtML

原标题：实践：分布式事务本地模拟验证实践
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：www.read.shengquanyk.cn/Article/details/412807.sHtML

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：www.read.shengquanyk.cn/Article/details/969424.sHtML

原标题：浏览器内存泄漏排查前端页面
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：www.read.shengquanyk.cn/Article/details/887105.sHtML

原标题：重复提交幂等防护再次讲解
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：www.read.shengquanyk.cn/Article/details/422022.sHtML

原标题：golang minio 存储桶权限管控配置
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：www.read.shengquanyk.cn/Article/details/757608.sHtML

原标题：golang k8s 本地 minikube 调试应用
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：www.read.shengquanyk.cn/Article/details/106852.sHtML

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：www.read.shengquanyk.cn/Article/details/491856.sHtML

原标题：golang 系统设计延迟队列业务实现
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：www.read.shengquanyk.cn/Article/details/586726.sHtML

原标题：开发测试生产多环境配置区分
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：www.read.shengquanyk.cn/Article/details/236768.sHtML

原标题：零基础学习简单正则表达式实战案例
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：www.read.shengquanyk.cn/Article/details/902869.sHtML

原标题：golang 系统设计日志系统架构思路
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：www.read.shengquanyk.cn/Article/details/798761.sHtML

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：www.read.shengquanyk.cn/Article/details/460505.sHtML

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：www.read.shengquanyk.cn/Article/details/850112.sHtML

三、实战开发｜Practice
原标题：golang 系统设计内部服务 mock 集成测试方案
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：www.read.shengquanyk.cn/Article/details/884656.sHtML

原标题：Performance：数据库索引优化常见错误案例
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：www.read.shengquanyk.cn/Article/details/289666.sHtML

原标题：实践：前后端分离项目登录状态保持完整方案
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：www.read.shengquanyk.cn/Article/details/407183.sHtML

原标题：Performance：避免全表扫描索引失效场景汇总
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：www.read.shengquanyk.cn/Article/details/369997.sHtML

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：www.read.shengquanyk.cn/Article/details/578636.sHtML

原标题：golang 系统设计大事务拆分实战思路
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：www.read.shengquanyk.cn/Article/details/268146.sHtML

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：www.read.shengquanyk.cn/Article/details/023911.sHtML

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：www.read.shengquanyk.cn/Article/details/705045.sHtML

原标题：CDN 缓存刷新获取最新静态资源
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：www.read.shengquanyk.cn/Article/details/567609.sHtML

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：www.read.shengquanyk.cn/Article/details/730384.sHtML

原标题：新手向：开源项目fork与同步上游代码
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：www.read.shengquanyk.cn/Article/details/043239.sHtML

原标题：golang 系统设计 monorepo 仓库管理方案
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：www.read.shengquanyk.cn/Article/details/578457.sHtML

原标题：安全笔记：GitHubAction密钥安全管理
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：www.read.shengquanyk.cn/Article/details/773134.sHtML

原标题：主干开发团队代码合并策略
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：www.read.shengquanyk.cn/Article/details/995810.sHtML

原标题：gitignore 文件编写过滤规则
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：www.read.shengquanyk.cn/Article/details/851363.sHtML

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：www.read.shengquanyk.cn/Article/details/222843.sHtML

原标题：零基础理解JSON、XML数据格式处理
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：www.read.shengquanyk.cn/Article/details/788571.sHtML

原标题：实战：Redis管道批量操作性能优化实践
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：www.read.shengquanyk.cn/Article/details/859547.sHtML

原标题：接口限流逻辑简单模拟实现
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：www.read.shengquanyk.cn/Article/details/998550.sHtML

原标题：golang 日志 zap 结构化日志实践
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：www.read.shengquanyk.cn/Article/details/564731.sHtML

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：www.read.shengquanyk.cn/Article/details/726156.sHtML

原标题：性能调优：MySQL查询性能优化实战清单
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：www.read.shengquanyk.cn/Article/details/322175.sHtML

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：www.read.shengquanyk.cn/Article/details/655697.sHtML

原标题：HelloTest：理解集成测试基础编写思路
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：www.read.shengquanyk.cn/Article/details/807997.sHtML

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：www.read.shengquanyk.cn/Article/details/342732.sHtML

原标题：golang 多协程任务池并发控制
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：www.read.shengquanyk.cn/Article/details/531363.sHtML

原标题：golang cron 定时任务防并发执行
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：www.read.shengquanyk.cn/Article/details/044835.sHtML

原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：www.read.shengquanyk.cn/Article/details/733927.sHtML

原标题：排错：前端sourcemap错误线上无法定位报错
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：www.read.shengquanyk.cn/Article/details/151765.sHtML

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：www.read.shengquanyk.cn/Article/details/830764.sHtML

原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：www.read.shengquanyk.cn/Article/details/450797.sHtML

原标题：golang 系统设计定时任务执行超时中断防护
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：www.read.shengquanyk.cn/Article/details/169368.sHtML

原标题：前端打包分包加载提速方案
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：www.read.shengquanyk.cn/Article/details/270140.sHtML

原标题：5分钟快速搭建个人技术文档站点
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：www.read.shengquanyk.cn/Article/details/821028.sHtML

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：www.read.shengquanyk.cn/Article/details/552887.sHtML

原标题：golang 系统设计创建更新时间自动维护方案
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：www.read.shengquanyk.cn/Article/details/958730.sHtML

原标题：golang 系统设计防爬虫简单策略
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：www.read.shengquanyk.cn/Article/details/758285.sHtML

原标题：开源实践：维护开源项目Issue管理经验总结
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：www.read.shengquanyk.cn/Article/details/644326.sHtML

原标题：golang 系统设计日志系统架构思路
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：www.read.shengquanyk.cn/Article/details/804566.sHtML

原标题：golang 系统设计大事务拆分实战思路
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：www.read.shengquanyk.cn/Article/details/782771.sHtML

四、架构设计｜Architecture
原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：www.read.shengquanyk.cn/Article/details/451772.sHtML

原标题：golang 数据库慢查询监控实现
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：www.read.shengquanyk.cn/Article/details/752317.sHtML

原标题：golang k8s 基础概念 pod deployment
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：www.read.shengquanyk.cn/Article/details/845037.sHtML

原标题：排错：静态资源404，打包路径配置错误
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：www.read.shengquanyk.cn/Article/details/514287.sHtML

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：www.read.shengquanyk.cn/Article/details/973265.sHtML

原标题：nodejs 全局异常捕获进程防护
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：www.read.shengquanyk.cn/Article/details/339718.sHtML

原标题：内网测试服务搭建团队调试
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：www.read.shengquanyk.cn/Article/details/539582.sHtML

原标题：数值类型溢出错乱问题修复
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：www.read.shengquanyk.cn/Article/details/614789.sHtML

原标题：golang 系统设计分库分表扩容平滑迁移
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：www.read.shengquanyk.cn/Article/details/563561.sHtML

原标题：golang 系统设计会话共享多实例部署
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：www.read.shengquanyk.cn/Article/details/466632.sHtML

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：www.read.shengquanyk.cn/Article/details/047005.sHtML

原标题：golang 系统设计消息重试次数间隔策略设置
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：www.read.shengquanyk.cn/Article/details/169416.sHtML

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：www.read.shengquanyk.cn/Article/details/487414.sHtML

原标题：golang 系统设计单元测试编写原则最佳实践
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：www.read.shengquanyk.cn/Article/details/944185.sHtML

原标题：nodejs 接口限流防刷代码实现
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：www.read.shengquanyk.cn/Article/details/898873.sHtML

原标题：入门实践：项目配置文件多环境管理方案
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：www.read.shengquanyk.cn/Article/details/632861.sHtML

原标题：架构笔记：业务操作审计日志系统架构设计
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：www.read.shengquanyk.cn/Article/details/372266.sHtML

原标题：开源项目构建失败排查步骤
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：www.read.shengquanyk.cn/Article/details/493654.sHtML

?
