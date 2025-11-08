# 🌋 Impact Visualization Challenge

## 概要
USGSのライブ地震データを使用し、地震の発生状況や影響を可視化しました。  
この分析を通して「Impact（衝撃・影響）」を感じ取ることを目的としています。

---

## How to Begin
1. `earthquake.ipynb` を開く  
2. Code Cellで以下を実行してUSGSデータを取得  
3. 地図やグラフでImpactを表現  

---

## 可視化内容
- 世界地図上での地震分布（マグニチュードを点の大きさ、深さを色で表現）  
- マグニチュード分布のヒストグラム  
- 特定期間の地震の推移アニメーション（Plotlyなどを利用）

---

## 結果例
<img src="./images/earthquake_map.png" width="600">

---

## 日本語サマリー（約300字）
USGSの地震データを分析し、地震の分布と特徴を可視化した。  
地震は世界各地で毎日のように発生しており、特に太平洋周辺に集中している。  
マグニチュードの分布を確認すると、多くは小規模だが、深発地震も無視できない割合で存在することがわかった。  
この可視化を通して、地震活動の活発さとその「見えない影響」を直感的に理解できた。

---

## 技術
- Python（pandas, matplotlib, geopandas, plotly）
- Jupyter Notebook
- USGS Earthquake API（GeoJSON）

---

## 実行方法
```bash
pip install pandas geopandas plotly requests
jupyter notebook earthquake.ipynb
```
