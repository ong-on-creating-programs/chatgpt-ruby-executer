# ChatGPT に Python 以外の言語も実行させたい！
## Step0

> [!NOTE]
> ChatGPT に Python 以外の言語も実行させたい

> [!TIP]
> 現在のところ、ChatGPTはPythonのコードのみを実行することができます。他のプログラミング言語（例えばJavaScript、Ruby、C++など）のコードを直接実行する機能は提供されていません。
> 
> ただし、Pythonに関する質問やコードの実行、またはPython以外のプログラミング言語に関する質問については、アドバイスやコードの例を提供することが可能です。プログラミングに関する質問やコードサンプルがあれば、どうぞお気軽にお聞きください。

ですよねー。


## Step1: Ruby on Browwser を改造する
- https://rubyonbrowser.ongaeshi.me を改造してzip圧縮かつURLエンコードされたパラメータを受け取れるようにする。
- q2=xxxxxx で受け取れるようにする

## Step2: ChatGPT に Ruby on Browser の URL ルールを教える

```
大文字を小文字に変換するRubyスクリプト。
```

```
このRubyスクリプトをrubyonbrowser上で実行させたいです。

URL は https://rubyonbrowser.ongaeshi.me/
後ろにクエリ文字列 ?q= 
コードテキストを zip 圧縮した文字列を q のパラメータに設定
```

## Step3: 日本語からスクリプトを生成させてそのまま Ruby on Broser の URL も作成する

## 既知の不具合
- PC 版だとURLがクリックできない？(iOS の Safari なら問題なくクリックできた)

