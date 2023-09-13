# misskey-destroyer-watch-plugin
直近の通知破壊者のリアクションを一覧で見るMisskeyプラグインです。

![images](images/image_101.png)

## 使い方

投稿用テキスト入力画面のプラグインボタンから選択し、リアクションを通知を取得します。  
[閲覧] ボタンを押すとダイアログウインドウの表示のみを行います。  
[投稿] ボタンを押すとダイアログウインドウの表示後、投稿用テキストに結果の反映をします。  

## 導入

releaseからMisskeyDestroyerWatchPlugin.isをダウンロードし、内容を全てコピーし、`設定 > プラグインのインストール`のテキストエリアに貼付、`インストール`を押してください。  
<small>※コピーに不備がある場合はインストールに失敗しエラーが表示されると思います。</small>

![images](images/image_106.png)

通知を見るreleaseからMisskeyDestroyerWatchPlugin.isをダウンロードし、内容を全てコピーし、`設定 > プラグインのインストール`のテキストエリアに貼付、`インストール`を押してください。  
<small>※コピーに不備がある場合はインストールに失敗しエラーが表示されると思います。</small>

![images](images/image_107.png)


###  ダイアログの表示修正用custom css
max-widthとtext-alignを以下のように修正して適応(数値は調整してください)
```css
.xa5A4 {
    min-width: 320px;
    max-width: 2000px;  /* original 480px; */
    box-sizing: border-box;
    text-align: left; /* original center; */
}
```

## 設定値の変更
設定 > プラグイン > 設定ボタンからパラメータの変更画面に遷移します。
![images](images/image_102.png)

### 共通パラメータ
共通のパラメータです。  
![images](images/image_103.png)

### ダイアログのパラメータ
共通のパラメータです。  
![images](images/image_104.png)

### 投稿用テキストのパラメータ
投稿用テキストのパラメータです。
![images](images/image_105.png)

## 作者
@hatopop_vr@misskey.io