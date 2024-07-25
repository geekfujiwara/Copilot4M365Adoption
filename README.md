# Copilot4M365Adoption

Copilot Adoption Platform (以下CAP)は、Copilot for M365 の活用促進を支援するゲーミフィケーションプラットフォームです。

CAP はPower Platform をベースとしています。

![image](https://github.com/user-attachments/assets/ee1f2cb7-2533-452c-9447-7963da4d2966)

レスポンシブデザインに対応しています。

![image](https://github.com/user-attachments/assets/e1f51730-b21b-45e4-9d72-a855e43fce3a)

アクションに活用するため利用状況が可視化でき人気コンテンツから必要なコンテンツを確認することができます。

![image](https://github.com/user-attachments/assets/5e1996c7-7f7e-4ace-85a2-6fc411b5ac86)


## アーキテクチャ

CAP は2種類のPower Apps で作成されています。

* モデル駆動型アプリ: CoE チーム
* キャンバスアプリ: 利用者

アーキテクチャはこちらのようになっており、データは一つのDataverse で共有されています。

先にモデル駆動型アプリで設定をして、利用者の方々にご利用いただきます。

![image](https://github.com/user-attachments/assets/ad133dc6-d393-468e-8108-554be5bf71e7)

### コンポーネント別の説明

## CoEチーム向けアプリ

### 可視化

学習リソースの視聴やイベント参加などでもらえるポイントをランキング形式で可視化

![image](https://github.com/user-attachments/assets/c70ded54-befc-4a95-9847-faea308ae6e0)

ユーザーがよく利用しているイベントや学習リソース、プロンプトを可視化

![image](https://github.com/user-attachments/assets/1afdaf16-b633-4baa-a4f4-0cae3082881b)

イベントや学習リソース、プロンプトのカテゴリ別の数量を表示

![image](https://github.com/user-attachments/assets/77d0ef6e-e173-4f3a-bb13-3ef217d6296d)

### トレーニングの提供やプロンプトのテンプレート化

ユーザーに提供したいプロンプトを追加することができます。

![image](https://github.com/user-attachments/assets/a7f65693-920d-49e0-91b5-0e4f4d0b2470)

ユーザーに提供したいイベントを追加することができます。

![image](https://github.com/user-attachments/assets/a1c96660-f959-4da0-9431-40fd483c1d1e)

ユーザーに提供したい学習リソースを追加することができます。

![image](https://github.com/user-attachments/assets/2c910626-198b-439d-8e0a-1ce2000baad8)

### ゲーミフィケーションの設定

イベントや学習リソース、プロンプトを利用するとその種類によって付与されるポイントが異なります。その設定を行うことができます。

![image](https://github.com/user-attachments/assets/47d26e6e-af4f-4d8f-98ec-3084b5f0af18)

ポイントが貯まると、バッジを取得することができます。

![image](https://github.com/user-attachments/assets/8c1f5856-ee28-421b-aeff-3b4ad5c89377)


バッジはぽポイント到達だけではなく、特定のイベントに参加したユーザーに与えることもできます。

![image](https://github.com/user-attachments/assets/75849c93-3de0-4b70-9c46-e5ff56572b3f)

## 利用者向けのアプリ

### イベント

![image](https://github.com/user-attachments/assets/a5db0ae9-e3af-4cb8-ac00-105522421487)

詳細のリンクに遷移することができます。

![image](https://github.com/user-attachments/assets/ead359a6-c8ac-4835-bf2f-c15350a658b2)


### 学習リソース

![image](https://github.com/user-attachments/assets/5b6f973c-f4b0-45cc-9f11-bd868a3d7bae)

学習リソースの詳細の確認ができます。

![image](https://github.com/user-attachments/assets/cf62b07d-558f-4887-ae3d-8663df1ec919)


### ポイント申請

![image](https://github.com/user-attachments/assets/72924323-9ddd-493e-a01b-aaf0f8dac3bb)

ポイント申請する際には承認ワークフローが起動されます。

![image](https://github.com/user-attachments/assets/b361dcf1-1058-40a3-8cd8-b4db07997ff7)


### ポイント獲得履歴

![image](https://github.com/user-attachments/assets/740d8815-e9a8-4f79-9161-9948ea645050)

### プロンプト

![image](https://github.com/user-attachments/assets/bc869128-a76a-4b37-8748-5760e25ef566)

### ランキング

![image](https://github.com/user-attachments/assets/a0305664-28d6-4a7c-9d01-d908e1125258)

### バッジ

![image](https://github.com/user-attachments/assets/28addb0c-a109-455e-81da-4013769fe86f)



## インストール方法

### 前提条件

* ライセンスは、管理者及び利用者にPower Apps Premium ライセンスが必要です。
* 言語ラベルは日本語で利用できます。

### ソリューションの取得

ソリューションを取得します。

[こちら](https://github.com/geekfujiwara/Copilot4M365Adoption/releases)から取得することができます。


[Power Apps ポータル](https://make.powerapps.com/)にアクセスします。

ソリューションに移動します。

![image](https://github.com/user-attachments/assets/8f4f0f73-088d-49b3-aa68-80d3bbf14564)


取得したソリューションをPower Apps ポータルにインポートします。

![image](https://github.com/user-attachments/assets/45b42639-a985-4a89-94ac-6293d8b827ad)

ソリューションを参照からZip形式のままインポートします。

![image](https://github.com/user-attachments/assets/85211ab5-7c2a-45e5-bb92-20a8bd9a6775)

次へをクリックして、接続情報が更新されるのを街、インポートへ進みます。

![image](https://github.com/user-attachments/assets/8037bf94-94fb-4662-88ca-f82de6ba09ae)

インポートには数分かかります。

![image](https://github.com/user-attachments/assets/396a66e8-27bf-4188-829e-3ec00981cf8a)


> [!NOTE]
> 以下のように警告が表示されたとしてもラベルの問題のため問題ありません。
> ![image](https://github.com/user-attachments/assets/0d264880-d39b-489e-8e54-08489e46da01)


インポートが完了し次第、ソリューションに移動します。

![image](https://github.com/user-attachments/assets/fda9e6d3-06c6-4854-870a-87cd5a95bced)

管理者向け(CoEチーム)のアプリと、利用者向けアプリ(Copilot 活用アプリ)の2種類が提供されています。、

![image](https://github.com/user-attachments/assets/71aaaa5c-ccf0-4ea3-8cfd-34c45fcd8a3d)

ソリューションのインポートは完了です。

### セキュリティロール

利用者向けに必要な最低限のセキュリティロールとして「CAP Basic User」というセキュリティロールが提供されています。

Copilot 活用アプリを共有するにはこちらのセキュリティロールを共有するようにしてください。

Copilot 活用アプリを共有するには、まずアプリを選択して共有します。

![image](https://github.com/user-attachments/assets/f6d7389a-9593-4f99-be88-a148848ac745)

共有先のユーザーを選択します。

![image](https://github.com/user-attachments/assets/4d5bf525-bdbb-4c17-84f0-c1f18785b4b2)

セキュリティグループに対して共有することもできます。

![image](https://github.com/user-attachments/assets/d6aa6496-65a1-4df5-9fbd-1d9bff3db331)








