<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="utf-8">
</head>
<body>
  <h2>Webシステム / Webサイト</h2>
  <div class="mermaid">
  graph RL
    subgraph "仕様"
      A-1[Mermaid]
    end
    subgraph "実装"
      A-1 --> B-1["JavaScriptライブラリ(mermaid.js)"]
      A-1 --> B-2[CLI]
      A-1 --> B-3[プラグイン]
      A-1 --> B-4[Webサービス]
    end
    A-1[Mermaid] --> A-2[公式ドキュメント]
  </div>
  <script src="https://unpkg.com/mermaid/dist/mermaid.min.js"></script>
  <script>
    mermaid.initialize({startOnLoad:true});
  </script>
</body>
</html>
