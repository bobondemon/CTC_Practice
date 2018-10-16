# CTC Forward, Backward and Gradient Practice. Compared with tf.ctc_loss.

Credit 是此篇 [DingKe ipynb](https://github.com/DingKe/ml-tutorial/blob/master/ctc/CTC.ipynb) 的, 他完整呈現了 CTC loss 以及 gradient 的計算, 非常棒!

此筆記加入自己的說明, 並且最後使用 tensorflow 來驗證.

這篇另一個主要目的為改成可以練習的格式 (**#TODO tag**). 因為我相信最好的學習方式是自己造一次輪子, 所以可以的話, 請試著完成把 #TODO tag 的部分做完吧.

我們只專注在 CTC loss 的 forward, backwark and gradient. Decoding 部分請參考原作者的 [ipynb](https://github.com/DingKe/ml-tutorial/blob/master/ctc/CTC.ipynb). 最後使用 tf.nn.ctc_loss and tf.gradients 與我們的計算做對比

1. 完成 CTC_Practice.ipynb #TODO tag
2. 參考 CTC_Practice_Answer.ipynb
