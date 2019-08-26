# SDK 示例代码使用



### 操作步骤

#### 1.进入[UAPI产品](<https://console.ucloud.cn/uapi/ucloudapi>)，选择需要使用的API。

#### 2.填写相关字段。以 获取弹性IP信息-[DescribeEIP](<https://console.ucloud.cn/uapi/detail?id=DescribeEIP>)为例，查询账户中北京二地域某一项目的EIP资源列表。

  ![](https://static.ucloud.cn/fbb00d85944945a0b247cdb647bcd2ca.png)

#### 3.查看【示例代码】，选择 SDK 语言 ，即可获得该语言的SDK Demo代码

  ![](https://static.ucloud.cn/f5a033ee1a1a4be693b7c37d5c4cff6b.png)

#### 4.获取[账户公私钥](https://console.ucloud.cn/uapi/apikey).

#### 5.替换【示例代码】中的PublicKey及PrivateKey

#### 6.复制代码，并在本地运行，即可获得相应的查询结果。

##### 1）若为**GO SDK Demo**，请参考如下步骤：

**说明**
如需更多帮助，可查看[GO SDK使用文档](<https://github.com/ucloud/ucloud-sdk-go>)




* 保存请求代码为 main.go
* 执行 go mod init main
* 执行 go mod tidy
* go run ./main.go




**说明**

1. 如同时使用 go mod 和 Goland IDE，请在 Settings 中搜索 vgo，并启用 vgo 支持；



2. 如同时使用 go mod 和 GOPATH，注意 go mod init/tidy 不能在 GOPATH 下执行，把项目从 GOPATH 下移出即可



##### 2）若为**Python SDK Demo**，请参考如下步骤：  

**说明**
如需更多帮助，可查看[Python2 SDK使用文档](<https://ucloud.github.io/ucloud-sdk-python2/>)和 [Python3 SDK使用文档](<https://ucloud.github.io/ucloud-sdk-python3/>)



* 保存请求代码为 main.py
* pip install ucloud-sdk-python3 (若使用python2 则执行 pip install ucloud-sdk-python2)
* python ./main.py

