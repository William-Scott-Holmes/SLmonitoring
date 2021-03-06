---
copyright:
  years: 1994, 2017
lastupdated: "2018-05-18"
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# 既存のモニターの編集
デバイスに追加したモニターは、いつでも変更したり削除したりできます。モニターの変更では、タイプと通知オプションを変更できます。一方、モニターを削除すると、そのモニターは完全に取り消されます。既存のモニターを編集するには、以下の手順に従います。

1\. **「モニター」**ページの**「既存のモニターの編集」**という見出しの下にあるモニター詳細をクリックして、編集のためにモニターを開きます。

2\. 必要に応じて、**「モニターの詳細 (Monitor Details)」**を変更します。編集可能な各フィールドについて詳しくは、以下の表を参照してください。

<caption>表 1. 編集可能なフィールドの詳細 </caption> 
|フィールド|詳細|操作|
|---|---|---|
|モニター・タイプ|デバイスからの応答を待機する時間。デフォルトでは Service Ping に設定されます。Slow Ping は、応答を 5 秒間待機するので、非ネットワーク・タスク用に最適化されたサーバーに使用して、要求の処理時間をより長く確保することができます。Service Ping は ping を 5 分ごとに 1 回発行し、エコー応答を 1 秒間待機します。複数回 ping の応答が返されなかった場合は、アラートが発行されます。|**「Slow Ping」**または**「Service Ping」**のいずれかを選択します。|
|通知| 通知対象ユーザーは、割り当てられた応答時間内にデバイスが ping に応答しない場合に、必ず自動通知を受け取ります。通知を受け取るには、通知を受け取るデバイスに関連付けられたアカウントにユーザーが属している必要があります。|ユーザーを追加するには、新しい**通知対象ユーザー**を選択し、**「ユーザーの追加」**をクリックします。ユーザーを削除するには、既存の通知対象ユーザーの横の**「削除」**アイコンをクリックし、**「はい」**をクリックして操作を確認します。|
|通知までの時間|デバイスが ping に応答しなかった場合に、システムが通知を送信するまで待機する時間。複数の待機時間を使用できます。**注:** 通知対象ユーザーを選択していない場合、通知の詳細は必要ありません。|必要な待機時間を選択します。|

3\. モニターに変更を適用するには、**「更新」**をクリックします。操作を取り消すには、**「キャンセル」**をクリックします。

## 次の手順

モニターを編集すると、モニターは、モニターの詳細指定に従って機能を再開します。タイプを変更した場合は、ping の受信を待機する時間が変わります。通知オプションを変更した場合は、通知モードが新しい選択内容に基づいて変更されます。編集後も「モニタリング」タブからモニターにアクセスできます。
