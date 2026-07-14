# Vulkan Tutorial 日本語訳 用語集

章をまたいで表記を統一するための用語一覧。初出では「英語（カタカナ／日本語）」とし、以降は右列に揃える。

| English | Japanese |
|---------|----------|
| swap chain / swapchain | スワップチェーン |
| pipeline | パイプライン |
| pipeline barrier | パイプラインバリア |
| graphics pipeline | グラフィックスパイプライン |
| compute pipeline | コンピュートパイプライン |
| descriptor | ディスクリプタ |
| descriptor set | ディスクリプタセット |
| descriptor set layout | ディスクリプタセットレイアウト |
| descriptor pool | ディスクリプタプール |
| command buffer | コマンドバッファ |
| command pool | コマンドプール |
| queue | キュー |
| queue family | キューファミリー |
| physical device | 物理デバイス |
| logical device | 論理デバイス |
| instance | インスタンス |
| surface | サーフェス |
| image view | イメージビュー |
| framebuffer | フレームバッファ |
| render pass | レンダーパス |
| dynamic rendering | ダイナミックレンダリング |
| shader module | シェーダモジュール |
| vertex buffer | 頂点バッファ |
| index buffer | インデックスバッファ |
| staging buffer | ステージングバッファ |
| uniform buffer | ユニフォームバッファ |
| push constant | プッシュ定数 |
| sampler | サンプラー |
| texture | テクスチャ |
| mipmap / mipmaps | ミップマップ |
| multisampling / MSAA | マルチサンプリング / MSAA |
| depth buffer | 深度バッファ |
| stencil | ステンシル |
| synchronization | 同期 |
| semaphore | セマフォ |
| timeline semaphore | タイムラインセマフォ |
| fence | フェンス |
| barrier | バリア |
| memory barrier | メモリバリア |
| image barrier | イメージバリア |
| validation layer | バリデーションレイヤ |
| presentation | プレゼンテーション |
| present | プレゼント（提示） |
| frame in flight | フレームインフライト |
| attachment | アタッチメント |
| subpass | サブパス |
| acceleration structure | アクセラレーション構造 |
| ray tracing | レイトレーシング |
| ray query | レイクエリ |
| binding | バインディング |
| layout transition | レイアウト遷移 |
| host | ホスト |
| device | デバイス |
| extension | 拡張 |
| feature | 機能 |
| swap chain recreation | スワップチェーンの再作成 |

## 翻訳ルール要約

- 本文・見出し・リスト・注釈 → 日本語
- コードブロック・インラインコード → 原文のまま
- `Vk*` / `vk*` / 拡張名・列挙値 → 英語のまま
- `include::` / `image::` / `xref:` のパス → 変更しない
- SPDX / Copyright ヘッダ → 維持
