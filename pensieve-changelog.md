----
- Name: bearychat
- Platform: web

----
# 20170207/ 2017-02-07
## Added
- 自定义贴纸功能
- OSChina 机器人支持标签事件
## Fixed
- 修改了消息流中的图片大小
- 修复了英文版若干翻译
- 修复了 travis 机器人不支持分支构建结果的问题
- 修复其他 Bug 若干

# 20170118/ 2017-01-18
## Added
- 新版首页上线
- 临时讨论组功能
## Fixed
- 恢复了石墨文档集成

# 20170112/ 2017-01-12
## Added
- gogs 机器人新增 pull requests 相关事件支持
- worktile 机器人新增任务相关事件支持
## Fixed
- 下架了 GitCafe 机器人, farewell peter

# 20170110/ 2017-01-10
## Added
- 增加 coveralls 及 zabbix 机器人

# 20161227/ 2016-12-27
## Added
- 新版 BearyChat 上线：为您带来全新的用户界面和全新的交互

# 20160823/ 2016-08-23
## Added
- 增加高级版月付和年付的快速切换
- 优化代码块的显示样式
- 优化团队信息页面的交互

# 20160818/ 2016-08-18
## Added
- 增加团队图标设置功能

# 20160816/ 2016-08-16
## Added
- 增加勿扰模式

# 20160804/ 2016-08-04
## Added
- 增加对 Dropbox 文件分享的支持
- 支持永久有效的邀请链接
## Fixed
- 修复补全时无法使用左右键的问题

# 20160728/ 2016-07-28
## Added
- 增加更详细的付费提醒设置
- 使用新的 CDN 域名加速静态文件加载

# 20160714/ 2016-07-14
## Added
- 增加发票列表显示
- 增加文件私密标记
## Fixed
- 修复文件上次计数错误

# 20160708/ 2016-07-08
## Added
- 更新用户资料设计
- 增加定时提醒命令
- 增加用户名/全名的默认显示设置

# 20160630/ 2016-06-30
## Fixed
- 修复头像上次弹出两次文件选择问题
- 修复可搜索下拉器的交互问题
- 修复消息内链接特殊字符转义问题

# 20160627/ 2016-06-27
## Added
- 更新个人信息修改设计
- 首页增加团队选择器
- 价格页面支持直接为所在团队升级
- 增加消息编辑删除的权限控制
- 团队可以选择是否优先显示全名
- HUBOT 机器人支持 Attachments 参数
## Fixed
- 修复无法在 @ 时使用拼音补全的问题

# 20160614/ 2016-06-14
## Added
- 增加 BearyChat 高级版
- 增加数据统计功能（高级版专享）
- 增加表情回应
- 引用消息支持上下文跳转

# 20160605/ 2016-06-05
## Added
- 增加充值功能
- 更新 GitHub 机器人事件
- 更新文件预览弹窗设计
- 增加 <a href="/integrations/prometheus">Prometheus 机器人</a>
- 增加 <a href="/integrations/zentaopms">禅道机器人</a>
## Fixed
- 修复成员更改名拼音补全问题
- 修复文件评论导致未读标记出错

# 20160511/ 2016-05-11
## Added
- 增加消息发送失败时重发功能
- 增加 Protalk 机器人
- 增加 阿里云Code 机器人
- 增加 GreenhouseCI 机器人

# 20160330/ 2016-03-30
## Added
- 修改公告显示逻辑
- 更新 GitHub OAuth scope(需要重新授权)
## Fixed
- 修复托拽上传文件夹报错
- 修复全名换行，侧栏宽度压缩等样式问题

# 20160323/ 2016-03-23
## Added
- 增加 Hubot 机器人
- 支持文件评论

# 20160302/ 2016-03-02
## Added
- 发布贴纸消息可以先预览
- 增加石墨文档分享

# 20160224/ 2016-02-24
## Added
- 可以发布贴纸消息
- 增加权限管理功能
## Fixed
- 修复同时修改多条消息的问题
- 修复 @ 补全列表顺序问题

