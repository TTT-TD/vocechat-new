# vocechat-new
VoceChat|自托管的IM应用|开源且轻量化的即时聊天应用|支持Android/iOS/PWA

> 该仓库来自[https://github.com/Privoce/vocechat-web](https://github.com/Privoce/vocechat-web),进行一些中文补充

Telegram 频道: [@vocechat_channel](https://t.me/vocechat_channel)

Telegram 群组: [@vocechat_group](https://t.me/vocechat_group)

TG频道以及群组刚刚创建，有感兴趣的小伙伴可以群内交流

## 关于Pro版本授权的一些说明

VoceChat提供免费的社区版和Pro版本，Pro版本目前特性如下：
- 没有用户数限制 (社区版限制20人)
- Pro版本已经去除了非管理员登录的版权信息
- 没有Bot/Webhook限制

## 关于Pro版本价格

- 官网https://voce.chat 有价格标注，为买断制$49/server
- TG群内购买可享优惠价为￥235或$30
- 通过TG获取Pro版本均为正式授权，并非破解版，使用官方方式安装正常授权正常更新

## 近期改动计划

- Agora音视频支持(进行中)
- Bark/Pushdeer推送接入(进行中，目前使用Google FCM)
- 对接CN国内推送(友盟Upush，计划中...)


---

# Web Client of VoceChat

<center>
  <img src="https://github.com/Privoce/vocechat-web/raw/main/public/android-chrome-192x192.png" width="100" height="100">
</center>
<p>
<center>

[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/privoce/vocechat-web/issues)
![GitHub issues](https://img.shields.io/github/issues-raw/Privoce/vocechat-web) ![GitHub](https://img.shields.io/github/license/privoce/vocechat-web) ![GitHub top language](https://img.shields.io/github/languages/top/privoce/vocechat-web) ![Docker Pulls](https://img.shields.io/docker/pulls/privoce/vocechat-server)

</center>

- 🎉 Powered by React & Redux Toolkit
- ✅ Typescript
- 📦 PWA
- 📢 Notification

## Host your server! Or use our test server

- Host your own Voce server ([docker image](https://hub.docker.com/r/privoce/vocechat-server/tags)):
  Run on x86_64 platform:

```bash
docker run -d --restart=always \
  -p 3000:3000 \
  --name vocechat-server \
  privoce/vocechat-server:latest
```

For more server hosting instructions, see our documentation: https://doc.voce.chat/

## Preview

- official site: https://voce.chat
- live demo: https://privoce.voce.chat/
- demo API Docs (Swagger): https://dev.voce.chat/api/swagger

- design: https://www.figma.com/file/EHnNr53kNmDWgUT86It6CH/UI
- text editor: https://plate.udecode.io/docs/installation
- markdown editor: https://nhn.github.io/tui.editor/latest/
- redux: [@reduxjs/toolkit](https://redux-toolkit.js.org/introduction/getting-started)
- indexDB wrapper: https://github.com/localForage/localForage

## Local Development

- `git clone https://github.com/Privoce/vocechat-web vocechat-web`

- `cd vocechat-web & yarn install`

- `yarn start`

- Open `localhost:3009`

### Tools Recommended

- [VS Code](https://code.visualstudio.com/) Editor Recommended
- VS Code plugins:
  - [dbaeumer.vscode-eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): ESLint
  - [esbenp.prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode): Prettier
  - [dsznajder.es7-react-js-snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets): Extensions for React, React-Native and Redux in JS/TS with ES7+ syntax

## License

[GPL v3](https://github.com/Privoce/vocechat-web/blob/main/LICENSE)

## Thanks all the contributors

<a href="https://github.com/privoce/vocechat-web/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=privoce/vocechat-web" />
</a>

Discuss collaboration: han@privoce.com or https://bridger.chat/han
  
Telegram Group: https://t.me/vocechat_group 
