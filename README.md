# データビリティweb講座（画像処理/大倉担当分）
データビリティweb講座（画像処理/大倉担当分）の演習

## 演習内容
- [サンプル画像・動画](https://drive.google.com/drive/folders/1vRglA8dPsKaqYOO066_IfzJtj18G045p?usp=sharing)

### 第3回分
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fumio125/datability_web/blob/master/3-1_bg_subtraction.ipynb) [背景差分法の実装](3-1_bg_subtraction.ipynb)
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fumio125/datability_web/blob/master/3-2_frame_subtraction.ipynb) [フレーム間差分法の実装](3-2_frame_subtraction.ipynb)
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fumio125/datability_web/blob/master/3-3_subtraction_opencv.ipynb) [統計的背景差分法（OpenCV）](3-3_subtraction_opencv.ipynb)

### 第4回分
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fumio125/datability_web/blob/master/4-1_optical_flow_iterative.ipynb) [繰り返し最適化によるオプティカルフローの実装](4-1_optical_flow_iterative.ipynb)
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fumio125/datability_web/blob/master/4-2_optical_flow_LK.ipynb) [KLT法によるオプティカルフロー（OpenCV）](4-2_optical_flow_LK.ipynb)


### オプション課題用
- (docs/intro.pdf)[環境導入の説明]


## 課題
自分で短い**動画**を撮影し、実際に実行してみましょう。上記のうち、動画を対象とした手法（3-2, 3-3, 4-1, 4-2）から2個以上を選んで実行したり、パラメータを調整したりして、以下について論じてください。
- どういう感じで動画を撮影したらうまくいくか（あるいはうまくいかないか）
- その動画に適したパラメータを、どのように選択したか
- その他、結果の考察（結果画像を貼り付けつつ、どのあたりがうまくいって、どのあたりがうまくいかなかったか、など）

## オプション課題
- もし可能なら、上記の実装などをもとに、自分なりに価値がある「自分が得する」アプリケーションを実装してみましょう。サンプルコードを多少書き換える程度でもOKです。
- 自分以外の誰にも価値がなくても良いです。提出するドキュメント内に、どのように（自分にとって）価値があるのか、そして、そのためにどうしてその方法を使ったのかを含め、論ずるようにしてください。

以上をドキュメント（WordあるいはPDF）にまとめ、okura (at) ist.osaka-u.ac.jp まで送ってください。メールタイトルに「画像処理講座課題」を含めるようにしてください。
