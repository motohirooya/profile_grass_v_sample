# profile_grass_v_sample.model3 
- QGIS,GRASSGIS v.sampleで作る断面図
- https://qiita.com/mooya/items/22d97535048fb1860778

# profile_grass_v_sample2.model3 
- QGISでgrassが利用できるようになったので作り直した
-- https://github.com/qgis/QGIS/pull/49226
- DEMとpolylineのCRSが異なる場合でも断面図を作成可能に
- Z値を設定→標高断面図で表示可能に。散布図の出力を削除
- 点の作成方法を間隔による高密度化→頂点の抽出に変更
- 斜距離（DISR_SURF）の属性を追加
