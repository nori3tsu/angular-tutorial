# Angular Example

[目黒JavaScriptもくもく会 \#6 \- connpass](https://megurojsmk2.connpass.com/event/152024/) でもくもくした [Angular 公式チュートリアル](https://angular.jp/start) のリポジトリです。

```
$ npm install
$ npx ng serve
htts://localhost:4200
```

VSCode用に下記設定を追加しています。

* TSLintの自動修正(.vscode/settings.json)
* VSCodeデバッグ(.vscode/launch.json)

## VSCodeデバッグ

* `$ npx ng server` で開発サーバーを立ち上げる
* VSCodeのDebugから `Launch Chrome against localhost` を実行
* VSCodeの止めたい箇所にブレイクポイントを設定

参考:

* [【Angular】VS Codeでデバック設定](https://mosapride.com/index.php/2018/04/12/post-774/)

## VSCode拡張

下記のExtensionを入れると開発がはかどりました。

* [Angular Language Service \- Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
  * Angular公式が開発、基本的な機能を提供してくれる。必須。
    * コンポーネントの補完
    * コンポーネント定義元にジャンプ
    * HTMLタグ内でコンパイルエラーを出す
* [vscode\-angular\-html \- Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=ghaschel.vscode-angular-html)
  * AngularのHTMLテンプレートをシンタックスハイライトしてくれる。必須。
* [Angular Files \- Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=alexiv.vscode-angular2-files)
  * VSCode Explorerから右クリックで各種generateコマンドを実行できる。
