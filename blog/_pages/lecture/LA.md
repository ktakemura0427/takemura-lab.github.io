---
layout: single
title: Linear Algebra
permalink: /lecture/LA/

sidebar:
  nav: "lecture"

use_math: true
---

# ガイダンス
線形代数は，理工系大学生に必須の初等数学です．理系において学ばないという選択肢はないです．必ず，1年次に履修してください．

- 内容
  1. 教科書・参考書
  2. 学習目標
  3. 評価方法
  4. Python開発環境
  5. スケジュール

---
# 教科書・参考書
<!-- _class: split -->
<div class=ldiv>

日本語版
- **ストラング：教養の線形代数**
  *Gilbert Strang著，松崎公紀，訳*  
  近代科学社，6,160円+税

補足
- スライドを配布する予定だが，理解を深めるため，購入を強く推奨．
- **「線形代数は理工系大学生に必須の初等数学」**，教科書を手元に置くことは無駄ではない！
- 難易度高めの教科書ですが，将来的に役に立ちます．
</div>
<div class=rdiv>

![](https://m.media-amazon.com/images/I/71YhOj4qblL._SY522_.jpg)<span class ="img-caption">図1 : 教科書</span>
</div>



---
# 学習目標
### リベラルアーツコース(他学科向け)では
1. **行列の基本的な計算**  
   - 逆行列，固有値・固有ベクトル，行列式が計算できる。
2. **行列を用いた工学的応用**  
   - 最小二乗法，主成分分析が理解できる。
### コンピュータサイエンスコース(DA向け)では
1. **リベラルアーツコースの内容**に加え
2. **Pythonを用いたプログラミング**  
   - 行列演算をプログラムで実装できることを目指す。  

---
# 評価方法
**100点満点**
- **:レポート50%**
  - **遅延は一切認めません**
  - **指定の用紙を使用すること**
  - ソフトウェアを使用して**A4用紙に整形されたPDFファイル**をOpenLMSに提出．
  - 直接PDFに記入してもOK．但し，OpenLMS上で，解答が見えるか確認すること．
- **試験50%**
  - 中間試験 25%
  - 期末試験 25%

---
# Pythonの開発環境
- Python3(バージョン３系)，venvで仮想環境の構築を推奨
- 必要なモジュール(numpy, matplotlib)はpipで管理
- エディタ, 統合開発環境
なんでも良いが，PyCharm，VSCodeが主流
- 環境構築が難しい場合(非推奨)
• Google Colaboratory(https://colab.research.google.com)

---
# ベクトルの線形結合
**列ベクトルと転置ベクトル**

$$

\mathbf{v} =
\begin{bmatrix}
v_1\\
v_2
\end{bmatrix}=\begin{bmatrix} v_1 & v_2 \end{bmatrix}^\top

$$

    
