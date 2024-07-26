English | [简体中文](README_zh.md)

<h2 align="center">Flutter Server Box</h2>

<p align="center">
  <img alt="lang" src="https://img.shields.io/badge/lang-dart-pink">
  <img alt="license" src="https://img.shields.io/badge/license-GPLv3-pink">
</p>

<p align="center">
A Flutter project which provide charts to display <a href="../../issues/43">Linux</a> server status and tools to manage server.
<br>
Especially thanks to <a href="https://github.com/TerminalStudio/dartssh2">dartssh2</a> & <a href="https://github.com/TerminalStudio/xterm.dart">xterm.dart</a>.
</p>


## 📥 Install

Platform | From
--- | --- 
iOS / macOS | [AppStore](https://apps.apple.com/app/id1586449703)
Android | [GitHub](https://github.com/lollipopkit/flutter_server_box/releases) / [CDN](https://cdn.lolli.tech/serverbox/?sort=time&order=desc&layout=grid) / [F-Droid](https://f-droid.org/packages/tech.lolli.toolbox) / [OpenAPK](https://www.openapk.net/serverbox/tech.lolli.toolbox/)
Linux / Windows | [GitHub](https://github.com/lollipopkit/flutter_server_box/releases) / [CDN](https://cdn.lolli.tech/serverbox/?sort=time&order=desc&layout=grid)

**Please only download pkgs from the source that you trust!**  
- `AppStore` & `CDN` packages are built by myself
- Github releases are built by Github Actions
- Other sources are built by themselves


## 🔖 Feature
- `Status chart` (CPU, Sensors, GPU...), `SSH` Term, `SFTP`, `Docker & Pkg & Process`...
- Platform specific: `Bio auth`、`Msg push`、`Home widget`、`watchOS App`...
- English, 简体中文; Deutsch [@its-tom](https://github.com/its-tom), 繁體中文 [@kalashnikov](https://github.com/kalashnikov), Indonesian [@azkadev](https://github.com/azkadev), Français [@FrancXPT](https://github.com/FrancXPT), Dutch [@QazCetelic](https://github.com/QazCetelic); Español, Русский язык, Português, 日本語 (Generated by GPT)


## 🏙️ ScreenShots
<table>
  <tr>
    <td><img width="277px" src="https://cdn.lolli.tech/serverbox/screenshot/1.png"></td>
    <td><img width="277px" src="https://cdn.lolli.tech/serverbox/screenshot/2.png"></td>
    <td><img width="277px" src="https://cdn.lolli.tech/serverbox/screenshot/3.png"></td>
  </tr>
  <tr>
    <td><img width="277px" src="https://cdn.lolli.tech/serverbox/screenshot/4.png"> </td>
    <td><img width="277px" src="https://cdn.lolli.tech/serverbox/screenshot/5.png"></td>
    <td><img width="277px" src="https://cdn.lolli.tech/serverbox/screenshot/6.png"></td>
  </tr>
</table>


## 🆘 Help
- In order to push  server status to your portable device without opening ServerBox app (Such as **message push** and **home widget**), you need to install [ServerBoxMonitor](https://github.com/lollipopkit/server_box_monitor) on your servers, and config it correctly. See [wiki](https://github.com/lollipopkit/server_box_monitor/wiki) for more details.
- **Common issues** can be found in [app wiki](https://github.com/lollipopkit/flutter_server_box/wiki).

Before you open an issue, please read the following:
1. Paste the **entire log** (click the top right of the home page) in the issue template.
2. Make sure whether the issue is caused by ServerBox app.
3. Welcome all valid and positive feedback, subjective feedback (such as you think other UI is better) may not be accepted.

After you read the above, you can open an [issue](https://github.com/lollipopkit/flutter_server_box/issues/new).


## 🧱 Contribution
Any positive contribution is welcome.

### Development
1. Setup [Flutter](https://flutter.dev/docs/get-started/install) environment.
2. Clone this repo, run `flutter run` to start the app.
3. Run `dart run fl_build -p PLATFORM` to build the app.

### Translation
- [Guide](https://blog.lpkt.cn/posts/faq/) can be found in my blog.
- We need your help! Just feel free to open a PR.


## 💡 My other apps
- [GPT Box](https://github.com/lollipopkit/flutter_gpt_box) - A third-party GPT Client for OpenAI API on all platforms.
- [More](https://github.com/lollipopkit) - Tools & etc.


## 📝 License
`GPL v3 lollipopkit`
