# image-search-system-with-vertex-ai-feature

このリポジトリは、Vertex AI Feature Store & BigQuery に関する3つの Jupyter Notebook を含んでいます。

## ノートブックの説明

このリポジトリには以下のノートブックが含まれています：

1. **[公開用]_vertex_ai_feature_store_get_embeddings.ipynb** - このノートブックではVertex AI Embeddings API を使って抽出した特徴量を BigQuery に格納する処理を書いています。最後の手動同期ジョブは、「[公開用]_vertex_ai_feature_store_setup_onlinestore.ipynb」でオンラインストアが作成されていることを前提にしています。
   
2. **[公開用]_vertex_ai_feature_store_setup_onlinestore.ipynb** - このノートブックはBigQuery をデータソースとした Vertex AI Feature Store のオンラインストアを作成する処理に焦点を当てています。
   
3. **[公開用]_vertex_ai_feature_store_get_nearest_neighbors.ipynb** - ここでは作成されたオンラインストアから、近傍ベクトルをクエリする処理について書いています。
