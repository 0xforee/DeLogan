# DeLogan

## How To Use ?
`java DeLogan [test|help] encryptFileOrDirPath [verbose|greedy]`


## 一些问题

1. 如果提示 GZIP 格式问题?    
很大可能是因为秘钥错误，尝试检查秘钥

2. 如果日志解密出很少的内容？    
可以尝试 greedy 贪婪模式，跳过中间的异常区域，最大限度的解析日志文件
