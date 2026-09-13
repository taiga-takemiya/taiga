# taiga

## 🗼 Tokyo Tower 3D World

Three.js で作った東京タワーの 3D ワールド（`index.html`）。ビルド不要の単一ページで、three.js は `vendor/` に同梱しているので外部 CDN に依存しません。

### 開く

```bash
python3 -m http.server 8000
# → http://localhost:8000/index.html
```

（ES モジュールを使うため `file://` ではなく HTTP サーバー経由で開いてください。GitHub Pages でもそのまま動きます。）

### 操作

| 操作 | 内容 |
| --- | --- |
| Orbit モード | ドラッグで回転、ホイールでズーム、右ドラッグで移動 |
| Walk モード | WASD で歩行、マウスで視点、Shift でダッシュ、Esc で戻る |
| 🌙 Night | 夜景（タワーのライトアップとビルの窓明かり） |
| ⟳ Auto | 自動回転 |

### 構成

- 実寸ベース（全高 333 m、メインデッキ 150 m、トップデッキ 250 m）の手続き生成ラティス構造
- 国際オレンジと白の 7 段バンド塗装、航空障害灯の点滅
- 周辺の芝公園風の広場、街区ビル、道路
