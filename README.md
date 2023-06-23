# ordinalpublicgoods
A list of resources inscribed on bitcoin 


| Library | Inscription ID | Format | Notes | Source | 
| --- | --- | --- | --- | --- |
| Three.js | 2dbdf9ebbec6be793fd16ae9b797c7cf968ab2427166aaf390b90b71778266abi0 | gzip | to extract and use: inscription.split("\n")[32] fflate.strFromU8(fflate.gunzipSync(new Uint8Array(Array.from(atob(d3)).map((char)=>char.charCodeAt(0))))) |  [onchain monkey](https://github.com/metagood/OCM-Dimensions/blob/main/README.md)
| gunzip in fflate | 2dbdf9ebbec6be793fd16ae9b797c7cf968ab2427166aaf390b90b71778266abi0 | gzip | need to do inscription.split("\n")[28] |  [onchain monkey](https://github.com/metagood/OCM-Dimensions/blob/main/README.md)
| p5.js | 255ce0c5a0d8aca39510da72e604ef8837519028827ba7b7f723b7489f3ec3a4i0 | gzip | need to unzip | [onchain monkey](https://github.com/metagood/OCM-Dimensions/blob/main/README.md)
