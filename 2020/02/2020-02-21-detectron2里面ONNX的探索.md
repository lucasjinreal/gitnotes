今天要尝试的东西很简单，就是要尝试看一下detectron2官方写的onnx导出模型，是否值得用，如何用。这个gitnote总是无法push，咋回事，我了个去。

粗略的看了一下，detectron2里面的东西需要master branch的pytorch，同时只支持CPU，不支持GPU。那么这就意味着，这个生成的onnx文件，可能会比较奇怪。

但是不管怎么样，值得尝试一下