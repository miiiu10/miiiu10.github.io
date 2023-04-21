---
title: 会議室の予約管理をするSlackアプリを作りました。
subtitle: 今まで会議室の予約管理がチャットで行われており、予約の確認・登録が面倒だったためSlack上で予約の確認・登録ができるようなアプリを作成しました。

# Summary for listings and search engines
summary: 今まで会議室の予約管理がチャットで行われており、予約の確認・登録が面倒だったためSlack上で予約の確認・登録ができるようなアプリを作成しました。

# Link this post with a project
projects: []

# Date published
date: '2023-04-21T00:00:00Z'

# Date updated
lastmod: '2023-04-21T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
#   focal_point: ''
#   placement: 2
#   preview_only: false

authors:
  - admin

tags:
  - 趣味

categories:
  - Demo
---

# OchanomaBookerの使い方

![gif](./kirin.gif)

## 概要
研究室のお茶室のスケジュールを管理するSlackアプリです。
現在はお茶の間が消失したため、621の会議室のスケジュールを管理しています。
Google Calendar上でもスケジュールの確認・削除ができます。

## 導入方法
slackのAppから"OchanomaBooker"を選択します。

## 使い方
基本的にホームタブから使用します。
![png](./home.png)

### 予定追加時
日付と開始時刻・終了時刻を選択し、伝えたいことがあれば詳細に記入できます。
終了時刻を入力しなかった場合は開始時刻から1時間後まででスケジュールに登録されます。
最後に追加ボタンを押すと、予定が追加されます。
アプリから追加すると#お茶室予約 に予約したことが通知されます。
誰かが先に予定を入れていた際には予約ができないようになっています。

### 予定確認時
削除ボタンの横にある確認ボタンを押すと、予定の確認ができます。
30日後までの予定のみ表示されます。
![png](./check.png)

### 予定削除時
予約確認時に表示された予定のIDを入力し、削除ボタンを押すと予定が削除されます。
予約をした際に送信されたチャット横にあるdeleteボタンを押すとその予定が削除されます。

~~隠しコマンド~~
- メッセージで"hello"と打つと…

## その他
もし、botが動いていない時はGoogle Calendarにアクセスして入力してください。

その他の要望，不具合等があれば，ご連絡ください！

実装コードは[ここ](https://github.com/miiiu10/ocha-room)にあります。もし一緒に開発したい！という人がいたら気軽に声をかけてください。