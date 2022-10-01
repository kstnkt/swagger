# swagger の使い方

## 本ドキュメントの更新方法

1. theapi.yaml を修正しコミット
1. 基本的にコミットされると以降の処理は自動で実行されるが、必要な場合は以降を実行する
1. 本リポジトリの上部 **Actions** をクリック
![image](https://user-images.githubusercontent.com/56060104/183226452-19b72aa5-9b27-4f73-ad36-75df238cb7d8.png)
1. 過去に成功している **Pages build and deployment** をクリック
![image](https://user-images.githubusercontent.com/56060104/183226502-2335d6f3-43ba-4f75-a4fe-7315147ff7e1.png)
1. 右上の **Re-run all jobs** をクリックし、すべてのジョブがグリーンで終わるのを待つ
![image](https://user-images.githubusercontent.com/56060104/183226574-eb130f82-3a25-49f3-9557-33a89d147eb0.png)

上記で、所定の URL から swagger のドキュメントを参照できるようになる。

## API を swagger から確認する

### 事前準備

ローカルに開発環境を構築し、API サーバをトークン認証にしてローカルで以下のようにして実行しておく。
```
cd api
source venv/bin/activate
flask run
```
Swagger の Authorize を以下のように設定する

![image](https://user-images.githubusercontent.com/56060104/184055536-500b6faf-ae05-4a55-8d3e-bc5187da000d.png)

![image](https://user-images.githubusercontent.com/56060104/184055634-d96ade53-187b-495a-8778-6717838b106d.png)

### Swagger 上から API を実行

![image](https://user-images.githubusercontent.com/56060104/184055726-ca28b27c-7509-4439-843f-bd39adef4e52.png)

![image](https://user-images.githubusercontent.com/56060104/184055770-0c90188f-5ece-42c0-9d52-78a47684ec75.png)

![image](https://user-images.githubusercontent.com/56060104/184055830-b372f3b3-b585-4d03-a4f9-e2a3febd16b5.png)
 
