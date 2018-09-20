# 正誤表

| ページ    | 修正前                   | 修正後              |
|:--------|:------------------------|:--------------------|
| 109     | `mutate(region =  gsub("[ア-ン].+州", "", region))` | `mutate(region =  gsub("[[:space:]][ア-ン].+州", "", region))` |
| 154     | e-Stat APIのホームページ（https://www.e-stat.go.jp/api/apiuser/provisional/ ） | e-Stat APIのホームページ（https://www.e-stat.go.jp/mypage/user/preregister ） |
| 154     | e-Stat APIの利用登録は、e-Stat本体のユーザー登録とは別になります | 2018年1月4日からはAPI機能のユーザ登録も本体に統合されました。 |
| 154     | ログインして、「アプリケーションIDの取得」（https://www.e-stat.go.jp/api/apiuser/appid_regist/ ）というページにアクセスします。 | ログインして、マイページの「API機能(アプリケーションID発行)」（https://www.e-stat.go.jp/mypage/view/api ）というページにアクセスします。 |
