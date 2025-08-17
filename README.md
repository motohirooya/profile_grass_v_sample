# profile_grass_v_sample.model3 
- QGIS,GRASSGIS v.sampleで作る断面図
- https://qiita.com/mooya/items/22d97535048fb1860778

# 同gridとinterval 
- QGISでgrassが利用できるようになったので作り直した
- DEMとpolylineのCRSが異なる場合でも断面図を作成可能に
- Z値を設定→標高断面図で表示可能に。散布図の出力を削除
- 斜距離（DISR_SURF）の属性を追加→処理が重いのでオプションに→斜距離の高速化、オプション削除
- QGIS 3.32.3 / Windows10 で動作確認
- https://qiita.com/mooya/private/a4c84d4c9f9a0b8d8579

## profile_grass_v_sample_grid.model3 
- 無印を踏襲してDEMから作成した格子と断面ラインの交点に頂点を作成
- 「線で分割」を「線の交差」に置き換え高速化

## profile_grass_v_sample_interval.model3 
- 測線ラインを均等分割して頂点を作成
