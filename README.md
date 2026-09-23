# type2En · 打字译英语

一款 Android 输入法:正常的中文拼音输入,打开「译」即可边打字边输出英文或日文。

**官网(含下载)**:开启 GitHub Pages 后访问 `https://<你的用户名>.github.io/type2en/`

## 下载

- 最新版:[`download/type2en-1.0.0.apk`](download/type2en-1.0.0.apk)(v1.0.0,0.7 MB,Android 7.0+)
- SHA256:`fa55331dbaab8bfcdd028641f5e4b2892a289e193e84379ad39592b629418cd0`

## 特性

- 🀄 正常的中文拼音输入:整句词优先、同音字全量候选
- 🌐 「译」开关注定输出:实时预览英文,空格上屏
- 🇯🇵 中→日双语对:拼音直出日文,罗马音直输假名
- 😀 表情面板、符号层、长按连删
- 📚 离线词典本地运行;在线翻译(MyMemory / Google)自动纠偏
- 🎨 iOS 原生质感键盘

## 发布到 GitHub Pages

1. 在 GitHub 新建空仓库 `type2en`(或任意名字)
2. 运行 `bash publish.sh <你的GitHub用户名> <你的PAT令牌>`
   - PAT 需要 `repo` 权限:GitHub → Settings → Developer settings → Personal access tokens
3. 脚本会自动:推送代码 → 上传 APK 到 Release → 开启 Pages
4. 访问 `https://<用户名>.github.io/type2en/` 即为官网

## 许可

仅供学习交流使用。
