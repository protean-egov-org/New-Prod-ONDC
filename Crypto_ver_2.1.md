## Crypto Utility 
Specifically shared to assist in Onboarding of Network Participants in ONDC

### Option 1 to use it as docker container
``docker run -d -p 9001:9001 --name sign proteantech/sign-encrypt:75b90a5-0.0.1-v2 com.nsdl.signing.DemoApplication``

### Option 2 to use it as jar 
Download [jar](/sign-encrypt/ondc-sign-encrypt.jar) and execute it as ```java -Dserver.port=8000 -jar beckn-sign-encrypt-0.0.1 ```

### Use below postman collection to execute the same 

[![Run in Postman](https://run.pstmn.io/button.svg)](https://god.gw.postman.com/run-collection/4458383-4e8390fd-1e4a-4f83-83d2-52f7f2264637?action=collection%2Ffork&collection-url=entityId%3D4458383-4e8390fd-1e4a-4f83-83d2-52f7f2264637%26entityType%3Dcollection%26workspaceId%3D7aec3395-f6dd-4231-b557-4406b610a970)

* Generate Signing Keys
* Generate Encryption Keys
* Encrypt Challenge String
* Decrypt Challenge String
* Sign Request ID
* Verfiy Request ID
