# awesome-go

## Actor 模型

_用于构建基于 Actor 的程序的库_

- [Ergo](https://github.com/ergo-services/ergo) - Golang 的基于 Actor 的框架，具有网络透明性，灵感来自 Erlang。
- [ProtoActor](https://github.com/asynkron/protoactor-go) - 高效分布式 Actor 框架，支持 Go、C#、Java/Kotlin。

## 人工智能 (AI)

_用于构建 AI 程序的库_

- [langchaingo](https://github.com/tmc/langchaingo) - 基于语言模型开发应用的框架。
- [LocalAI](https://github.com/mudler/LocalAI) - 开源的 OpenAI 替代方案，可以自托管 AI 模型。

## 音频与音乐

_用于处理音频的库_

- [flac](https://github.com/mewkiz/flac) - 原生 Go FLAC 编码/解码库。
- [GoAudio](https://github.com/DylanMeeus/GoAudio) - Go 语言的音频处理库。
- [Oto](https://github.com/hajimehoshi/oto) - 支持多平台播放音频的低级别库。

## 身份认证与 OAuth

_用于实现身份认证方案的库_

- [authboss](https://github.com/volatiletech/authboss) - 模块化身份认证系统，适合快速开发 web 应用时直接使用。
- [casbin](https://github.com/hsluoyz/casbin) - 支持 ACL、RBAC、ABAC 的访问控制库。
- [gologin](https://github.com/dghubble/gologin) - 支持 OAuth1 和 OAuth2 的身份认证处理器。
- [goth](https://github.com/markbates/goth) - 简洁的 OAuth 和 OAuth2 处理库，支持多种身份提供商。
- [jwt-go](https://github.com/golang-jwt/jwt) - 全功能 JSON Web Token (JWT) 实现库，支持解析、验证、生成和签名。
- [keto](https://github.com/ory/keto) - 开源的权限系统，基于 Google 的 Zanzibar 论文实现，支持 ACL、RBAC 等模型。
- [oauth2](https://github.com/golang/oauth2) - 通用 OAuth 2.0 包，支持 JWT、Google API、Compute Engine 等。
- [oidc](https://github.com/zitadel/oidc) - 使用简单的 OpenID Connect 客户端和服务器库，通过 OpenID 基金会认证。

## 区块链工具

### 最常用的工具
- [cosmos-sdk](https://github.com/cosmos/cosmos-sdk): 构建公共区块链的框架，主要用于 Cosmos 生态。
- [go-ethereum](https://github.com/ethereum/go-ethereum): 以太坊协议的官方 Go 实现。
- [tendermint](https://github.com/tendermint/tendermint): 高性能的中间件，用于将状态机转换为拜占庭容错的区块链系统。

## 机器人开发库

### 最常用的工具
- [bot](https://github.com/go-telegram/bot): 无依赖的 Telegram 机器人库，包含 UI 组件。
- [go-chat-bot](https://github.com/go-chat-bot/bot): 用于 IRC、Slack 和 Telegram 的通用聊天机器人。
- [telebot](https://github.com/tucnak/telebot): 用 Go 语言编写的 Telegram 机器人框架。

## 构建自动化工具

### 最常用的工具
- [air](https://github.com/cosmtrek/air): Go 应用的实时重载工具。
- [Task](https://github.com/go-task/task): 类似于 Make 的简单替代工具，用于任务管理。
- [mage](https://github.com/magefile/mage): 使用 Go 语言编写的 make/rake 类构建工具。

## 命令行界面开发库

### 常用库
- [cobra](https://github.com/spf13/cobra): 用于构建现代 Go 命令行应用程序的工具。
- [pflag](https://github.com/spf13/pflag): Go 语言 `flag` 包的替代品，支持 POSIX/GNU 风格的命令行参数解析。
- [urfave/cli](https://github.com/urfave/cli): 构建命令行应用的简单且有趣的包。

## 配置管理库

### 常用工具
- [viper](https://github.com/spf13/viper): 功能强大的配置管理库，支持 JSON、TOML、YAML 等多种格式。
- [env](https://github.com/caarlos0/env): 将环境变量解析为 Go 结构体的工具，支持默认值。
- [godotenv](https://github.com/joho/godotenv): 从 `.env` 文件加载环境变量的工具。

## 数据库工具

### 常用数据库实现
- [bbolt](https://github.com/etcd-io/bbolt): Go 实现的嵌入式键值数据库。
- [badger](https://github.com/dgraph-io/badger): 快速的键值存储，使用 Go 语言编写。
- [prometheus](https://github.com/prometheus/prometheus): 时间序列数据库与监控系统。

### SQL 构建器
- [gorm](https://github.com/go-gorm/gorm): 强大的 ORM 库，支持多种数据库。
- [sqlc](https://github.com/kyleconroy/sqlc): 从 SQL 生成类型安全代码的工具。
- [goqu](https://github.com/doug-martin/goqu): 直观的 SQL 构建和查询库。

## 分布式系统开发

### 常用工具
- [go-kit](https://github.com/go-kit/kit): 支持服务发现、负载均衡等功能的微服务工具包。
- [go-zero](https://github.com/tal-tech/go-zero): 提供稳定性保障的 Web 和 RPC 框架，集成了代码生成工具 `goctl`。
- [rpcx](https://github.com/smallnest/rpcx): 类似于 Dubbo 的分布式可插拔 RPC 框架。

## 邮件处理工具

### 常用库
- [email](https://github.com/jordan-wright/email): 灵活且健壮的邮件库，用于创建和发送邮件。
- [gomail](https://github.com/go-gomail/gomail): 简单易用的邮件发送库。
- [MailHog](https://github.com/mailhog/MailHog): 邮件和 SMTP 测试工具，具有 Web 界面和 API 接口。

## 常用的GUI开发库

### 工具包
- [fyne](https://github.com/fyne-io/fyne) - 基于Material Design的跨平台GUI库，支持Linux、macOS、Windows、BSD、iOS和Android。
- [gio](https://gioui.org) - 即时模式的跨平台GUI库，支持主要平台：Linux、macOS、Windows、Android、iOS等。
- [gotk3](https://github.com/gotk3/gotk3) - GTK3的Go语言绑定。
- [qt](https://github.com/therecipe/qt) - Go语言的Qt绑定，支持多个平台：Windows、macOS、Linux等。
- [Wails](https://wails.io) - 利用系统自带的HTML渲染器开发Mac、Windows和Linux桌面应用。
- [webview](https://github.com/zserge/webview) - 简单的跨平台Webview，适用于Windows、macOS、Linux。

### 交互工具
- [robotgo](https://github.com/go-vgo/robotgo) - 跨平台的GUI系统自动化库，可以控制鼠标、键盘等。
- [systray](https://github.com/getlantern/systray) - 用于创建系统通知区域图标的跨平台库。

## 硬件交互常用库
- [ghw](https://github.com/jaypipes/ghw) - 硬件信息探测库。
- [go-rpio](https://github.com/stianeikeland/go-rpio) - GPIO控制库，适用于树莓派，不需要cgo。
- [gocv](https://github.com/hybridgroup/gocv) - 基于OpenCV的计算机视觉库。

## 图片处理库
- [imaging](https://github.com/disintegration/imaging) - 简单易用的Go图像处理库。
- [gg](https://github.com/fogleman/gg) - 2D图形渲染库。
- [bimg](https://github.com/h2non/bimg) - 使用libvips实现高效图像处理的小型库。
- [go-qrcode](https://github.com/yeqown/go-qrcode) - 支持自定义颜色和图标的二维码生成库。

## IoT物联网开发库
- [periph](https://periph.io/) - 设备外设接口库，帮助开发低层硬件交互代码。
- [gobot](https://github.com/hybridgroup/gobot/) - 机器人、物理计算和物联网的框架。

## 任务调度
- [gocron](https://github.com/go-co-op/gocron) - 简单易用的Go语言任务调度库。
- [gron](https://github.com/roylee0704/gron) - 使用简单API定义基于时间的任务，自动运行。

## JSON处理库
- [GJSON](https://github.com/tidwall/gjson) - 通过一行代码从JSON中获取值。
- [go-json](https://github.com/goccy/go-json) - 高性能的JSON处理库，替代标准库。

## 日志处理库
- [logrus](https://github.com/sirupsen/logrus) - 结构化日志库，支持多种格式和输出方式。
- [zap](https://github.com/uber-go/zap) - 高性能的结构化日志库。
- [zerolog](https://github.com/rs/zerolog) - 零内存分配的JSON日志库。

## 机器学习库
- [gorgonia](https://github.com/gorgonia/gorgonia) - 类似于Theano的图计算库，支持构建机器学习算法。
- [gorse](https://github.com/zhenghaoz/gorse) - 基于协同过滤的推荐系统。

## HTTP客户端库
- [resty](https://github.com/go-resty/resty) - 简洁易用的HTTP和REST客户端。
- [grequests](https://github.com/levigross/grequests) - 类似于Python Requests的HTTP客户端。

## ORM库
- [GORM](https://github.com/go-gorm/gorm) - 功能强大的ORM库，适合开发者使用。
- [ent](https://github.com/facebook/ent) - 实体框架，简洁强大的ORM解决方案。
- [bun](https://github.com/uptrace/bun) - SQL优先的ORM库，支持PostgreSQL、MySQL等。

## 项目结构模板
- [golang-standards/project-layout](https://github.com/golang-standards/project-layout) - Go语言项目的常见结构模板，适合新项目参考。
- [modern-go-application](https://github.com/sagikazarmark/modern-go-application) - 应用现代开发实践的Go项目模板。

## 字符串处理库
- [gobeam/Stringy](https://github.com/gobeam/Stringy) - 支持字符串的驼峰、蛇形、短横线转换等操作。
- [strutil](https://github.com/ozgio/strutil) - 字符串工具库。
- [xstrings](https://github.com/huandu/xstrings) - 提供其他语言中的常用字符串操作方法。

## 语言检测和处理
- [whatlanggo](https://github.com/abadojack/whatlanggo) - 支持84种语言的自然语言检测包。
- [go-stem](https://github.com/agonopol/go-stem) - 词干提取库，支持Porter算法。

## 网络库
- [fasthttp](https://github.com/valyala/fasthttp) - 高性能HTTP库，速度比标准库快。
- [gopacket](https://github.com/google/gopacket) - 数据包处理库，适合网络分析。
- [quic-go](https://github.com/lucas-clemente/quic-go) - QUIC协议的纯Go实现。

## OpenGL开发库
- [gl](https://github.com/go-gl/gl) - OpenGL的Go绑定。
- [glfw](https://github.com/go-gl/glfw) - GLFW 3的Go绑定，用于创建OpenGL上下文和处理事件。

## 常用依赖注入库
- [wire](https://github.com/google/wire) - 自动初始化工具。
- [dig](https://github.com/uber-go/dig) - 基于反射的依赖注入工具包。
- [fx](https://github.com/uber-go/fx) - 基于依赖注入的应用程序框架。

## 模板引擎

_常用的Go语言模板引擎库。_

- [goview](https://github.com/foolin/goview) - 基于 Go 的轻量级、简洁的模板库，适用于构建 Go Web 应用程序。
- [pongo2](https://github.com/flosch/pongo2) - 类似 Django 的模板引擎，功能强大且易于使用。
- [jet](https://github.com/CloudyKit/jet) - 强大的模板引擎，提供良好的性能和模板继承支持。
- [quicktemplate](https://github.com/valyala/quicktemplate) - 高效的模板引擎，将模板转换为 Go 代码后编译。
  
## 测试

_用于测试代码库和生成测试数据的常用工具库。_

### 测试框架

- [Testify](https://github.com/stretchr/testify) - 常用的 Go 测试扩展库，提供断言和 mock 支持。
- [GoConvey](https://github.com/smartystreets/goconvey/) - BDD 风格测试框架，带有 Web UI 和实时刷新功能。
- [ginkgo](https://onsi.github.io/ginkgo/) - 适用于 Go 的 BDD 测试框架。

### Mock 工具

- [gomock](https://github.com/golang/mock) - Go 语言的常用 mock 框架，用于生成模拟接口的对象。
- [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL 驱动程序，用于测试数据库交互。

### Fuzz 测试

- [go-fuzz](https://github.com/dvyukov/go-fuzz) - 随机化测试工具，用于找出边界条件和潜在问题。
  
### Selenium 和浏览器控制工具

- [chromedp](https://github.com/knq/chromedp) - Chrome Debugging Protocol 的 Go 绑定，用于控制浏览器进行自动化测试。

## 文本处理

_用于解析和操作文本的常用库。_

### 格式化工具

- [go-humanize](https://github.com/dustin/go-humanize) - 将时间、数字和内存大小格式化为可读形式。
- [gotabulate](https://github.com/bndr/gotabulate) - 方便地将表格数据美观地打印出来。

### 标记语言

- [goldmark](https://github.com/yuin/goldmark) - 现代的 Markdown 解析器，符合 CommonMark 标准，易于扩展。
- [html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) - 将 HTML 转换为 Markdown 的工具。

### 爬虫工具

- [colly](https://github.com/asciimoo/colly) - 高效的爬虫框架，用于从网站抓取结构化数据。
- [GoQuery](https://github.com/PuerkitoBio/goquery) - 提供类似 jQuery 的 API，以便轻松地解析和操作 HTML 文档。

## 第三方 API

_用于访问各种第三方服务 API 的库。_

- [aws-sdk-go](https://github.com/aws/aws-sdk-go-v2) - 官方 AWS SDK for Go，支持访问 AWS 的所有服务。
- [discordgo](https://github.com/bwmarrin/discordgo) - 适用于 Discord 聊天 API 的 Go 绑定。
- [go-openai](https://github.com/sashabaranov/go-openai) - OpenAI 的 ChatGPT、DALL·E、Whisper API 库。
- [slack](https://github.com/slack-go/slack) - Slack API 的 Go 客户端。
- [github](https://github.com/google/go-github) - 访问 GitHub REST API v3 的 Go 库。
- [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud API 的 Go 客户端库。 

以下是简化后的常用工具、库和框架列表，更加贴近中国用户的需求，去掉了小众和过时内容，并以Markdown格式展示：

## 常用工具

_使开发更高效的通用工具和库。_

- [clipboard](https://github.com/golang-design/clipboard) - 跨平台剪贴板工具包。
- [cvt](https://github.com/shockerli/cvt) - 安全、方便地将任意值转换为其他类型。
- [delve](https://github.com/go-delve/delve) - Go语言调试器。
- [dive](https://github.com/wagoodman/dive) - 用于探索Docker镜像中每一层的工具。
- [fzf](https://github.com/junegunn/fzf) - Go编写的命令行模糊查找工具。
- [goreleaser](https://github.com/goreleaser/goreleaser) - 快速生成Go二进制文件发布工具。
- [gotenv](https://github.com/subosito/gotenv) - 从 `.env` 文件中加载环境变量。
- [lo](https://github.com/samber/lo) - 类似 Lodash 的 Go 语言工具库，基于 Go 1.18+ 泛型实现。
- [sqlx](https://github.com/jmoiron/sqlx) - 为标准 `database/sql` 包增加了扩展功能。

## UUID 生成库

_用于生成唯一标识符的库。_

- [nanoid](https://github.com/aidarkhanov/nanoid) - 高效且轻量级的Go唯一字符串ID生成器。
- [ulid](https://github.com/oklog/ulid) - Go实现的ULID（通用唯一可排序标识符）。
- [uuid](https://github.com/google/uuid) - 基于RFC 4122的Go UUID库。

## 验证库

_数据验证库。_

- [govalidator](https://github.com/asaskevich/govalidator) - 字符串、数值、切片和结构体的验证和过滤器。
- [validator](https://github.com/go-playground/validator) - Go结构体和字段验证，支持交叉字段、交叉结构体、Map、Slice和数组。

## Web 框架

_全栈Web框架。_

- [Beego](https://github.com/beego/beego) - 高性能的开源Go Web框架。
- [Echo](https://github.com/labstack/echo) - 高性能、简洁的Go Web框架。
- [Fiber](https://github.com/gofiber/fiber) - 类似Express.js的Web框架，基于 `fasthttp` 实现。
- [Gin](https://github.com/gin-gonic/gin) - 高性能、简洁的Go Web框架。
- [Goravel](https://github.com/goravel/goravel) - 受Laravel启发的Go Web框架，内置ORM、认证、队列等功能。

### 中间件

- [CORS](https://github.com/rs/cors) - 轻松为API添加CORS支持。
- [Tollbooth](https://github.com/didip/tollbooth) - HTTP请求速率限制中间件。
- [Limiter](https://github.com/ulule/limiter) - 简单的速率限制中间件。

### 路由库

- [chi](https://github.com/go-chi/chi) - 小巧、快速且表现力丰富的HTTP路由库。
- [httprouter](https://github.com/julienschmidt/httprouter) - 高性能HTTP路由库。
- [mux](https://github.com/gorilla/mux) - 功能强大的URL路由和调度器。

## 代码分析工具

_源代码分析工具。_

- [golangci-lint](https://github.com/golangci/golangci-lint) - 快速的Go静态分析工具，支持多种linters。
- [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - 类似`go vet`的静态分析工具，包含多种检查。

## Go工具

_提高开发效率的Go语言相关工具。_

- [go-callvis](https://github.com/TrueFurby/go-callvis) - 使用dot格式可视化Go程序的调用图。
- [go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0的Go实现，用于自动化生成REST API文档。
- [richgo](https://github.com/kyoh86/richgo) - 美化 `go test` 输出结果。
- [gotestdox](https://github.com/bitfield/gotestdox) - 将Go测试结果展示为可读的句子。


## 软件包

_Go编写的软件。_

### DevOps 工具

- [Docker](https://www.docker.com/) - 为开发人员和系统管理员提供的分布式应用程序开源平台。
- [Flannel](https://github.com/flannel-io/flannel) - Kubernetes 容器网络工具。
- [Gitea](https://github.com/go-gitea/gitea) - Gogs的社区分支，轻量级的Git服务。
- [Hey](https://github.com/rakyll/hey) - 一个小型的程序，用于向Web应用程序发送负载。
- [k3s](https://github.com/k3s-io/k3s) - 轻量级Kubernetes。
- [k6](https://github.com/grafana/k6) - 现代化的负载测试工具，使用Go和JavaScript编写。
- [minikube](https://github.com/kubernetes/minikube) - 在本地运行Kubernetes。
- [Traefik](https://github.com/containous/traefik) - 反向代理和负载均衡器，支持多种后端。

### 其他软件

- [croc](https://github.com/schollz/croc) - 在计算机之间安全、轻松地发送文件或文件夹。
- [hugo](https://gohugo.io/) - 快速现代的静态网站引擎。
- [restic](https://github.com/restic/restic) - 去重备份程序。
- [syncthing](https://syncthing.net/) - 开源的分布式文件同步工具。

## 资源

### E-Books

#### 免费电子书

- [Go 101](https://go101.org) - 一本聚焦Go语言语法和语义的书籍。
- [Build Web Application with Golang](https://astaxie.gitbooks.io/build-web-application-with-golang/content/en/) - 使用Golang构建Web应用的教程。
- [The Go Programming Language](https://www.gopl.io/) - Go语言编程书籍。

## 社区资源

### Reddit

- [r/golang](https://www.reddit.com/r/golang/) - Go语言的新闻和讨论社区。

### 网站

- [Go Blog](https://blog.golang.org) - 官方Go博客。
- [Go Projects](https://github.com/golang/go/wiki/Projects) - Go社区项目列表。
- [pkg.go.dev](https://pkg.go.dev/) - 开源Go包的文档。

### 指南

- [Uber Go 语言编码指南](https://github.com/uber-go/guide/blob/master/style.md) - Uber的Go语言编码风格指南。

