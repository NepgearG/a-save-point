引き続き資料の構成

コードの構造について、
stock_lstm_2018_gamma.pyを回して実験を行う形になります。

↓

selection

↓

optimization

↓

robo(bayesian_optimizationのコア), predict(LSTMモデルのコア)




LSTM & MTBO
この部分はInherit_nakayamaの中に参照してください。




Transformer
コードについて、先ず原作者のコードは"https://github.com/LongxingTan/Time-series-prediction" で見ることができます。（Transformer以外のモデルにもあります。e.g. GAN）

ただ、ハイパーパラメータの最適化のため、サーバー上の個人ファイルの下のwork/transformer/Time-series-prediction/bo/transformer_bo.pyを参照ください。
optimizerについてのハイパーパラメータは今回よく最適化されないかもしれないので、それについて再実験する価値はあるだと思います。
（β1,β2,ε）