# 20160203/ 2016-02-03
## Added
- 增加公告版功能
- 升级 BearyChat Jenkins 插件

# 20160201/ 2016-02-01
## Added
- 管理面板采用响应式设计
- 机器人 Hook 地址采用新的复制控件
- 增加 WordPress 机器人
- Teambition 机器人支持评论事件
- 增加 Bugsnag 机器人
- 增加 OneAPM Cloud Insight 机器人
## Fixed
- 修复 .ico .webp 文件的显示问题
- 修复私人聊天时在线状态显示不准问题

# 20160113/ 2016-01-13
## Added
- 管理面板增加主题设计
- 增加忽略未读消息快捷键

# 20160106/ 2016-01-06
## Added
- RSS 机器人关键词过滤器支持「与」逻辑
- 优化邮件内容展示
- GitLab CI 机器人支持到最新版本

# 20151231/ 2015-12-31
## Added
- 增加团队 Emoji 定制功能

# 20151227/ 2015-12-27
## Added
- RSS 机器人增加预抓取功能
## Fixed
- 修复标签输入框在有空间时仍提前换行的问题

# 20151217/ 2015-12-17
## Added
- 增加了 Appear.in 视频会议支持
## Fixed
- 修复视频预览大小没有自适应的问题
- 修复搜索只有过滤器没有关键词需要两次回车提交的问题
- 修复收藏翻页不准确的问题

# 20151207/ 2015-12-07
## Added
- 支持搜索机器人消息
- 多种文件在浏览器端支持使用 PDF 预览
- 增加 Phabricator 机器人
## Fixed
- 修复讨论组成员数据不一致问题
- 修复编辑消息后链接消失问题

# 20151125/ 2015-11-25
## Added
- 增加「提到我的消息」面板
- 桌面客户端支持鼠标右键复制粘贴
- 点击机器人头像显示详情
- Mac 版客户端增加截图按钮
- 讨论组导航增加讨论组人数显示
## Fixed
- 修复查看讨论组和讨论组提醒设置样式错误
- 修复复制多条消息里混入其他内容的问题

# 20151117/ 2015-11-17
## Added
- 图片视频预览可以支持左右切换
- 更新帮助面板内容
## Fixed
- 修复混排模式下的搜索位置不固定的问题
- 修复上传图片进度条出现两次的问题
- 修复「正在输入……」消除不掉问题

# 20151110/ 2015-11-10
## Added
- 左侧栏增加混排模式
- 可以切换英文界面
- 切换英文界面
- 增加 iOS 9 的 Emoji
- 预览未加入讨论组

# 20151104/ 2015-11-04
## Added
- 增加 为知笔记 机器人
- 增加 Heroku 机器人
- 增加 HockeyApp 机器人

# 20151028/ 2015-10-28
## Fixed
- 修复切换主题影响用户全局提醒设置的问题

# 20151027/ 2015-10-27
## Added
- 增加 Logentries 机器人
- 增加 Rundeck 机器人
- 增加 Zendesk 机器人
- 机器人可以查看请求/响应历史
- 微博机器人和 AppReview 机器人设置抓取频率设置
## Fixed
- 修复粘贴后 Snippet 发送不成功问题
- 修复多次 @group 解析错误

# 20151019/ 2015-10-19
## Added
- 增加 BugHD 机器人
- 增加 Confluence 机器人
- 增加 NewRelic 机器人
- 增加 Mailgun 机器人
- 增加 CircleCI 机器人

# 20151012/ 2015-10-12
## Added
- 讨论组增加快速设置提醒规则按钮
- 机器人消息支持 @ 用户
## Fixed
- 修复命令模式补全后带有空格影响匹配的问题

