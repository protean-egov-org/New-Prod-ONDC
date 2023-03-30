## Crypto Utility 
Specifically shared to assist in Onboarding of Network Participants in ONDC

### Use it as docker container
``docker run -d -p 9001:9001 --name sign proteantech/sign-encrypt:75b90a5-0.0.1-v2 com.nsdl.signing.DemoApplication``



### Use below postman collection to execute the same 


<div class="postman-run-button"
data-postman-action="collection/fork"
data-postman-var-1="21537714-5c85c5b7-09b9-4e50-ab39-000ee78f91e6"
data-postman-collection-url="entityId=21537714-5c85c5b7-09b9-4e50-ab39-000ee78f91e6&entityType=collection&workspaceId=53a76419-024e-450d-a188-c32507739a55"></div>
<script type="text/javascript">
  (function (p,o,s,t,m,a,n) {
    !p[s] && (p[s] = function () { (p[t] || (p[t] = [])).push(arguments); });
    !o.getElementById(s+t) && o.getElementsByTagName("head")[0].appendChild((
      (n = o.createElement("script")),
      (n.id = s+t), (n.async = 1), (n.src = m), n
    ));
  }(window, document, "_pm", "PostmanRunObject", "https://run.pstmn.io/button.js"));
</script>


[![Run in Postman](https://run.pstmn.io/button.svg)](https://god.gw.postman.com/run-collection/21537714-5c85c5b7-09b9-4e50-ab39-000ee78f91e6?action=collection%2Ffork&collection-url=entityId=21537714-5c85c5b7-09b9-4e50-ab39-000ee78f91e6&entityType=collection&workspaceId=53a76419-024e-450d-a188-c32507739a55)


* Generate Signing Keys
* Generate Encryption Keys
* Encrypt Challenge String
* Decrypt Challenge String
* Sign Request ID
* Verfiy Request ID
