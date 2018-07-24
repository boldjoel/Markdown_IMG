根据 equal 生成的 table, True的填第二个的对应数字, False 的对应 False 的数字

```
self.tensor_peaks = tf.where(tf.equal(gaussian_heatMat, max_pooled_in_tensor),
                             gaussian_heatMat,
                             tf.zeros_like(gaussian_heatMat)
                             )
```

