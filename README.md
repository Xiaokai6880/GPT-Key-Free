# GPT-Key-Free
GPT-Key-Free，免费ChatGPT API，支持GPT4 API（免费），ChatGPT国内可用免费转发API，直连无需代理。
可以搭配ChatBox等软件/插件使用，极大降低接口使用成本。国内即可无限制畅快聊天。

## 特点
1. 支持 **GPT-4全系列** / Claude3全系列 / Gemini全系列 / 微软Bing全系列 / Suno-v3 /DALL·E / whisper / TTs全系列
2. 与官方完全一致的接口标准，兼容各种软件/插件。
3. 国内动态加速 直连无需代理
4. 支持流式响应。
5. 无需科学上网，国内环境直接可用。

## 领取API-Key
1. 关注微信公众号：SmallAI
2. 回复“抽奖”立即获取领取链接
3. 填入Key至SmallAI或第三方平台
4. 代理地址：https://ai98.vip 或 https://ai98.vip/v1

## 付费APIKey
1. 立即购买[SmallAI-Key](https://faka.smallai.chat)
2. 有无限制使用版本，极大的减少了使用成本！
3. 专属24小时客服支持！
4. 高速VIP通道支持！
5. 未来永远保持更新！
6. 无需科学上网，国内环境直接可用。
客服微信：GangHouse_
## 常见软件/插件使用方法

### **python openai官方库（使用AutoGPT，langchain等）**
示例代码请参考[OpenAI官方文档](https://platform.openai.com/docs/guides/text-generation)

***方法一（推荐）***

直接使用[SmallAI](https://www.smallai.chat)
设置-语言模型-SmallAIKey-填入你的Key


### **开源gpt_academic**
找到`config.py`文件中的`API_URL_REDIRECT`配置并修改为以下内容：
```python
API_URL_REDIRECT = {"https://api.openai.com/v1/chat/completions": "https://api.chatanywhere.tech/v1/chat/completions"}
# API_URL_REDIRECT = {"https://api.openai.com/v1/chat/completions": "https://api.chatanywhere.cn/v1/chat/completions"}
```
### **BotGem(AMA)**

ChatGPT桌面应用，支持全平台，***支持gpt-4-vision***。

下载链接：https://bytemyth.com/ama

使用方法：下载安装后在设置中如图设置，并点击更新。

![](images/botgem.png)

### **ChatBox**

ChatGPT开源桌面应用，支持全部桌面平台。

下载链接：https://github.com/Bin-Huang/chatbox/releases

使用方法：如图在设置中填入购买的密钥，并将代理设置为`https://api.chatanywhere.tech`即可

![](images/chatbox.png)

### **Zotero插件**

**pdf阅读插件zotero-gpt**

下载链接：https://github.com/MuiseDestiny/zotero-gpt/releases

安装好插件后使用以下命令设置，还是不会可以去b站搜教程。
```
/api https://api.chatanywhere.tech

/secretKey 购买的转发key 记住别忘记带sk-

# 切换模型命令
/model gpt-3.5-turbo-0125 
```

![](images/zotero-gpt.png)


**翻译插件zotero-pdf-translate**

下载链接：https://github.com/windingwind/zotero-pdf-translate/releases

接口地址填写: https://api.chatanywhere.tech/v1/chat/completions

不用管状态是否显示可用 填上之后就可以了

![](images/zotero-pdf-translate.png)


### **浏览器插件ChatGPT Sidebar**

官网链接：https://chatgpt-sidebar.com/

安装好插件后进入设置页面，如图所示修改设置，将url修改为 `https://api.chatanywhere.tech` 。

![](images/sidebar.png)

### **Jetbrains插件ChatGPT - Easycode**
<img src="./images/jet1.png" width='200'/>

安装好插件后在Settings > Tools > OpenAI > GPT 3.5 Turbo中如图所示配置好插件，重点要将Server Settings 修改为 `https://api.chatanywhere.tech/v1/chat/completions` 。并勾选Customize Server。

![](images/jet2.png)


### **Raycast 插件 ChatGPT**

1. 在 Raycast Store 中找到 ChatGPT 插件，并按照提示安装：
![](images/raycast1.png)

2. 安装完成后在该插件配置中的 `API Key` 中填入我们的API Key，以及选中 `Change API Endpoint`，并在 `API Endpoint` 中填入 `https://api.chatanywhere.tech/v1`
![](images/raycast2.png)
![](images/raycast3.png)
