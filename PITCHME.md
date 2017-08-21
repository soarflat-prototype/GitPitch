# GitPitch 
GitPitchは、マークダウンファイルであるPITCHME.mdをオンライン、及びオフラインのスライドショーに変えるサービス。

---

## 使い方

1. 任意のディレクトリにPITCHME.mdを作成し、マークダウンを記述する
1. PITCHME.mdをGitHubなどのリポジトリにpushする
1. pushしたらGitPitchが自動でマークダウンを整形するため、スライドショー完成
1. [https://github.com/soarflat-prototype/GitPitch](https://github.com/soarflat-prototype/GitPitch)にPITCHME.mdをpushした場合、[https://gitpitch.com/soarflat-prototype/GitPitch](https://gitpitch.com/soarflat-prototype/GitPitch)でスライドショーを見れる

---

## ソースコードを読み込んで表示する
- `---?code=[ファイルのパス]`
- `+++?code=[ファイルのパス]`

で指定したファイルのソースコードを読み込んで表示する

+++?code=assets/js/sample.js

---