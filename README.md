# Auto Reply Bot

An automatically replying messages bot using MITSUKU intelligent.
## Getting Started

This is simply a bot that automatically replies to messages, go along with interesting commands!

### Prerequisites

You need to install the following software to use this.
* [NodeJs](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)

### Installing
Open CLI, type these words:<br>
```
npm run setup
```
```
npm install
```

### Updating
Open CLI, type these words:
```
npm run update
```

## Deployment
* Step 1: <br>
There are two ways of this:<br>
1: <b>If you want to logged in by your email and password</b> then type your email and password in ./credentials/credential.json<br>
2: <b>If you want to logged in by cookies</b> then i would like you to download [J2TEAM Cookies](https://chrome.google.com/webstore/detail/j2team-cookies/okpidcojinmlaakglciglbpcpajaibco), after that, export 2 cookie files of your "facebook.com" and "messenger.com", rename it into facebook.json and messenger.json then move it in folder ./credentials/ (the tool will automatically detects your files and prefer logging in by your cookies to logging in by your email/passwrd)
* Step 2: Type this in your CLI
```
npm start
```

<br><br>
<hr>
<br><br>

## Phần này chỉ dành cho những người xài web để tạo bot thay vì cái trên (cái trên sẽ không lưu trữ gì hết :/ và web sắp hoàn thành nên mình sẽ update link sau)
### Một số điều lưu ý khi sử dụng web kb2abot
* Khuyến cáo nên sử dụng acc clone để login thay vì sử dụng acc chính tránh bị haccu hack (hi vọng là haccu sẽ báo lỗi thay vì đi hack acc mọi người).
* Khi bị dính checkpoint hay login approval liên tục (không ngừng nghỉ) thì có vẻ như tài khoản của bạn đã bị bảo mật, nên hãy tạo tài khoản mới để sử dụng.
* Chúng tôi chỉ lưu trữ: số lượng tin nhắn, language, weather default, các trạng thái của "status", "emote", trên database ngoài ra không còn gì khác!
* Username, Password của bạn được lưu trữ trực tiếp trên server và được mã hóa Vigenère nên sẽ không bao giờ bị hack!