# 20150924/ 2015-09-24
## Added
- 收藏列表增加撤销操作功能
- 增加屏蔽机器人消息提醒的功能
- 工具栏里讨论组图标区分私密和公开
## Fixed
- 修复 GBK 文本预览乱码的问题
- 修复消息里的英文单词折行问题

# 20150916/ 2015-09-16
## Added
- 增加新用户引导流程
- 增加麦客机器人
## Fixed
- 修复切换讨论组命令模式依然保留的问题

# 20150914/ 2015-09-14
## Added
- @ 补全默认显示补全历史
- 管理员可以删除机器人消息
- 增加监控宝机器人
## Fixed
- 修复七牛大文件上传失败的 BUG
- 修复 Excel 文件图标显示问题

# 20150907/ 2015-09-07
## Added
- 增加最后一个讨论组成员不能退出的策略(但可以归档讨论组)
- 增加通过邮箱找回团队域名的入口

# 20150826/ 2015-08-26
## Added
- 增加快速切换功能
## Fixed
- 修复聊天页面连接不稳定问题

# 20150819/ 2015-08-19
## Fixed
- 修复 GitHub 机器人设置 Repos 翻页问题

# 20150817/ 2015-08-17
## Added
- Bitbucket 机器人使用新版 API
- Bitbucket 使用 OAuth2.0 授权
## Fixed
- 修复搜索结果无法收藏的问题

# 20150812/ 2015-08-12
## Added
- 聊天界面更新设计
- 增加多主题切换功能
- 申请加入列表更新设计
## Fixed
- 修复置顶讨论组导致收藏列表不完整问题

# 20150810/ 2015-08-10
## Added
- 链接抓取摘要可以删除了
- 增加 Fabric(Crashlytics) 机器人
- 更新消息操作设计
- Snippet 页面设计更新
- 对不兼容环境提供默认页面

# 20150803/ 2015-08-03
## Added
- 增加消息引用功能
- 增加 SendCloud 机器人
- 增加 Gitlab CI 机器人
## Fixed
- 修复 Favicon 消失的问题

# 20150727/ 2015-07-27
## Added
- 使用 Electron 的新版桌面客户端，支持增量更新
- 增加 Teambition 机器人
- 增加自动更新最新代码机制
- 更新侧栏提醒的内容和设计
## Fixed
- 修复上传文件有可能 Token 过期的问题
- 修复客户端图标闪耀问题

# 20150715/ 2015-07-15
## Added
- 修改密码功能
- 增加 VSO 机器人
## Fixed
- 修复断线后可能丢失历史消息的问题

# 20150701/ 2015-07-01
## Added
- 第三栏的消息可以支持跳转到原上下文
- 支持视频文件的弹窗播放
- 增加 TravisCI 机器人
## Fixed
- 修复搜索无关键词时文件显示错误

# 20150629/ 2015-06-29
## Added
- 增加 AppReview 机器人
## Fixed
- 修复删除文件后消息内文件没立即消失的问题

# 20150617/ 2015-06-17
## Added
- 增加过滤器和搜索历史
- 个人资料设置更新设计
- 成员管理页面更新设计

# 20150615/ 2015-06-15
## Added
- 更新加入申请管理页面
- 增加 git@OSC 机器人

# 20150603/ 2015-06-03
## Added
- 增加 RSS 机器人

# 20150601/ 2015-06-01
## Added
- 增加搜索功能
- 增加服务器错误的统一显示
## Fixed
- 修复返回聊天界面不清空当前未读的问题

# 20150528/ 2015-05-28
## Added
- 增加访客模式

# 20150520/ 2015-05-20
## Added
- 增加 Email 机器人
- 更新文件和消息在第三栏里的样式
## Fixed
- 修复拉取消息可能拉取多次的问题
- 修复上传引导消失后上传按钮失效的问题

# 20150518/ 2015-05-18
## Added
- 增加修改邮箱功能
- 登录后跳转原始地址

# 20150513/ 2015-05-13
## Added
- 增加消息页面加载动画
- 第三栏反馈面板转变成帮助面板
## Fixed
- 修复文件上传错误没有提示的问题
- 修复断线重连后上传文件失败的问题

