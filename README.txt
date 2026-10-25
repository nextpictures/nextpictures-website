ネクストピクチャーズ LP 公開用データ
================================

■ 中身
  index.html … ページ本体
  thanks.html … お問い合わせ送信後の完了ページ
  images/    … ページで使う写真（index.html と同じ階層に置いてください）

■ 公開方法（どれか1つ）
  1) 今のサーバーにアップ
     FTPソフトやサーバーのファイルマネージャーで、
     ドメインの公開フォルダ（public_html など）に index.html と images フォルダをそのままアップロード。
     例） https://（ドメイン）/ でトップに表示
         サブページにしたい場合はフォルダを作って入れる → https://（ドメイン）/lp/

  2) Netlify（無料）
     app.netlify.com にこのフォルダ（または zip）をドラッグ＆ドロップ →
     Domain settings で今あるドメインを追加し、ドメイン会社のDNSを案内どおり設定。

■ 公開前に確認してほしいこと
  ・写真は Unsplash の仮素材です。自社撮影の写真に差し替えを推奨（同じファイル名で上書きすればOK）。
  ・お問い合わせフォームは Netlify Forms で nextpictures.japan@gmail.com に届く設定です。
    Netlify の管理画面で次の2つを行ってください。
      1) Forms →「Enable form detection」を押す（押した後に再デプロイ）
      2) Forms →「Submission notifications」→ Email notification の宛先に nextpictures.japan@gmail.com を登録
  ・料金・郵便番号・事例の［ ］部分は仮のままです。
