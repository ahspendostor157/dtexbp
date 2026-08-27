最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计技术文档编写最佳实践
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.zjcfkrp.asia/blog/6686802.sHtMl

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://book.zjcfkrp.asia/blog/1957082.sHtMl

原标题：Performance：数据库分表解决单表过大性能衰减
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.zjcfkrp.asia/blog/2953596.sHtMl

原标题：进程线程并发基础概念讲解
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://book.zjcfkrp.asia/blog/8623103.sHtMl

原标题：线程调度优化减少上下文切换
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://book.zjcfkrp.asia/blog/2030915.sHtMl

原标题：架构复盘：消息死信处理架构避免消息丢失
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.zjcfkrp.asia/blog/3389109.sHtMl

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.zjcfkrp.asia/blog/5920400.sHtMl

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://book.zjcfkrp.asia/blog/0547948.sHtMl

原标题：golang 系统设计短链接服务实现思路
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://book.zjcfkrp.asia/blog/4131458.sHtMl

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.zjcfkrp.asia/blog/0311766.sHtMl

原标题：设计思考：分布式ID系统架构选型对比
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://book.zjcfkrp.asia/blog/4649533.sHtMl

原标题：golang 系统设计唯一索引业务使用场景
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://book.zjcfkrp.asia/blog/9610240.sHtMl

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://book.zjcfkrp.asia/blog/0369677.sHtMl

原标题：Performance：避免循环查询N+1问题完整优化
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.zjcfkrp.asia/blog/8875454.sHtMl

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://book.zjcfkrp.asia/blog/0262759.sHtMl

原标题：golang 系统设计监控告警阈值设置思路
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.zjcfkrp.asia/blog/8893180.sHtMl

原标题：线程池拒绝策略任务丢失防护
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://book.zjcfkrp.asia/blog/6119437.sHtMl

原标题：golang 系统设计接口向前兼容改造实操
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://book.zjcfkrp.asia/blog/0152422.sHtMl

原标题：golang mysql 慢查询日志开启分析
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://book.zjcfkrp.asia/blog/1146863.sHtMl

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.zjcfkrp.asia/blog/8082083.sHtMl

原标题：golang 系统设计熔断降级架构讲解
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://book.zjcfkrp.asia/blog/5091081.sHtMl

原标题：nodejs 日志轮转生产环境配置
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.zjcfkrp.asia/blog/0145688.sHtMl

原标题：webpack chunk 分包策略详解
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://book.zjcfkrp.asia/blog/8250436.sHtMl

原标题：nodejs 中间件模式原理剖析
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.zjcfkrp.asia/blog/4970455.sHtMl

原标题：项目实践：灰度发布简易方案落地实践
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://book.zjcfkrp.asia/blog/3497502.sHtMl

原标题：golang 系统设计监控大盘故障快速定位思路
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.zjcfkrp.asia/blog/1217133.sHtMl

原标题：消息队列消费堆积扩容处理
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://book.zjcfkrp.asia/blog/6202517.sHtMl

原标题：入门实践：简单批量处理脚本编写
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://book.zjcfkrp.asia/blog/7406273.sHtMl

原标题：开发记录：容器日志标准输出采集实践方案
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://book.zjcfkrp.asia/blog/7516209.sHtMl

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.zjcfkrp.asia/blog/1516500.sHtMl

原标题：安全复盘：Redis命令注入风险防护手段
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.zjcfkrp.asia/blog/1578177.sHtMl

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://book.zjcfkrp.asia/blog/7803310.sHtMl

原标题：golang 配置热更新不重启服务
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://book.zjcfkrp.asia/blog/5032759.sHtMl

原标题：golang redis 位图用户签到统计
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://book.zjcfkrp.asia/blog/5320322.sHtMl

原标题：Debug日志：生产环境偶发空指针异常排查
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.zjcfkrp.asia/blog/5372697.sHtMl

原标题：从零学习基础的接口请求与参数处理
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.zjcfkrp.asia/blog/6766943.sHtMl

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.zjcfkrp.asia/blog/2618335.sHtMl

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.zjcfkrp.asia/blog/7836221.sHtMl

原标题：方案对比：单体、微服务、模块化单体取舍
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://book.zjcfkrp.asia/blog/2132778.sHtMl

原标题：HTTPS 证书过期更新操作
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://book.zjcfkrp.asia/blog/0508332.sHtMl


二、踩坑排错｜Troubleshooting
原标题：实践：API版本控制多种策略落地对比实践
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.zjcfkrp.asia/blog/8690504.sHtMl

原标题：Practice：实现简单信号处理优雅停机实践
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://book.zjcfkrp.asia/blog/1652850.sHtMl

原标题：golang gorm 批量插入性能调优
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.zjcfkrp.asia/blog/3850500.sHtMl

原标题：Architecture：鉴权授权系统架构设计思路
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://book.zjcfkrp.asia/blog/9793881.sHtMl

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.zjcfkrp.asia/blog/2252840.sHtMl

