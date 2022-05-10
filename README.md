# Who use Stripe in Japan?

## 会社・アプリの追加について

"Who use Stripe in Japan" に会社・組織を追加するには、`src/data/organizations.csv`ファイルを編集するプルリクエストを提出してください。

追加する JSON オブジェクトは以下の形式にしたがってください。

- name: 会社・組織の名前 (必須)
- websiteUrl: 会社・組織の URL (必須)
- description: 会社・組織の説明（1 文程度) (必須)
- applicationUrl: Stripe を使っているサービスやプロダクトの公開 URL (必須)
- applicationUrl2: Stripe を使っているサービスやプロダクトの公開 URL (必須・ない場合は`-`を入力)
- applicationUrl３: Stripe を使っているサービスやプロダクトの公開 URL (必須・ない場合は`-`を入力)

**入力例**

```csv
Example co,https://example.com,Awesome Stripe developer agency,https://app1.example.com,https://app2.example.com,-
```

## See also

- Angular: https://github.com/ng-japan/who-use-angular-in-japan
- Vue.js: https://github.com/vuejs-jp/who-use-vuejs-in-japan
- Node.js: https://github.com/nodejsjp/who-use-nodejs-in-japan
  
## Inspired by

https://github.com/nodejsjp/who-use-nodejs-in-japan
