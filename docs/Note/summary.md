## 总结

### 额外知识
1. ​PUT/DELETE 支持：参考网页5和网页6，需启用 HiddenHttpMethodFilter。[11](https://m.php.cn/faq/536439.html) [12](https://blog.csdn.net/qq_47768542/article/details/110872204)
2. ​CSRF 拦截：参考网页3和网页8，禁用 Spring Security 的 CSRF 保护。[13](https://mp.weixin.qq.com/s?__biz=MzAxNjE2MTcyNQ==&mid=2450589323&idx=8&sn=bfa5ed20f991bd40fd811f3d1f4900dc&chksm=8d3e97a0bd3cc9261776fa686f5e3a0662937cc51b8dd7770c7387258a81640cb90ba28e88cd#rd) [14](https://cloud.tencent.com/developer/ask/sof/107605217)
3. ​文件上传限制：参考网页2的配置调整方法。[15](https://www.528045.com/article/9e270ccd39.html)


### 项目感觉
1. 感觉细节方面要多注意，然后依赖问题也很吐血，还有一些兼容性问题。
2. 项目的每个文件，都有起相应的逻辑，按相应的逻辑，分步，有利于项目的观察和维护。


