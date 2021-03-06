# opcua-tools
OPC UA Tools (Unified Architecture)标准工具，包括服务器和客户端，并提供调用接口（服务器和客户端）。

相关lib文件在[www.unified-automation.com](https://www.unified-automation.com/products/server-sdk/java-ua-server-sdk.html)下载

### LICENSE
 - Prosys SDK license [Prosys_OPC_UA_Java_SDK_License](/LICENSE/Prosys_OPC_UA_Java_SDK_License.pdf)

```html
Prosys OPCUA Java SDK is covered by the license terms in 
Prosys_OPC_UA_Java_SDK_License.pdf
```

 - Libraries

```html
The SDK uses the following libraries, which are covered by individual licenses,
available in the following files.
```

|JAR|Library|License file|
|---|---|---|
|Opc.Ua.Stack*.jar|OPC Foundation Java Stack|[LICENSE.opc.ua.stack](/LICENSE/LICENSE.opc.ua.stack)|
|log4j-1.2.17.jar|Apache Logging Services|[LICENSE.apache2.0](/LICENSE/LICENSE.apache2.0)|
|http-*.jar|Apache HttpComponents|[LICENSE.apache2.0](/LICENSE/LICENSE.apache2.0)|
|commons-logging*.jar|Apache Commons Logging Component|[LICENSE.apache2.0](/LICENSE/LICENSE.apache2.0)|
|bc*.jar|Bouncy Castle security|[LICENSE.bouncycastle](/LICENSE/LICENSE.bouncycastle)|
|sc*.jar|Spongy Castle security|[LICENSE.bouncycastle](/LICENSE/LICENSE.bouncycastle)|
|*slf4j*.jar|Simple Logging Facade for Java (SLF4j)|[LICENSE.slf4j](/LICENSE/LICENSE.slf4j)|

-------------------------

## OPC UA Client 使用说明

### 创建一个无证书（NONE）的 OPC UA Client

### 创建一个有证书（SINGN）的 OPC UA Client

### 创建一个有证书（SINGNANDENCRYPT）的 OPC UA Client

## OPC UA Server 使用说明