原标题：golang gin 框架接口开发实战
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.zjcfkrp.asia/blog/0206200.sHtMl

原标题：golang 系统设计配置灰度下发简单实现思路
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.zjcfkrp.asia/blog/1206544.sHtMl

原标题：入门实践：实现简单文件读写功能
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.zjcfkrp.asia/blog/6496904.sHtMl

原标题：golang 系统设计灰度发布流量切分实现
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.zjcfkrp.asia/blog/1546684.sHtMl

原标题：系统字符集统一乱码修复
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.zjcfkrp.asia/blog/1871740.sHtMl

原标题：静态资源 404 路径打包修复
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://book.zjcfkrp.asia/blog/3540558.sHtMl

原标题：调优方案：服务实例扩容，水平扩展性能
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://book.zjcfkrp.asia/blog/3797491.sHtMl

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://book.zjcfkrp.asia/blog/6795830.sHtMl

原标题：入门实践：简单重试逻辑封装实现
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://book.zjcfkrp.asia/blog/7503672.sHtMl

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://book.zjcfkrp.asia/blog/5686233.sHtMl

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.zjcfkrp.asia/blog/3420325.sHtMl

原标题：golang prometheus metrics 埋点开发
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://book.zjcfkrp.asia/blog/1875912.sHtMl

原标题：零基础理解进程、线程基础概念区别
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.zjcfkrp.asia/blog/6025945.sHtMl

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.zjcfkrp.asia/blog/2431598.sHtMl

原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://book.zjcfkrp.asia/blog/6521104.sHtMl

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://book.zjcfkrp.asia/blog/1514153.sHtMl

原标题：设计思考：业务系统如何做故障隔离架构
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.zjcfkrp.asia/blog/2430103.sHtMl

原标题：golang 系统设计限流服务架构讲解
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://book.zjcfkrp.asia/blog/6793399.sHtMl

原标题：golang 系统设计分布式配置中心思路
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.zjcfkrp.asia/blog/8947533.sHtMl

原标题：golang 系统设计监控告警体系搭建思路
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://book.zjcfkrp.asia/blog/6100836.sHtMl

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://book.zjcfkrp.asia/blog/8649406.sHtMl

原标题：零基础理解JSON、XML数据格式处理
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://book.zjcfkrp.asia/blog/4270191.sHtMl

原标题：golang docker 运行 etcd 本地测试
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://book.zjcfkrp.asia/blog/6107204.sHtMl

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.zjcfkrp.asia/blog/0847568.sHtMl

原标题：golang dockerfile 多阶段构建详解
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://book.zjcfkrp.asia/blog/6363298.sHtMl

原标题：环境变量不生效问题修复
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://book.zjcfkrp.asia/blog/7434648.sHtMl

原标题：golang redis 缓存更新策略讲解
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.zjcfkrp.asia/blog/5286124.sHtMl

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://book.zjcfkrp.asia/blog/3984253.sHtMl

原标题：方案对比：同步事务vs事务消息最终一致性
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://book.zjcfkrp.asia/blog/5150188.sHtMl

原标题：DevOps：GitLabCI完整流水线配置示例
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.zjcfkrp.asia/blog/9899480.sHtMl

原标题：接口请求重试容错机制实现
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://book.zjcfkrp.asia/blog/2293847.sHtMl

原标题：跨域偶现失败配置修复
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.zjcfkrp.asia/blog/7888039.sHtMl

原标题：nodejs 接口限流防刷代码实现
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.zjcfkrp.asia/blog/4200284.sHtMl

原标题：Redis 大 key 拆分集群卡顿解决
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.zjcfkrp.asia/blog/0520757.sHtMl

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.zjcfkrp.asia/blog/6729253.sHtMl

三、实战开发｜Practice
原标题：Nginx 请求头大小上限调整
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.zjcfkrp.asia/blog/2287723.sHtMl

原标题：内网 DNS 不稳定随机报错排查
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://book.zjcfkrp.asia/blog/6918067.sHtMl

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://book.zjcfkrp.asia/blog/9729771.sHtMl

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://book.zjcfkrp.asia/blog/2049846.sHtMl

原标题：golang kafka 死信队列业务落地
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.zjcfkrp.asia/blog/8902976.sHtMl

原标题：安全复盘：定时任务权限过大风险管控
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.zjcfkrp.asia/blog/3759084.sHtMl

原标题：性能笔记：HTTP连接复用性能优化实践
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.zjcfkrp.asia/blog/1861629.sHtMl

原标题：入门实践：简单重试逻辑封装实现
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://book.zjcfkrp.asia/blog/8347700.sHtMl

原标题：golang 系统设计故障应急响应完整流程梳理
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://book.zjcfkrp.asia/blog/2783526.sHtMl

原标题：golang elasticsearch 索引设计思路
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://book.zjcfkrp.asia/blog/7879392.sHtMl