# 20150506/ 2015-05-06
## Added
- 增加 GitCafe 集成
- 增加 Stash 集成
## Fixed
- 修复客户端点击通知没有自动切换团队的 BUG

# 20150429/ 2015-04-29
## Added
- 桌面客户端支持多团队
- 桌面客户端增加自动检测升级功能
## Fixed
- 修复机器人向 bearybot 发消息未读提示不准问题

# 20150427/ 2015-04-27
## Added
- 增加新浪微博机器人
- 优化 Trello 机器人消息格式

# 20150420/ 2015-04-20
## Added
- 修复编辑机器人基本信息功能
- 修正消息文本中链接的识别问题

# 20150416/ 2015-04-16
## Added
- 可以将讨论组置顶
## Fixed
- 修复使用多客户端时未读提醒不准确问题

# 20150408/ 2015-04-08
## Added
- 可以分享 Evernote 里的笔记了
- 可以把机器人的发送目标设置为 @bearybot（即只对自己可见）
## Fixed
- 修复私有组没有显示未读 @ 数的问题

# 20150406/ 2015-04-06
## Added
- 消息正文里的图片支持点击预览
- 断线重连机制更新
- 支持 Coding 更多的事件
- 支持多客户端已读标记同步
## Fixed
- 修复消息删除后未读提醒仍存在的问题

# 20150326/ 2015-03-26
## Added
- 新的文件样式
- 支持邮箱或用户名登录
- 表单工具<a href="https://jinshuju.net/" target="_blank">金数据</a>集成
- GitHub Trello Bitbucket 机器人表单优化
## Fixed
- 修复消息删除后未读提醒仍存在的问题
- 修复消息删除后未读标志还保留的问题
- 修复消息内图片变形问题
- 修复“所有人”讨论组成员也显示移出按钮问题

# 20150317/ 2015-03-17
## Added
- 新的消息文件样式
- 全站 HTTPS 支持
- 新的成员邀请流程
- 机器人设置优化
## Fixed
- 修复第三栏文件列表同步问题
- 修复消息里预览图变形问题

# 20150305/ 2015-03-05
## Added
- 增加小助手，发布 BearyChat 新鲜事
- 增加第三方服务投票
- 增加 Outgoing 机器人，将消息发到外部服务并获得返回结果
- 上传头像支持剪裁
- 加入团队页面新设计
## Fixed
- 修复在线状态不准确问题
- 修复文本片段不显示预览问题

# 20150211/ 2015-02-11
## Added
- 第三栏增加文件列表
- 增加 <a href="http://worktile.com">Worktile</a> 机器人
- 更新机器人列表页设计
## Fixed
- 修复上传文件的报错

# 20150203/ 2015-02-03
## Added
- 收藏可以显示消息附件
- 分享收藏文件到其他地方
- 新建讨论组去掉描述，增加邀请
## Fixed
- 修复 Markdown 的 bug

# 20150130/ 2015-01-30
## Added
- 消息和文件的加星标收藏功能
- 将用户反馈和快捷键列表移至第三栏
- 新的登录界面和用户引导样式
- 支持 Markdown 标准语法
## Fixed
- 修复图片预览显示上的 BUG 和滚动问题

# 20150110/ 2015-01-10
## Added
- 图片预览界面上的优化
- 联系人列表离线和在线分开排序
- Snippet 代码高亮优化
- 光标不在输入框时，「?」调出快捷键提示
- 性能优化
## Fixed
- Markdown 模块 BUG 修复

# 20141230/ 2014-12-30
## Added
- 代码 Snippet 有了默认名称，展示样式也有了改进
- Emoji 增加自动补全
- 现在可以用 # 讨论组名称来 Mention 讨论组了
- 讨论组归档增加了二次确认，避免误操作
- 邮件模板优化
- 消息提醒设置界面优化
