## Crypto Utility 
Specifically shared to assist in Onboarding of Network Participants in ONDC

### Use it as docker container
``docker run -d -p 9001:9001 --name sign proteantech/sign-encrypt:75b90a5-0.0.1-v2 com.nsdl.signing.DemoApplication``



### Use below postman collection to execute the same 

Download [Postman_Collection](/sign-encrypt/Crypto V2.postman_collection.json)
Download [jar](/sign-encrypt/ondc-sign-encrypt.jar)

* Generate Signing Keys
* Generate Encryption Keys
* Encrypt Challenge String
* Decrypt Challenge String
* Sign Request ID
* Verfiy Request ID
