# interchange-station-for-file
As a station where files can be stored temporarily.

加密过程：
1）将待加密的目录拷贝到./cryptography/target。
2）运行./cryptography/cryptography.bat，并选择加密选项。
3）加密的结果拷贝到./files，增量提交。

解密过程：
1）把私钥rsa.private放到./cryptography/keypair。
2）将待解密的目录拷贝到./cryptography/target。
3）运行./cryptography/cryptography.bat，并选择解密选项。
