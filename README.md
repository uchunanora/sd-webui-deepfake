# sd-webui-deepfake
 
## 利用方法

### Step0: このリポジトリをクローン

```bash
git clone https://github.com/uchunanora/sd-webui-deepfake.git
```

### Step1: モデルのインストール
webui.ipynbの2段目を実行（けっこう時間がかかる）

### Step2: 一度実行

webui.ipynbの1段目を実行（少し時間かかる）

Running on public URL: https://??????????.gradio.live

と出てくるのでリンクをクリックしてStable Diffusion Web UIに飛ぶ。

### Step3: mov2movとReActorをインストール

Web UI内のExtensionsをクリック

Install from URLをクリック

URL for extension's git repositoryに

```bash
https://github.com/Scholar01/sd-webui-mov2mov
```

をペーストしてInstallをクリック

また、

```bash
https://github.com/Gourieff/sd-webui-reactor
```

をペーストしてInstallをクリック

### Step4: 再実行
webui.ipynbの1段目セルのStopを押して、もう一度Runを押し再実行する。

### Step5: Enjoy🎉
