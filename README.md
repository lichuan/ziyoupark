# ziyoupark is a truly private 1-to-1 encrypted chat tool
ziyoupark is a truly private 1-to-1 encrypted chat tool. No phone number, no email, no registration required — just open the web page and start chatting. All messages are end-to-end encrypted with AES-GCM, ensuring that no one except the two chatting parties can access the content. ziyoupark is committed to creating a pure chat space free from any surveillance. Official website: https://www.ziyoupark.com

自由公园是一个真正私密的 1对1 加密聊天工具。无需手机号，无需邮箱，无需注册，打开网页即可使用。所有消息均经过 AES-GCM 端到端加密，除了聊天双方，任何人都无法获取聊天内容。致力于打造一个不被任何人监控的纯净聊天空间。官方网站：https://www.ziyoupark.com

## In today's digital world, privacy has become a luxury. ziyoupark is driven by a series of simple yet powerful principles:
- **True End-to-End Encryption:** Using AES-GCM 128-bit encryption, messages are encrypted before sending and can only be decrypted by the recipient holding the correct key
- **Complete Anonymity:** No personal information is collected — no phone, email, or any authentication required
- **No Server Retention:** We only act as a temporary relay for encrypted messages; the server cannot read any content
- **Keys Under Your Control:** Your keys exist only in your browser locally and are never transmitted
- **Clear to Disappear:** Click "Clear Traces" and all chat history and keys are immediately deleted locally

## 在当今的数字世界，隐私已成为奢侈品。自由公园由一系列简单而强大的理念驱动：
- **真正的端到端加密:** 采用 AES-GCM 128位加密，消息在发送前加密，只有持有正确密钥的接收者才能解密
- **完全匿名:** 不收集任何个人信息，无需手机、邮箱或任何身份验证
- **无服务器留存:** 我们仅作为加密消息的临时中转，服务器无法读取任何内容
- **密钥由你掌控:** 你的密钥只存在于你的浏览器本地，永不传输
- **清空即消失:** 点击「清空痕迹」，所有聊天记录和密钥立即从本地删除

## ziyoupark uses a pure frontend encryption architecture. Your keys and chat history are stored only in the browser's LocalStorage. When sending a message:
1. The message is AES-GCM encrypted using the recipient's public key (their key)
2. The encrypted message is sent to the server for relay
3. The server cannot decrypt it and only delivers it to the correct recipient based on hash indexes
4. The recipient decrypts locally using their private key (their own key)
5. The entire process ensures: the server does not store plaintext, does not hold keys, and cannot monitor any conversation.

## 自由公园采用纯前端加密架构，你的密钥和聊天记录仅存储在浏览器的 LocalStorage 中。发送消息时：
1. 使用对方的公钥（即对方密钥）对消息进行 AES-GCM 加密
2. 将加密后的消息发送至服务器中转
3. 服务器无法解密，仅根据哈希索引将消息投递给正确的接收方
4. 接收方使用自己的私钥（即我的密钥）在本地解密
5. 整个过程确保：服务器不存储明文、不掌握密钥、无法监控任何对话。

## How to use
1. Open https://www.ziyoupark.com
2. Copy your "My Key" and securely send it to your friend (via another channel)
3. Paste the key your friend sent you into the "Their Key" field
4. Start sending encrypted messages! Each message will show an AES encryption indicator
5. ⚠️ Important: When exchanging keys for the first time, use another secure channel (in person, encrypted messaging app, etc.) to prevent man-in-the-middle attacks.

## 使用方法
1. 打开 https://www.ziyoupark.com
2. 复制你的「我的密钥」并安全地发送给你的朋友（通过其他渠道）
3. 将朋友发给你的密钥粘贴到「对方密钥」框中
4. 开始发送加密消息！每条消息都会显示 AES 加密标识
5. ⚠️ 重要提示：首次交换密钥时请通过其他安全渠道（如当面、加密通讯软件等）传输，防止中间人攻击。

## ziyoupark will never:
- Collect your personal information
- Store your chat plaintext
- Sell any data
- Insert third-party tracking code
- Display any advertisements

We believe privacy is not a privilege, but a fundamental right.

## 自由公园永远不会：
- 收集你的个人信息
- 存储你的聊天明文
- 出售任何数据
- 插入第三方追踪代码
- 显示任何广告

我们相信，隐私不是特权，而是基本权利。

## ziyoupark is now completely open source! We welcome everyone to review the code, suggest improvements, or contribute. You can participate through:
- GitHub Issues: Report problems or suggest new features
- Pull Requests: Submit code improvements
- QQ Group 933529835: Discuss with other privacy enthusiasts

## 自由公园现已完全开源！我们欢迎所有人审查代码、提出建议或贡献代码。你可以通过以下方式参与：
- GitHub Issues：报告问题或提出新功能
- Pull Requests：提交代码改进
- QQ群 933529835：与其他隐私爱好者交流




