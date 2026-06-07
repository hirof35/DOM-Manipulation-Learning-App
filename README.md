DOM Manipulation Labこのプロジェクトは、JavaScriptを用いた基本的なDOM操作（取得、作成、置換、削除）を学習・実験するためのサンプルコード集です。
<img width="1913" height="1030" alt="スクリーンショット 2026-06-07 105107" src="https://github.com/user-attachments/assets/c5a8c4b4-4f3b-4af0-8c6b-d0409da34c09" />

概要本コードは、以下のDOM操作の基本を網羅しています。
要素の取得: id, name, tagName, className を用いた要素の特定。
要素の作成: createElement と createTextNode を使用した動的な要素生成。
要素の操作: replaceChild による置換や removeChild による削除処理。イベント処理: addEventListener を用いたインタラクティブな動作の実装。
ディレクトリ構成Plaintext.
├── index.html       # DOM操作の実装と構造
└── README.md        # プロジェクトの説明書
各ボタンの機能説明ボタンID実行内容使用技術button1入力値の取得（ID）getElementById, valuebutton2入力値の取得（Name）getElementsByNamebutton3タグ名の取得とループ表示getElementsByTagNamebutton4クラス名の取得とループ表示getElementsByClassNamebutton5新しいリストアイテムの追加createElement, appendChildbutton6リストアイテムの置換replaceChildbutton7リスト末尾の削除removeChild学習のポイントこのコードを理解する上で、以下の概念に注目してください。
NodeList と HTMLCollectionの違い: 取得方法によって返されるオブジェクトの性質（forEachが使えるか等）が異なります。
セキュリティ: innerHTML を使用する際は、外部からの入力をそのまま挿入するとXSS（クロスサイトスクリプティング）のリスクがあるため、安全な textContent の利用を検討してください。
効率的なDOM操作: removeChild を行う際に、親ノードを特定してから削除する、あるいは lastElementChild のようなモダンなプロパティを活用すると、コードがより簡潔になります。
ライセンス本コードは学習用途として自由にご利用いただけます。
