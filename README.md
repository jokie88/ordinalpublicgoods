# Ordinal Public goods
A list of resources (js libraries, etc) inscribed on bitcoin. Feel free to create a pull request to add to it. Its just text so anyone can do it!

Caution: These libraries are NOT vetted and may contain issues/malware. Please be cautious when opening and using these files and look at the source. 

| Library | Inscription ID | Format | Notes | Source | 
| --- | --- | --- | --- | --- |
| Three.js | 2dbdf9ebbec6be793fd16ae9b797c7cf968ab2427166aaf390b90b71778266abi0 | gzip | to extract and use: inscription.split("\n")[32] fflate.strFromU8(fflate.gunzipSync(new Uint8Array(Array.from(atob(d3)).map((char)=>char.charCodeAt(0))))) |  [onchain monkey](https://github.com/metagood/OCM-Dimensions/blob/main/README.md)
| gunzip in fflate | 2dbdf9ebbec6be793fd16ae9b797c7cf968ab2427166aaf390b90b71778266abi0 | gzip | need to do inscription.split("\n")[28] |  [onchain monkey](https://github.com/metagood/OCM-Dimensions/blob/main/README.md)
| p5.js | 255ce0c5a0d8aca39510da72e604ef8837519028827ba7b7f723b7489f3ec3a4i0 | gzip | need to unzip | [onchain monkey](https://github.com/metagood/OCM-Dimensions/blob/main/README.md)
| html2canvas 1.4.1 | be2585187c2e016b654ecc1f207fa73c38e55eee404cdf709346c4511689d24ai0 | none | | [king bootoshi](https://twitter.com/KingBootoshi/status/1670534828922400768?s=20)
|jquery 3.7.0 | 773e4865bcf3084e6d6ee5d49136fb5f7071d4c050ec4aeeaeb9c6d24fea5fc1i0 | none | | [inscribed.space](https://twitter.com/InscribedSpace/status/1671541360703205381?s=20)
|fflate 0.8.0 | f815bd5c566c6e46de5cdb6ccb3a7043c63deeba61f4234baea84b602b0d4440i0 | none | | [harry.xbt](https://twitter.com/hbeckeri/status/1671917397832335361?s=20)
| Google model viewer 3.1.1 | 547a6709441bc5c9d206150ce5fb7605c28a90c46bd6e4330c4420cb41477aeai0 | none | Usage:
<script type="module" src="/content/547a6709441bc5c9d206150ce5fb7605c28a90c46bd6e4330c4420cb41477aeai0"></script | [harry.xbt](https://twitter.com/hbeckeri/status/1671917397832335361?s=20)
