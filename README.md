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
- 
#### ✨ **核心功能**  
1. **解除交互限制**：  
   - 恢复右键菜单、文本选择、复制/剪切功能，突破网页“禁止操作”限制。  
   - 支持绕过代码级（事件拦截）和CSS级（`user-select: none`）的限制。  

2. **灵活排除列表**：  
   - 🔒 **基础保护**：内置常用站点（YouTube、维基百科等），避免误解除重要功能。  
   - ✍️ **自定义排除**：在弹窗中输入域名（每行一个），保存后脚本不再对该网站生效（如 `baidu.com`、`blog.example.com`）。  


#### 🌐 **生效范围 & 例外**  
- **默认生效**：  
  📍 所有网站（通过 `@match *://*/*` 匹配），包括：  
  - 在线文档平台（百度文库、道客巴巴）  
  - 新闻资讯站（禁止复制的文章页）  
  - 技术博客/论坛（限制选择的代码块）  
  - 教育资源网（付费内容页）  
  - 商品详情页（禁止复制价格/描述）  

- **黑名单例外（不生效）**：  
  🚫 `youtube.com`、`wikipedia.org`、`mail.qq.com`、`translate.google.com`（保护敏感站点正常使用）。  


#### 🚀 **典型应用场景**  
- 📄 **复制付费文档**：突破“仅限会员复制”限制，直接选中内容。  
- 🖼️ **右键保存图片**：解除“禁止右键”网站的图片另存为限制。  
- ✂️ **自由剪贴内容**：在禁止剪贴的在线编辑器中恢复复制粘贴功能。  
- 📝 **提取网页文本**：快速选中并复制学术论文、新闻报道等内容。  
#### 💡 **使用方法**  
1. **排除列表设置**：  
   - 打开弹窗（浏览器右上角油猴图标 → 脚本 → 点击“当前状态”），在文本框输入域名（如 `example.com`），点击保存后刷新页面生效。  
2. **内置黑名单建议**：  
   - 保留 `mail.qq.com` 等邮箱域名，避免影响登录/写信功能；删除需谨慎，误删可能导致部分网站异常。  
3. **域名格式**：  
   - 直接输入域名（如 `blog.example.com`），无需添加 `http://` 或 `www.`。 
