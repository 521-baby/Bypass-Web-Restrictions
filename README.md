### 🛠️ 破除网页限制脚本 | 恢复右键菜单、文本选择、复制/剪切功能，突破网页“禁止操作”限制
### 访客人数：
<img src="https://count.kjchmc.cn/get/@Byass-Web-Restrictions?theme=rule34" alt="如果您无法看到此内容，请刷新页面。">

### 🔗 其他链接 
- 脚本源码：[GitHub 仓库](https://github.com/521-baby/ChaoXing-SuperSrarLearn)    
- 如果有帮助到你<img src='https://github.com/521-baby/Bypass-Web-Restrictions/blob/main/%E7%A0%B4%E9%99%A4%E7%BD%91%E9%A1%B5%E9%99%90%E5%88%B6.js' width='16px' /> 投喂渠道：[⚡爱发电](https://afdian.com/a/chunshu) or [微信赞赏](https://github.com/521-baby/521-baby/blob/main/DONATE.md) or [支付宝](https://github.com/521-baby/521-baby/blob/main/DONATE2.md)</del>
## 🛠️ 安装说明  
### 1. 安装浏览器扩展（二选一）  
#### ▶ 油猴 (Tampermonkey)  
- **官方网站**：[https://www.tampermonkey.net/](https://www.tampermonkey.net/)  
- **各浏览器安装链接**：  
  - Chrome：[点击安装 Tampermonkey for Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)  
  - Firefox：[点击安装 Tampermonkey for Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)  
  - Edge：[点击安装 Tampermonkey for Edge](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)  
  - Safari：[点击安装 Tampermonkey for Safari](https://apps.apple.com/us/app/tampermonkey/id1482490089)  

#### ▶ 脚本猫 (ScriptCat)  
- **官方网站**：[https://scriptcat.org/](https://scriptcat.org/)  
- **各浏览器安装链接**：  
  - Chrome：[点击安装 ScriptCat for Chrome](https://chrome.google.com/webstore/detail/scriptcat/lhplgjmbpnjgjmpbokdjpcbbekifcmli)  
  - Firefox：[点击安装 ScriptCat for Firefox](https://addons.mozilla.org/zh-CN/firefox/addon/scriptcat/)  
  - Edge：[点击安装 ScriptCat for Edge](https://microsoftedge.microsoft.com/addons/detail/scriptcat/llhcdfddnmmcmlbdennkpdnlnbgbmfak)  

### 2. 安装脚本  
- 点击下方链接一键安装：  
  [📥 安装 学习通（刷课+考试）油猴脚本](https://greasyfork.org/zh-CN/scripts/535746-%E7%BD%91%E9%A1%B5%E9%99%90%E5%88%B6%E8%A7%A3%E9%99%A4)
  
  [📥 安装 学习通（刷课+考试）脚本猫脚本](https://scriptcat.org/zh-CN/script-show-page/3403)
- 浏览器会自动跳转至安装页面，点击 **安装** 即可完成


#### 💡 使用方法  
!屏幕截图 2025-05-24 093359.png  
- **排除列表设置**  
  打开弹窗（浏览器右上角油猴图标 → 该脚本 → 点击“📜 当前状态”），在右侧“排除设置”文本框输入域名（如 example.com），点“保存排除列表”，刷新后生效。  
- **站点模式切换**  
  在弹窗右侧“站点设置”选择当前域名的模式（标准/轻量/友好/禁用），点击“保存模式”，刷新后生效。  
- **快速开关当前站点**  
  通过脚本菜单的“当前网站：✔️/❌”一键对本域启用/禁用，刷新后生效。  
- **内置黑名单建议**  
  默认保留 mail.qq.com 等邮箱域名于黑名单，避免影响登录/写信等关键功能；删除请谨慎。  
- **域名格式**  
  直接填写域名（如 blog.example.com），不用加 http:// 或 www.。  

#### ⚙️ 模式说明（可 per-site 配置）  

- **标准模式**：最大化解除限制  
  拦截站点通过事件阻止的限制（如右键、复制、选择）、清理内联 on* 事件、保护 returnValue 被强行设为 false 的行为，并注入 CSS 放开选择。
  
- **轻量模式（默认模式）**：最小侵入、常用场景推荐
  仅在捕获阶段阻断常见拦截事件（右键/复制/剪切/选择/拖拽），不 Hook 原型，不清理内联事件，副作用更小。
   
- **友好模式**：播放器等敏感站点专用  
  不 Hook、不清理，只保留 CSS 放行文本选择，尽量不影响网站原生交互（如视频播放器点击/键盘）。
  
- **禁用**：对当前域名完全不生效  

#### 🔁 默认行为（已内置最佳实践）  
- **全局默认**：轻量模式  
- **常见视频站默认友好模式**（不干扰播放器交互）：  
  bilibili.com、iqiyi.com、youku.com、v.qq.com、video.qq.com、mgtv.com、acfun.cn、sohu.com、tv.sohu.com、pptv.com、le.com、tudou.com、youtube.com  
- **黑名单例外（默认不生效）**：  
  youtube.com、wikipedia.org、mail.qq.com、translate.google.com（可在弹窗中自行调整）  

#### ✨ 核心功能  
- **解除交互限制**  
  恢复右键菜单、文本选择、复制/剪切功能，绕过代码级（事件拦截）与 CSS 级（user-select: none）限制。  
- **站点模式与可视化状态**  
  弹窗“当前状态”会显示“已处理事件”（中文）与“实现的功能”，不同模式下呈现不同的处理范围，便于诊断副作用。  
- **更稳健的实现**  
  采用 MutationObserver 增量清理新插入节点的内联事件，性能优于轮询。  
  使用更安全的 Object.defineProperty 方式保护 returnValue，兼顾兼容性与稳定性。  

#### 🌐 生效范围 & 例外  
- **默认生效范围**：所有站点（@match *://*/*）  
- **典型应用**：  
  - 在线文档（百度文库、道客巴巴）  
  - 禁止复制的新闻/博客/论坛页面  
  - 教育/学习资料页面  
  - 商品详情页禁止复制价格/描述等  
- **例外与友好模式**：  
  - 黑名单：默认不生效（可自行移除）  
  - 视频站：默认友好模式，避免影响播放器点击暂停/播放、进度条等  

#### 🚀 典型应用场景  
- 复制付费或限制复制的文档内容  
- 解除图片右键保存限制  
- 在限制剪贴的在线编辑器中自由复制/剪切  
- 快速选中并复制文章、论文、新闻内容  

#### 🧭 使用建议  
若遇副作用（如快捷键异常、页面交互被影响）：  
- 优先将站点切换为“轻量模式”或“友好模式”  
- 个别站点直接“禁用”或加入“排除列表”  
- 强制刷新（Ctrl+F5）或关闭旧标签重开页面  
- 暂时关闭可能冲突的脚本/扩展（手势、广告拦截、播放器增强等）  

#### 🔒 隐私与说明  
- 仅解除前端交互限制，不绕过服务器权限/付费墙，不进行内容破解或 OCR 识别。  
- 所有站点配置（模式、排除列表）仅保存在本地浏览器中。  

#### ✅ 已解决的已知问题  
- **B站点击暂停变为“跳进度”的问题**：  
  现已在所有模式下避免干扰播放器点击行为；B站默认“友好模式”，确保暂停/播放、拖动进度等操作正常。  

#### 📥 立即安装  
在浏览器安装油猴（Tampermonkey）后，添加本脚本即可自动生效。
