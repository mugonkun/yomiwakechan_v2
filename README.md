# 読み分けちゃん2 — 公式配布ページ

配信のコメントを、複数の声で読み分けて読み上げるツールです。
ツイキャス・YouTube・ニコニコ生放送・Twitch・ふわっち・ミクチャ・Kick・ミラティブのコメント取得に対応しています。

**最新版は v2.25g です（2026-10-17 公開）。**

## ご案内（説明書）

- **[ご案内ページ](https://mugonkun.github.io/yomiwakechan_v2/)** ← まずはこちら
  - [配信者向けガイド](https://mugonkun.github.io/yomiwakechan_v2/streamer.html)（インストール〜最初の配信まで・わんコメ連携・AI連携・音声認識）
  - [お歌記法ガイド](https://mugonkun.github.io/yomiwakechan_v2/song.html)（リスナー向け・インストール不要）

## ダウンロード

- **[最新版インストーラ（Releases）](https://github.com/mugonkun/yomiwakechan_v2/releases/latest)**
  … 最新版 **v2.25g**（2026-10-17 公開）
- **[v2.25g の更新内容](https://mugonkun.github.io/yomiwakechan_v2/#whatsnew-v225g)**（コメントの中の英文だけを「英文検出時」の声で読む〔既定 ON・2 文字以上の英単語・編集面で変更可〕／URL は「URL検出時」の声／新規インストール環境は英文・URL の声が Windows 標準の英語音声〔Zira〕／v2.25d〜f＝［今の 1 件を止める］・長い効果音の打ち切り・即時型パッドの声の自動合成）
- **[v2.25c の更新内容](https://mugonkun.github.io/yomiwakechan_v2/#whatsnew-v225c)**（CeVIO CS7〔Creative Studio 7〕に対応／タイムライン面にパッド帯＝押せるパッドが正方形のボタンで配信画面に並ぶ〔✓「パッド」で表示／非表示〕／シャウトの試し読みに［打ち切り］）
- **[v2.25b の更新内容](https://mugonkun.github.io/yomiwakechan_v2/#whatsnew-v225)**（v2.25b＝10/15 の Windows Update 後に CeVIO AI 未起動で本体が落ちる件の対策／コラボ席〔β〕＝コラボ相手の枠のコメントも受信して読み分け・最大 10 席／過去ログから追加／コメントのバインド＝末尾の + で分割投稿を 1 件に・16 件まで／パッドの背景画像／権利者の表示と来歴の署名）
- **[v2.24a／v2.24 の更新内容](https://mugonkun.github.io/yomiwakechan_v2/#whatsnew-v224)**（v2.24a＝不具合の報告に配信の生ログを 2 つまで添付〔作成前に確認・視聴者の ID・表示名・コメント本文が開発者に渡る〕・各ツールの席に✓「生ログを残す」〔既定 ON〕／v2.24＝シャウトの条件に音声認識ワード〔配信者の発話・2 欄〕とメンバーシップギフト〔贈り主の購入〕・置換語 $個数$／パッドは読み上げ文なしでも順番待ち・即時型の✓「順番待ちさせる」・押せない理由の表示／OBS 発話検出の表示是正）
- **[v2.23 の更新内容](https://mugonkun.github.io/yomiwakechan_v2/#whatsnew-v223)**（パッドで OBS のシーンを切り替える＝声〔キュー型は読み上げ〕と同時・N 秒後・後のタイミングで・Studio Mode 中はプレビューへ）
- **[v2.22a／v2.22 の更新内容](https://mugonkun.github.io/yomiwakechan_v2/#whatsnew-v222)**（新タブ「パッド」・効果音の「鳴らす長さ」4 択目・Kick／ミラティブ対応・同梱ツール 9 基の新版）
- **[v2.21a〜v2.18c の更新内容](https://mugonkun.github.io/yomiwakechan_v2/#whatsnew-v221)**（ニコニコ生放送・Twitch・ふわっち・ミクチャ・ツイキャス ブラウザ版に対応／出来事通知を種類ごとに受け取る・読み上げる・わんコメへ送るで選べる／初期設定ウィザードに同梱の全ツール／シャウトの承認制と 3 段化／起動時の更新確認）／[v2.18b](https://mugonkun.github.io/yomiwakechan_v2/#whatsnew-v218a)・[v2.16](https://mugonkun.github.io/yomiwakechan_v2/#whatsnew)／[v2.14](https://mugonkun.github.io/yomiwakechan_v2/#whatsnew-v214)・[v2.13 の更新内容](https://mugonkun.github.io/yomiwakechan_v2/#whatsnew-v213)
  （**新エンジン irodori-TTS-for-yomiwakechan に対応**・わんコメ連携・AI連携・音声認識・起動の手順の変更・アプリ内更新ほか）<br>
  - irodori-TTS-for-yomiwakechan の配布ページ：https://mugonkun.github.io/irodori-tts-for-yomiwakechan/
  v2.10 からのアップデートは上書きインストールで、**設定はそのまま引き継がれます**。
  起動の手順が変わり、コメントの取得は [受信開始] を押してから始まります。
- 対応 OS：Windows 10 / 11（64bit）
- 初回起動時に Windows の警告（SmartScreen）が表示されます。手順は
  [案内ページ](https://mugonkun.github.io/yomiwakechan_v2/#smartscreen)をご覧ください。
- **本ソフトの再配布は禁止しています。** 紹介の際はこのページの URL をお伝えください。
  公式配布ページ以外から入手したファイルは実行しないでください。

## 作者・連絡先

- 作者（本ソフトの権利者）：X アカウント [@mugonkun](https://x.com/mugonkun) の所有者
- 最新情報・お知らせ・不具合報告：X [@yomiwakechan](https://x.com/yomiwakechan)
