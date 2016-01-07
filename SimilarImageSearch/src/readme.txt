相似图片搜索的原理
你可以用一张图片，搜索互联网上所有与它相似的图片。

关键技术："感知哈希算法"（Perceptual hash algorithm）
它的作用是对每张图片生成一个"指纹"（fingerprint）字符串
然后比较不同图片的指纹。结果越接近，就说明图片越相似。


测试入口：SimilarImageSearch.java