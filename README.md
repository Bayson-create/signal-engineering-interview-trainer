# Signal / 工程面试训练器

一个证据驱动的现代软件工程面试学习网站首版。

## 设计原则

- 以公司官方招聘页面为一手来源；对岗位/团队范围有限的案例明确标注。
- 练习题与来源绑定；基础知识用随机选择题，编程能力用浏览器内 JavaScript 测试验证。
- 进度和 DeepSeek API Key 只保存在浏览器本机 localStorage，不写入源码或仓库；AI 实验直接调用 DeepSeek Chat Completions，适合个人本机练习。
- 本地运行：直接打开 `index.html`，或使用任意静态文件服务器。

## 当前内容

覆盖算法与 OA、系统设计、项目与行为、调试、代码审查、结对编程、take-home、真实代码库和 AI 辅助工程九类信号；包含 Amazon、Microsoft、Wise、OpsLevel、Runna、Trail of Bits、Google、Meta 的来源节点。

## 重要限制

浏览器内的代码执行器只用于本地 JavaScript 小题验证，不是安全的多语言云编译器。生产版若要支持 Python/Java/C++，应接入隔离的远程执行沙箱，并增加服务端密钥代理与速率限制。
