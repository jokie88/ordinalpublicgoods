# Ordinal Public Goods
A list of js libraries and other resources inscribed on bitcoin. Use it to lower the cost of your inscriptions. 

> **Warning**
> These libraries are NOT vetted. Be cautious when opening and using these inscriptions. 

| Library | Inscription ID | Format | Notes | Source | 
| --- | --- | --- | --- | --- |
|fflate 0.8.0 | f815bd5c566c6e46de5cdb6ccb3a7043c63deeba61f4234baea84b602b0d4440i0 | none | | [harry.xbt](https://twitter.com/hbeckeri/status/1671917397832335361?s=20)
| html2canvas 1.4.1 | be2585187c2e016b654ecc1f207fa73c38e55eee404cdf709346c4511689d24ai0 | none | | [king bootoshi](https://twitter.com/KingBootoshi/status/1670534828922400768?s=20)
|jquery 3.7.0 | 773e4865bcf3084e6d6ee5d49136fb5f7071d4c050ec4aeeaeb9c6d24fea5fc1i0 | none | | [inscribed.space](https://twitter.com/InscribedSpace/status/1671541360703205381?s=20)
| Google model viewer 3.1.1 | 547a6709441bc5c9d206150ce5fb7605c28a90c46bd6e4330c4420cb41477aeai0 | none | see tweet for useage | [harry.xbt](https://twitter.com/hbeckeri/status/1671917397832335361?s=20)
| Apache 2.0 | 3a4575b2a8fe6e7968146f290d494c2346d40ff692314050babcaa7268347f4bi0 | none | untested |  inscribed.space
| Moment.js 2.29.1 | b90b4516ea1a0b882e67387eb4f3e5def0307704b046e8ef98c5e72092c47eedi0 | none | | inscribed.space 
| Bootstrap 5.3.0 | 3bcfdc4e97209ecaaab06705b52ba6b7fc9d1cee77404ac15e655ce691a44654i0 | none | | inscribed.space
| gunzip in fflate | 2dbdf9ebbec6be793fd16ae9b797c7cf968ab2427166aaf390b90b71778266abi0 | gzip | need to do inscription.split("\n")[28] |  [onchain monkey](https://github.com/metagood/OCM-Dimensions/blob/main/README.md)
| Three.js | 2dbdf9ebbec6be793fd16ae9b797c7cf968ab2427166aaf390b90b71778266abi0 | gzip | to extract and use: inscription.split("\n")[32] fflate.strFromU8(fflate.gunzipSync(new Uint8Array(Array.from(atob(d3)).map((char)=>char.charCodeAt(0))))) |  [onchain monkey](https://github.com/metagood/OCM-Dimensions/blob/main/README.md)
| p5.js 1.6.0 | 255ce0c5a0d8aca39510da72e604ef8837519028827ba7b7f723b7489f3ec3a4i0 | gzip | see [example](/examples/p5js.html) | [onchain monkey](https://github.com/metagood/OCM-Dimensions/blob/main/README.md)
| matter0js 0.19.0 | 9d567e6ef8bd6b13458cc67cc5e8339395a4433e45db4554ff83c88a5df8bae2i0 | none | | [found on ord.io](https://www.ord.io/11774132)
| webGL-fluid-simulation | 3af8500b444c7f589fca666fe317e1f95c7226d49dc23f8a4b86093f01f3e7adi0 | none | | [found on ord.io](https://www.ord.io/11846310)
| axios min js | 6b81993428a217a341ffd68f3b3aa3664b2cfc674d57aad0d3b6daa0f125b821i0 | none | | [found on ord.io](https://www.ord.io/12399396)
| tone.js 14.7.77? | 44740a1f30efb247ef41de3355133e12d6f58ab4dc8a3146648e2249fa9c6a39i0 | none | | [found on ord.io](https://www.ord.io/13316104)
| cropper.js 1.5.6 | b00cfb90d712ab0c5fd80580629c1910538859e55b9a9d6306f734420f3721f5i0 | none | | [found on ord.io](https://www.ord.io/13345027)
| popper.js/core 2.11.8 | dcb205828669fece54d4040224190838bbe22b6d137ae9fc38c4b42f0777148ai0 | none | | [found on ord.io](https://www.ord.io/11821277)

## Contribute
Know of a library that isn't here yet? Edit this page by clicking the pencil icon!