原标题：文件读写与异常捕获代码示例
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://book.zjcfkrp.asia/blog/2474863.sHtMl

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://book.zjcfkrp.asia/blog/5617522.sHtMl

原标题：网络读取超时设置连接挂起防护
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.zjcfkrp.asia/blog/4877626.sHtMl

原标题：正则表达式优化 CPU 占满问题
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://book.zjcfkrp.asia/blog/1203577.sHtMl

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.zjcfkrp.asia/blog/1975799.sHtMl

原标题：项目目录结构规范化最佳实践
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.zjcfkrp.asia/blog/4205971.sHtMl

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.zjcfkrp.asia/blog/8175209.sHtMl

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://book.zjcfkrp.asia/blog/5408279.sHtMl

原标题：踩坑记录：端口被占用导致服务启动失败
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://book.zjcfkrp.asia/blog/5168377.sHtMl

原标题：排错：多实例部署session共享失效登录失效
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://book.zjcfkrp.asia/blog/0138782.sHtMl

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://book.zjcfkrp.asia/blog/3480385.sHtMl

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://book.zjcfkrp.asia/blog/9792686.sHtMl

原标题：后端分页查询逻辑代码实现
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://book.zjcfkrp.asia/blog/8651738.sHtMl

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.zjcfkrp.asia/blog/1643434.sHtMl

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://book.zjcfkrp.asia/blog/4470246.sHtMl

原标题：golang etcd 租约 lease 过期机制
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://book.zjcfkrp.asia/blog/7527492.sHtMl

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://book.zjcfkrp.asia/blog/4543289.sHtMl

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://book.zjcfkrp.asia/blog/2636092.sHtMl

原标题：开发记录：敏感数据加密存储解密业务实践
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://book.zjcfkrp.asia/blog/6754025.sHtMl

原标题：极简 API 网关路由转发实现
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://book.zjcfkrp.asia/blog/0895056.sHtMl

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://book.zjcfkrp.asia/blog/4681418.sHtMl

原标题：WSL 内存上限限制防止资源耗尽
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.zjcfkrp.asia/blog/2520343.sHtMl

原标题：开发记录：跨域中间件完整配置与边界处理
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.zjcfkrp.asia/blog/4568400.sHtMl

原标题：golang gin 中间件执行顺序讲解
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://book.zjcfkrp.asia/blog/3562554.sHtMl

原标题：golang 系统设计 rest http 方法使用原则
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://book.zjcfkrp.asia/blog/3574799.sHtMl

原标题：记一次第三方SDK版本兼容引发线上故障
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.zjcfkrp.asia/blog/2345405.sHtMl

原标题：hosts 配置本地回环访问修复
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.zjcfkrp.asia/blog/3760300.sHtMl

原标题：数据库连接及时关闭连接泄漏
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://book.zjcfkrp.asia/blog/1661884.sHtMl

原标题：设计思考：业务系统如何设计优雅失败架构
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://book.zjcfkrp.asia/blog/5924944.sHtMl

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.zjcfkrp.asia/blog/5778451.sHtMl

四、架构设计｜Architecture
原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://book.zjcfkrp.asia/blog/7402214.sHtMl

原标题：golang k8s 节点污点容忍度配置
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.zjcfkrp.asia/blog/4836655.sHtMl

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://book.zjcfkrp.asia/blog/3503441.sHtMl

原标题：全局时间标准统一逻辑错乱修复
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://book.zjcfkrp.asia/blog/3194724.sHtMl

原标题：Performance：数据库分表解决单表过大性能衰减
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.zjcfkrp.asia/blog/0899654.sHtMl

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://book.zjcfkrp.asia/blog/4764835.sHtMl

原标题：极简 API 网关路由转发实现
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.zjcfkrp.asia/blog/8972128.sHtMl

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.zjcfkrp.asia/blog/3339798.sHtMl

原标题：新手指南：看懂开源项目的Issue与PR
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.zjcfkrp.asia/blog/3828223.sHtMl

原标题：移动端适配 rem vw 方案对比
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://book.zjcfkrp.asia/blog/8805213.sHtMl

原标题：手写简易 RPC 服务通信原型
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.zjcfkrp.asia/blog/2316641.sHtMl

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.zjcfkrp.asia/blog/3677768.sHtMl

原标题：golang 系统设计技术方案评审关注点清单参考
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://book.zjcfkrp.asia/blog/2503946.sHtMl

原标题：golang kafka 消费者偏移量管理
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://book.zjcfkrp.asia/blog/9980520.sHtMl

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://book.zjcfkrp.asia/blog/8580273.sHtMl

原标题：快速入门异步编程基础模型
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://book.zjcfkrp.asia/blog/8468095.sHtMl

原标题：golang 批量任务协程控制防雪崩
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.zjcfkrp.asia/blog/4519298.sHtMl

原标题：零基础理解进程、线程基础概念区别
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.zjcfkrp.asia/blog/6514055.sHtMl

?
