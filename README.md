# Awesome CVE PoC [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://cve.mitre.org/images/cvebanner.gif" align="right" width="70">](https://cve.mitre.org/index.html)

> ✍️ A curated list of CVE PoCs.

Here is a collection about Proof of Concepts of Common Vulnerabilities and Exposures, and you may also want to check out [awesome-web-security](https://github.com/qazbnm456/awesome-web-security).

*Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.*

---

<p align="center"><b>🌈 This repo is full of PoCs for CVEs.</b></p>

---

If you enjoy this awesome list and would like to support it, check out my [Patreon](https://www.patreon.com/boik) page :)<br>Also, don't forget to check out my [repos](https://github.com/qazbnm456) 🐾 or say *hi* on my [Twitter](https://twitter.com/qazbnm456)!

## Contents

- [CVE-2011-2856](#cve-2011-2856)
- [CVE-2011-3243](#cve-2011-3243)
- [CVE-2013-2618](#cve-2013-2618)
- [CVE-2013-6632](#cve-2013-6632)
- [CVE-2014-1701](#cve-2014-1701)
- [CVE-2014-1705](#cve-2014-1705)
- [CVE-2014-1747](#cve-2014-1747)
- [CVE-2014-3176](#cve-2014-3176)
- [CVE-2014-6332](#cve-2014-6332)
- [CVE-2014-7927](#cve-2014-7927)
- [CVE-2014-7928](#cve-2014-7928)
- [CVE-2015-0072](#cve-2015-0072)
- [CVE-2015-0235](#cve-2015-0235)
- [CVE-2015-0240](#cve-2015-0240)
- [CVE-2015-1233](#cve-2015-1233)
- [CVE-2015-1242](#cve-2015-1242)
- [CVE-2015-1268](#cve-2015-1268)
- [CVE-2015-1635](#cve-2015-1635)
- [CVE-2015-1830](#cve-2015-1830)
- [CVE-2015-2177](#cve-2015-2177)
- [CVE-2015-3306](#cve-2015-3306)
- [CVE-2015-5119](#cve-2015-5119)
- [CVE-2015-5254](#cve-2015-5254)
- [CVE-2015-5531](#cve-2015-5531)
- [CVE-2015-6086](#cve-2015-6086)
- [CVE-2015-6755](#cve-2015-6755)
- [CVE-2015-6764](#cve-2015-6764)
- [CVE-2015-6769](#cve-2015-6769)
- [CVE-2015-6770](#cve-2015-6770)
- [CVE-2015-6771](#cve-2015-6771)
- [CVE-2015-7450](#cve-2015-7450)
- [CVE-2015-7501](#cve-2015-7501)
- [CVE-2015-7545](#cve-2015-7545)
- [CVE-2015-8584](#cve-2015-8584)
- [CVE-2016-0040](#cve-2016-0040)
- [CVE-2016-0450](#cve-2016-0450)
- [CVE-2016-0451](#cve-2016-0451)
- [CVE-2016-0728](#cve-2016-0728)
- [CVE-2016-0792](#cve-2016-0792)
- [CVE-2016-0856](#cve-2016-0856)
- [CVE-2016-1631](#cve-2016-1631)
- [CVE-2016-1646](#cve-2016-1646)
- [CVE-2016-1653](#cve-2016-1653)
- [CVE-2016-1665](#cve-2016-1665)
- [CVE-2016-1667](#cve-2016-1667)
- [CVE-2016-1668](#cve-2016-1668)
- [CVE-2016-1669](#cve-2016-1669)
- [CVE-2016-1672](#cve-2016-1672)
- [CVE-2016-1673](#cve-2016-1673)
- [CVE-2016-1674](#cve-2016-1674)
- [CVE-2016-1675](#cve-2016-1675)
- [CVE-2016-1676](#cve-2016-1676)
- [CVE-2016-1677](#cve-2016-1677)
- [CVE-2016-1688](#cve-2016-1688)
- [CVE-2016-1697](#cve-2016-1697)
- [CVE-2016-1710](#cve-2016-1710)
- [CVE-2016-1711](#cve-2016-1711)
- [CVE-2016-1779](#cve-2016-1779)
- [CVE-2016-1857](#cve-2016-1857)
- [CVE-2016-1910](#cve-2016-1910)
- [CVE-2016-2384](#cve-2016-2384)
- [CVE-2016-2386](#cve-2016-2386)
- [CVE-2016-2388](#cve-2016-2388)
- [CVE-2016-3087](#cve-2016-3087)
- [CVE-2016-3088](#cve-2016-3088)
- [CVE-2016-3309](#cve-2016-3309)
- [CVE-2016-3714](#cve-2016-3714)
- [CVE-2016-3371](#cve-2016-3371)
- [CVE-2016-3386](#cve-2016-3386)
- [CVE-2016-4338](#cve-2016-4338)
- [CVE-2016-4437](#cve-2016-4437)
- [CVE-2016-4622](#cve-2016-4622)
- [CVE-2016-4734](#cve-2016-4734)
- [CVE-2016-4971](#cve-2016-4971)
- [CVE-2016-5129](#cve-2016-5129)
- [CVE-2016-5172](#cve-2016-5172)
- [CVE-2016-5195](#cve-2016-5195)
- [CVE-2016-5198](#cve-2016-5198)
- [CVE-2016-5200](#cve-2016-5200)
- [CVE-2016-5204](#cve-2016-5204)
- [CVE-2016-5207](#cve-2016-5207)
- [CVE-2016-5208](#cve-2016-5208)
- [CVE-2016-5346](#cve-2016-5346)
- [CVE-2016-5610](#cve-2016-5610)
- [CVE-2016-5611](#cve-2016-5611)
- [CVE-2016-5734](#cve-2016-5734)
- [CVE-2016-6210](#cve-2016-6210)
- [CVE-2016-6277](#cve-2016-6277)
- [CVE-2016-6415](#cve-2016-6415)
- [CVE-2016-6662](#cve-2016-6662)
- [CVE-2016-6700](#cve-2016-6700)
- [CVE-2016-6702](#cve-2016-6702)
- [CVE-2016-6762](#cve-2016-6762)
- [CVE-2016-6787](#cve-2016-6787)
- [CVE-2016-7124](#cve-2016-7124)
- [CVE-2016-7189](#cve-2016-7189)
- [CVE-2016-7190](#cve-2016-7190)
- [CVE-2016-7194](#cve-2016-7194)
- [CVE-2016-7200](#cve-2016-7200)
- [CVE-2016-7201](#cve-2016-7201)
- [CVE-2016-7202](#cve-2016-7202)
- [CVE-2016-7203](#cve-2016-7203)
- [CVE-2016-7240](#cve-2016-7240)
- [CVE-2016-7241](#cve-2016-7241)
- [CVE-2016-7255](#cve-2016-7255)
- [CVE-2016-7286](#cve-2016-7286)
- [CVE-2016-7287](#cve-2016-7287)
- [CVE-2016-7288](#cve-2016-7288)
- [CVE-2016-7547](#cve-2016-7547)
- [CVE-2016-7552](#cve-2016-7552)
- [CVE-2016-8413](#cve-2016-8413)
- [CVE-2016-8477](#cve-2016-8477)
- [CVE-2016-8584](#cve-2016-8584)
- [CVE-2016-8585](#cve-2016-8585)
- [CVE-2016-8586](#cve-2016-8586)
- [CVE-2016-8587](#cve-2016-8587)
- [CVE-2016-8588](#cve-2016-8588)
- [CVE-2016-8589](#cve-2016-8589)
- [CVE-2016-8590](#cve-2016-8590)
- [CVE-2016-8591](#cve-2016-8591)
- [CVE-2016-8592](#cve-2016-8592)
- [CVE-2016-8593](#cve-2016-8593)
- [CVE-2016-9651](#cve-2016-9651)
- [CVE-2016-9793](#cve-2016-9793)
- [CVE-2016-10033](#cve-2016-10033)
- [CVE-2016-10191](#cve-2016-10191)
- [CVE-2016-10277](#cve-2016-10277)
- [CVE-2016-10370](#cve-2016-10370)
- [CVE-2017-0015](#cve-2017-0015)
- [CVE-2017-0037](#cve-2017-0037)
- [CVE-2017-0059](#cve-2017-0059)
- [CVE-2017-0070](#cve-2017-0070)
- [CVE-2017-0071](#cve-2017-0071)
- [CVE-2017-0134](#cve-2017-0134)
- [CVE-2017-0135](#cve-2017-0135)
- [CVE-2017-0141](#cve-2017-0141)
- [CVE-2017-0143](#cve-2017-0143)
- [CVE-2017-0144](#cve-2017-0144)
- [CVE-2017-0145](#cve-2017-0145)
- [CVE-2017-0146](#cve-2017-0146)
- [CVE-2017-0147](#cve-2017-0147)
- [CVE-2017-0148](#cve-2017-0148)
- [CVE-2017-0199](#cve-2017-0199)
- [CVE-2017-0213](#cve-2017-0213)
- [CVE-2017-0234](#cve-2017-0234)
- [CVE-2017-0236](#cve-2017-0236)
- [CVE-2017-0263](#cve-2017-0263)
- [CVE-2017-0283](#cve-2017-0283)
- [CVE-2017-0290](#cve-2017-0290)
- [CVE-2017-0392](#cve-2017-0392)
- [CVE-2017-0474](#cve-2017-0474)
- [CVE-2017-0475](#cve-2017-0475)
- [CVE-2017-0497](#cve-2017-0497)
- [CVE-2017-0521](#cve-2017-0521)
- [CVE-2017-0531](#cve-2017-0531)
- [CVE-2017-0541](#cve-2017-0541)
- [CVE-2017-0548](#cve-2017-0548)
- [CVE-2017-0576](#cve-2017-0576)
- [CVE-2017-0641](#cve-2017-0641)
- [CVE-2017-0678](#cve-2017-0678)
- [CVE-2017-0714](#cve-2017-0714)
- [CVE-2017-0718](#cve-2017-0718)
- [CVE-2017-0719](#cve-2017-0719)
- [CVE-2017-0720](#cve-2017-0720)
- [CVE-2017-0722](#cve-2017-0722)
- [CVE-2017-0745](#cve-2017-0745)
- [CVE-2017-0758](#cve-2017-0758)
- [CVE-2017-0760](#cve-2017-0760)
- [CVE-2017-0761](#cve-2017-0761)
- [CVE-2017-0764](#cve-2017-0764)
- [CVE-2017-0776](#cve-2017-0776)
- [CVE-2017-0777](#cve-2017-0777)
- [CVE-2017-0778](#cve-2017-0778)
- [CVE-2017-0781](#cve-2017-0781)
- [CVE-2017-0785](#cve-2017-0785)
- [CVE-2017-0813](#cve-2017-0813)
- [CVE-2017-0814](#cve-2017-0814)
- [CVE-2017-0820](#cve-2017-0820)
- [CVE-2017-1082](#cve-2017-1082)
- [CVE-2017-1083](#cve-2017-1083)
- [CVE-2017-1084](#cve-2017-1084)
- [CVE-2017-1085](#cve-2017-1085)
- [CVE-2017-2363](#cve-2017-2363)
- [CVE-2017-2364](#cve-2017-2364)
- [CVE-2017-2365](#cve-2017-2365)
- [CVE-2017-2367](#cve-2017-2367)
- [CVE-2017-2416](#cve-2017-2416)
- [CVE-2017-2419](#cve-2017-2419)
- [CVE-2017-2426](#cve-2017-2426)
- [CVE-2017-2442](#cve-2017-2442)
- [CVE-2017-2445](#cve-2017-2445)
- [CVE-2017-2446](#cve-2017-2446)
- [CVE-2017-2447](#cve-2017-2447)
- [CVE-2017-2460](#cve-2017-2460)
- [CVE-2017-2464](#cve-2017-2464)
- [CVE-2017-2468](#cve-2017-2468)
- [CVE-2017-2475](#cve-2017-2475)
- [CVE-2017-2479](#cve-2017-2479)
- [CVE-2017-2480](#cve-2017-2480)
- [CVE-2017-2491](#cve-2017-2491)
- [CVE-2017-2493](#cve-2017-2493)
- [CVE-2017-2504](#cve-2017-2504)
- [CVE-2017-2508](#cve-2017-2508)
- [CVE-2017-2510](#cve-2017-2510)
- [CVE-2017-2521](#cve-2017-2521)
- [CVE-2017-2528](#cve-2017-2528)
- [CVE-2017-2531](#cve-2017-2531)
- [CVE-2017-2536](#cve-2017-2536)
- [CVE-2017-2540](#cve-2017-2540)
- [CVE-2017-2541](#cve-2017-2540)
- [CVE-2017-2547](#cve-2017-2547)
- [CVE-2017-2636](#cve-2017-2636)
- [CVE-2017-2641](#cve-2017-2641)
- [CVE-2017-3066](#cve-2017-3066)
- [CVE-2017-3248](#cve-2017-3248)
- [CVE-2017-3506](#cve-2017-3506)
- [CVE-2017-3599](#cve-2017-3599)
- [CVE-2017-3629](#cve-2017-3629)
- [CVE-2017-3630](#cve-2017-3630)
- [CVE-2017-3631](#cve-2017-3631)
- [CVE-2017-3881](#cve-2017-3881)
- [CVE-2017-4901](#CVE-2017-4901)
- [CVE-2017-4914](#cve-2017-4914)
- [CVE-2017-4915](#cve-2017-4915)
- [CVE-2017-4918](#cve-2017-4918)
- [CVE-2017-4933](#cve-2017-4933)
- [CVE-2017-4946](#cve-2017-4946)
- [CVE-2017-4971](#cve-2017-4971)
- [CVE-2017-5007](#cve-2017-5007)
- [CVE-2017-5008](#cve-2017-5008)
- [CVE-2017-5010](#cve-2017-5010)
- [CVE-2017-5030](#cve-2017-5030)
- [CVE-2017-5033](#cve-2017-5033)
- [CVE-2017-5040](#cve-2017-5040)
- [CVE-2017-5053](#cve-2017-5053)
- [CVE-2017-5070](#cve-2017-5070)
- [CVE-2017-5071](#cve-2017-5071)
- [CVE-2017-5088](#cve-2017-5088)
- [CVE-2017-5098](#cve-2017-5098)
- [CVE-2017-5115](#cve-2017-5115)
- [CVE-2017-5116](#cve-2017-5116)
- [CVE-2017-5121](#cve-2017-5121)
- [CVE-2017-5122](#cve-2017-5122)
- [CVE-2017-5123](#cve-2017-5123)
- [CVE-2017-5124](#cve-2017-5124)
- [CVE-2017-5126](#cve-2017-5126)
- [CVE-2017-5127](#cve-2017-5127)
- [CVE-2017-5128](#cve-2017-5128)
- [CVE-2017-5129](#cve-2017-5129)
- [CVE-2017-5133](#cve-2017-5133)
- [CVE-2017-5135](#cve-2017-5135)
- [CVE-2017-5622](#cve-2017-5622)
- [CVE-2017-5624](#cve-2017-5624)
- [CVE-2017-5626](#cve-2017-5626)
- [CVE-2017-5638](#cve-2017-5638)
- [CVE-2017-5641](#cve-2017-5641)
- [CVE-2017-5689](#cve-2017-5689)
- [CVE-2017-5715](#cve-2017-5715)
- [CVE-2017-5753](#cve-2017-5753)
- [CVE-2017-5754](#cve-2017-5754)
- [CVE-2017-5891](#cve-2017-5891)
- [CVE-2017-5892](#cve-2017-5892)
- [CVE-2017-5948](#cve-2017-5948)
- [CVE-2017-6008](#cve-2017-6008)
- [CVE-2017-6074](#cve-2017-6074)
- [CVE-2017-6178](#cve-2017-6178)
- [CVE-2017-6198](#cve-2017-6198)
- [CVE-2017-6199](#cve-2017-6199)
- [CVE-2017-6200](#cve-2017-6200)
- [CVE-2017-6201](#cve-2017-6201)
- [CVE-2017-6326](#cve-2017-6326)
- [CVE-2017-6327](#cve-2017-6327)
- [CVE-2017-6736](#cve-2017-6736)
- [CVE-2017-6980](#cve-2017-6980)
- [CVE-2017-6984](#cve-2017-6984)
- [CVE-2017-7037](#cve-2017-7037)
- [CVE-2017-7056](#cve-2017-7056)
- [CVE-2017-7061](#cve-2017-7061)
- [CVE-2017-7089](#cve-2017-7089)
- [CVE-2017-7092](#cve-2017-7092)
- [CVE-2017-7115](#cve-2017-7115)
- [CVE-2017-7117](#cve-2017-7117)
- [CVE-2017-7150](#cve-2017-7150)
- [CVE-2017-7219](#cve-2017-7219)
- [CVE-2017-7269](#cve-2017-7269)
- [CVE-2017-7279](#cve-2017-7279)
- [CVE-2017-7280](#cve-2017-7280)
- [CVE-2017-7281](#cve-2017-7281)
- [CVE-2017-7281](#cve-2017-7282)
- [CVE-2017-7281](#cve-2017-7283)
- [CVE-2017-7293](#cve-2017-7293)
- [CVE-2017-7308](#cve-2017-7308)
- [CVE-2017-7344](#cve-2017-7344)
- [CVE-2017-7442](#cve-2017-7442)
- [CVE-2017-7494](#cve-2017-7494)
- [CVE-2017-7504](#cve-2017-7504)
- [CVE-2017-7525](#cve-2017-7525)
- [CVE-2017-7529](#cve-2017-7529)
- [CVE-2017-7533](#cve-2017-7533)
- [CVE-2017-8046](#cve-2017-8046)
- [CVE-2017-8291](#cve-2017-8291)
- [CVE-2017-8295](#cve-2017-8295)
- [CVE-2017-8386](#cve-2017-8386)
- [CVE-2017-8464](#cve-2017-8464)
- [CVE-2017-8514](#cve-2017-8514)
- [CVE-2017-8543](#cve-2017-8543)
- [CVE-2017-8548](#cve-2017-8548)
- [CVE-2017-8570](#cve-2017-8570)
- [CVE-2017-8601](#cve-2017-8601)
- [CVE-2017-8625](#cve-2017-8625)
- [CVE-2017-8634](#cve-2017-8634)
- [CVE-2017-8636](#cve-2017-8636)
- [CVE-2017-8640](#cve-2017-8640)
- [CVE-2017-8645](#cve-2017-8645)
- [CVE-2017-8646](#cve-2017-8646)
- [CVE-2017-8656](#cve-2017-8656)
- [CVE-2017-8670](#cve-2017-8670)
- [CVE-2017-8671](#cve-2017-8671)
- [CVE-2017-8729](#cve-2017-8729)
- [CVE-2017-8740](#cve-2017-8740)
- [CVE-2017-8751](#cve-2017-8751)
- [CVE-2017-8755](#cve-2017-8755)
- [CVE-2017-8759](#cve-2017-8759)
- [CVE-2017-8817](#cve-2017-8817)
- [CVE-2017-8850](#cve-2017-8850)
- [CVE-2017-8851](#cve-2017-8851)
- [CVE-2017-8877](#cve-2017-8877)
- [CVE-2017-8878](#cve-2017-8878)
- [CVE-2017-8890](#cve-2017-8890)
- [CVE-2017-8912](#cve-2017-8912)
- [CVE-2017-8917](#cve-2017-8917)
- [CVE-2017-9417](#cve-2017-9417)
- [CVE-2017-9791](#cve-2017-9791)
- [CVE-2017-9798](#cve-2017-9798)
- [CVE-2017-9805](#cve-2017-9805)
- [CVE-2017-9822](#cve-2017-9822)
- [CVE-2017-9948](#cve-2017-9948)
- [CVE-2017-9993](#cve-2017-9993)
- [CVE-2017-10271](#cve-2017-10271)
- [CVE-2017-10661](#cve-2017-10661)
- [CVE-2017-11105](#cve-2017-11105)
- [CVE-2017-11120](#cve-2017-11120)
- [CVE-2017-11421](#cve-2017-11421)
- [CVE-2017-11444](#cve-2017-11444)
- [CVE-2017-11610](#cve-2017-11610)
- [CVE-2017-11764](#cve-2017-11764)
- [CVE-2017-11774](#cve-2017-11774)
- [CVE-2017-11779](#cve-2017-11779)
- [CVE-2017-11793](#cve-2017-11793)
- [CVE-2017-11799](#cve-2017-11799)
- [CVE-2017-11802](#cve-2017-11802)
- [CVE-2017-11809](#cve-2017-11809)
- [CVE-2017-11811](#cve-2017-11811)
- [CVE-2017-11812](#CVE-2017-11812)
- [CVE-2017-11839](#cve-2017-11839)
- [CVE-2017-11840](#cve-2017-11840)
- [CVE-2017-11841](#cve-2017-11841)
- [CVE-2017-11855](#cve-2017-11855)
- [CVE-2017-11861](#cve-2017-11861)
- [CVE-2017-11870](#cve-2017-11870)
- [CVE-2017-11873](#cve-2017-11873)
- [CVE-2017-11882](#cve-2017-11882)
- [CVE-2017-11890](#cve-2017-11890)
- [CVE-2017-11893](#cve-2017-11893)
- [CVE-2017-11903](#cve-2017-11903)
- [CVE-2017-11906](#cve-2017-11906)
- [CVE-2017-11907](#cve-2017-11907)
- [CVE-2017-11909](#cve-2017-11909)
- [CVE-2017-11911](#cve-2017-11911)
- [CVE-2017-11914](#cve-2017-11914)
- [CVE-2017-11918](#cve-2017-11918)
- [CVE-2017-12097](#cve-2017-12097)
- [CVE-2017-12098](#cve-2017-12098)
- [CVE-2017-12149](#cve-2017-12149)
- [CVE-2017-12542](#cve-2017-12542)
- [CVE-2017-12581](#cve-2017-12581)
- [CVE-2017-12611](#cve-2017-12611)
- [CVE-2017-12615](#cve-2017-12615)
- [CVE-2017-12617](#cve-2017-12617)
- [CVE-2017-13089](#cve-2017-13089)
- [CVE-2017-13156](#cve-2017-13156)
- [CVE-2017-13253](#cve-2017-13253)
- [CVE-2017-13258](#cve-2017-13258)
- [CVE-2017-13260](#cve-2017-13260)
- [CVE-2017-13261](#cve-2017-13261)
- [CVE-2017-13262](#cve-2017-13262)
- [CVE-2017-13791](#cve-2017-13791)
- [CVE-2017-13792](#cve-2017-13792)
- [CVE-2017-14135](#cve-2017-14135)
- [CVE-2017-14335](#cve-2017-14335)
- [CVE-2017-14491](#cve-2017-14491)
- [CVE-2017-14492](#cve-2017-14492)
- [CVE-2017-14493](#cve-2017-14493)
- [CVE-2017-14494](#cve-2017-14494)
- [CVE-2017-14495](#cve-2017-14495)
- [CVE-2017-14496](#cve-2017-14496)
- [CVE-2017-14904](#cve-2017-14904)
- [CVE-2017-15277](#cve-2017-15277)
- [CVE-2017-15303](#cve-2017-15303)
- [CVE-2017-15361](#cve-2017-15361)
- [CVE-2017-15388](#cve-2017-15388)
- [CVE-2017-15396](#cve-2017-15396)
- [CVE-2017-15398](#cve-2017-15398)
- [CVE-2017-15399](#cve-2017-15399)
- [CVE-2017-15401](#cve-2017-15401)
- [CVE-2017-15411](#cve-2017-15411)
- [CVE-2017-15412](#cve-2017-15412)
- [CVE-2017-15415](#cve-2017-15415)
- [CVE-2017-15428](#cve-2017-15428)
- [CVE-2017-15613](#cve-2017-15613)
- [CVE-2017-15614](#cve-2017-15614)
- [CVE-2017-15615](#cve-2017-15615)
- [CVE-2017-15616](#cve-2017-15616)
- [CVE-2017-15617](#cve-2017-15617)
- [CVE-2017-15618](#cve-2017-15618)
- [CVE-2017-15619](#cve-2017-15619)
- [CVE-2017-15620](#cve-2017-15620)
- [CVE-2017-15621](#cve-2017-15621)
- [CVE-2017-15622](#cve-2017-15622)
- [CVE-2017-15623](#cve-2017-15623)
- [CVE-2017-15624](#cve-2017-15624)
- [CVE-2017-15625](#cve-2017-15625)
- [CVE-2017-15626](#cve-2017-15626)
- [CVE-2017-15627](#cve-2017-15627)
- [CVE-2017-15628](#cve-2017-15628)
- [CVE-2017-15629](#cve-2017-15629)
- [CVE-2017-15630](#cve-2017-15630)
- [CVE-2017-15631](#cve-2017-15631)
- [CVE-2017-15632](#cve-2017-15632)
- [CVE-2017-15633](#cve-2017-15633)
- [CVE-2017-15634](#cve-2017-15634)
- [CVE-2017-15635](#cve-2017-15635)
- [CVE-2017-15636](#cve-2017-15636)
- [CVE-2017-15637](#cve-2017-15637)
- [CVE-2017-15944](#cve-2017-15944)
- [CVE-2017-16544](#cve-2017-16544)
- [CVE-2017-16584](#cve-2017-16584)
- [CVE-2017-16716](#cve-2017-16716)
- [CVE-2017-16943](#cve-2017-16943)
- [CVE-2017-16944](#cve-2017-16944)
- [CVE-2017-16995](#cve-2017-16995)
- [CVE-2017-17033](#cve-2017-17033)
- [CVE-2017-17107](#cve-2017-17107)
- [CVE-2017-17215](#cve-2017-17215)
- [CVE-2017-17405](#cve-2017-17405)
- [CVE-2017-17408](#cve-2017-17408)
- [CVE-2017-17562](#cve-2017-17562)
- [CVE-2017-17692](#cve-2017-17692)
- [CVE-2017-17867](#cve-2017-17867)
- [CVE-2017-17969](#cve-2017-17969)
- [CVE-2017-18344](#cve-2017-18344)
- [CVE-2017-1000112](#cve-2017-1000112)
- [CVE-2017-1000117](#cve-2017-1000117)
- [CVE-2017-1000251](#cve-2017-1000251)
- [CVE-2017-1000353](#cve-2017-1000353)
- [CVE-2017-1000364](#cve-2017-1000364)
- [CVE-2017-1000365](#cve-2017-1000365)
- [CVE-2017-1000366](#cve-2017-1000366)
- [CVE-2017-1000367](#cve-2017-1000367)
- [CVE-2017-1000369](#cve-2017-1000369)
- [CVE-2017-1000370](#cve-2017-1000370)
- [CVE-2017-1000371](#cve-2017-1000371)
- [CVE-2017-1000372](#cve-2017-1000372)
- [CVE-2017-1000373](#cve-2017-1000373)
- [CVE-2017-1000374](#cve-2017-1000374)
- [CVE-2017-1000375](#cve-2017-1000375)
- [CVE-2017-1000376](#cve-2017-1000376)
- [CVE-2017-1000377](#cve-2017-1000377)
- [CVE-2017-1000378](#cve-2017-1000378)
- [CVE-2017-1000379](#cve-2017-1000379)
- [CVE-2017-1000405](#cve-2017-1000405)
- [CVE-2017-1000424](#cve-2017-1000424)
- [CVE-2017-1000459](#cve-2017-1000459)
- [CVE-2017-1002101](#cve-2017-1002101)
- [CVE-2018-0101](#cve-2018-0101)
- [CVE-2018-0114](#cve-2018-0114)
- [CVE-2018-0171](#cve-2018-0171)
- [CVE-2018-0296](#cve-2018-0296)
- [CVE-2018-0492](#cve-2018-0492)
- [CVE-2018-0497](#cve-2018-0497)
- [CVE-2018-0498](#cve-2018-0498)
- [CVE-2018-0743](#cve-2018-0743)
- [CVE-2018-0744](#cve-2018-0744)
- [CVE-2018-0752](#cve-2018-0752)
- [CVE-2018-0758](#cve-2018-0758)
- [CVE-2018-0763](#cve-2018-0763)
- [CVE-2018-0767](#cve-2018-0767)
- [CVE-2018-0769](#cve-2018-0769)
- [CVE-2018-0770](#cve-2018-0770)
- [CVE-2018-0774](#cve-2018-0774)
- [CVE-2018-0775](#cve-2018-0775)
- [CVE-2018-0776](#cve-2018-0776)
- [CVE-2018-0777](#cve-2018-0777)
- [CVE-2018-0780](#cve-2018-0780)
- [CVE-2018-0797](#cve-2018-0797)
- [CVE-2018-0802](#cve-2018-0802)
- [CVE-2018-0824](#cve-2018-0824)
- [CVE-2018-0833](#cve-2018-0833)
- [CVE-2018-0834](#cve-2018-0834)
- [CVE-2018-0835](#cve-2018-0835)
- [CVE-2018-0837](#cve-2018-0837)
- [CVE-2018-0838](#cve-2018-0838)
- [CVE-2018-0840](#cve-2018-0840)
- [CVE-2018-0860](#cve-2018-0860)
- [CVE-2018-0871](#cve-2018-0871)
- [CVE-2018-0878](#cve-2018-0878)
- [CVE-2018-0886](#cve-2018-0886)
- [CVE-2018-0891](#cve-2018-0891)
- [CVE-2018-0933](#cve-2018-0933)
- [CVE-2018-0934](#cve-2018-0934)
- [CVE-2018-0935](#cve-2018-0935)
- [CVE-2018-0953](#cve-2018-0953)
- [CVE-2018-0980](#cve-2018-0980)
- [CVE-2018-1036](#cve-2018-1036)
- [CVE-2018-1037](#cve-2018-1037)
- [CVE-2018-1038](#cve-2018-1038)
- [CVE-2018-1040](#cve-2018-1040)
- [CVE-2018-1111](#cve-2018-1111)
- [CVE-2018-1149](#cve-2018-1149)
- [CVE-2018-1150](#cve-2018-1150)
- [CVE-2018-1207](#cve-2018-1207)
- [CVE-2018-1270](#cve-2018-1270)
- [CVE-2018-1273](#cve-2018-1273)
- [CVE-2018-1275](#cve-2018-1275)
- [CVE-2018-1335](#cve-2018-1335)
- [CVE-2018-1435](#cve-2018-1435)
- [CVE-2018-2628](#cve-2018-2628)
- [CVE-2018-2694](#cve-2018-2694)
- [CVE-2018-2698](#cve-2018-2698)
- [CVE-2018-2844](#cve-2018-2844)
- [CVE-2018-2860](#cve-2018-2860)
- [CVE-2018-2893](#cve-2018-2893)
- [CVE-2018-2894](#cve-2018-2894)
- [CVE-2018-3055](#cve-2018-3055)
- [CVE-2018-3085](#cve-2018-3085)
- [CVE-2018-3191](#cve-2018-3191)
- [CVE-2018-3245](#cve-2018-3245)
- [CVE-2018-3253](#cve-2018-3253)
- [CVE-2018-3615](#cve-2018-3615)
- [CVE-2018-3693](#cve-2018-3693)
- [CVE-2018-3760](#cve-2018-3760)
- [CVE-2018-3784](#cve-2018-3784)
- [CVE-2018-3893](#cve-2018-3893)
- [CVE-2018-3894](#cve-2018-3894)
- [CVE-2018-3895](#cve-2018-3895)
- [CVE-2018-3896](#cve-2018-3896)
- [CVE-2018-3897](#cve-2018-3897)
- [CVE-2018-3903](#cve-2018-3903)
- [CVE-2018-3904](#cve-2018-3904)
- [CVE-2018-3905](#cve-2018-3905)
- [CVE-2018-3952](#cve-2018-3952)
- [CVE-2018-3971](#cve-2018-3971)
- [CVE-2018-4087](#cve-2018-4087)
- [CVE-2018-4010](#cve-2018-4010)
- [CVE-2018-4121](#cve-2018-4121)
- [CVE-2018-4148](#cve-2018-4148)
- [CVE-2018-4150](#cve-2018-4150)
- [CVE-2018-4192](#cve-2018-4192)
- [CVE-2018-4204](#cve-2018-4204)
- [CVE-2018-4233](#cve-2018-4233)
- [CVE-2018-4262](#cve-2018-4262)
- [CVE-2018-4307](#cve-2018-4307)
- [CVE-2018-4330](#cve-2018-4330)
- [CVE-2018-4338](#cve-2018-4338)
- [CVE-2018-4407](#cve-2018-4407)
- [CVE-2018-4415](#cve-2018-4415)
- [CVE-2018-4878](#cve-2018-4878)
- [CVE-2018-4990](#cve-2018-4990)
- [CVE-2018-4993](#cve-2018-4993)
- [CVE-2018-5002](#cve-2018-5002)
- [CVE-2018-5146](#cve-2018-5146)
- [CVE-2018-5175](#cve-2018-5175)
- [CVE-2018-5181](#cve-2018-5181)
- [CVE-2018-5189](#cve-2018-5189)
- [CVE-2018-5318](#cve-2018-5318)
- [CVE-2018-5390](#cve-2018-5390)
- [CVE-2018-5553](#cve-2018-5553)
- [CVE-2018-5711](#cve-2018-5711)
- [CVE-2018-5924](#cve-2018-5924)
- [CVE-2018-5925](#cve-2018-5925)
- [CVE-2018-5996](#cve-2018-5996)
- [CVE-2018-6034](#cve-2018-6034)
- [CVE-2018-6055](#cve-2018-6055)
- [CVE-2018-6056](#cve-2018-6056)
- [CVE-2018-6061](#cve-2018-6061)
- [CVE-2018-6064](#cve-2018-6064)
- [CVE-2018-6065](#cve-2018-6065)
- [CVE-2018-6072](#cve-2018-6072)
- [CVE-2018-6106](#cve-2018-6106)
- [CVE-2018-6128](#cve-2018-6128)
- [CVE-2018-6177](#cve-2018-6177)
- [CVE-2018-6184](#cve-2018-6184)
- [CVE-2018-6317](#cve-2018-6317)
- [CVE-2018-6376](#cve-2018-6376)
- [CVE-2018-6389](#cve-2018-6389)
- [CVE-2018-6460](#cve-2018-6460)
- [CVE-2018-6789](#cve-2018-6789)
- [CVE-2018-6794](#cve-2018-6794)
- [CVE-2018-6851](#cve-2018-6851)
- [CVE-2018-6852](#cve-2018-6852)
- [CVE-2018-6853](#cve-2018-6853)
- [CVE-2018-6854](#cve-2018-6854)
- [CVE-2018-6855](#cve-2018-6855)
- [CVE-2018-6856](#cve-2018-6856)
- [CVE-2018-6857](#cve-2018-6857)
- [CVE-2018-6871](#cve-2018-6871)
- [CVE-2018-6954](#cve-2018-6954)
- [CVE-2018-7182](#cve-2018-7182)
- [CVE-2018-7260](#cve-2018-7260)
- [CVE-2018-7273](#cve-2018-7273)
- [CVE-2018-7600](#cve-2018-7600)
- [CVE-2018-7602](#cve-2018-7602)
- [CVE-2018-7738](#cve-2018-7738)
- [CVE-2018-8021](#cve-2018-8021)
- [CVE-2018-8120](#cve-2018-8120)
- [CVE-2018-8140](#cve-2018-8140)
- [CVE-2018-8174](#cve-2018-8174)
- [CVE-2018-8212](#cve-2018-8212)
- [CVE-2018-8235](#cve-2018-8235)
- [CVE-2018-8367](#cve-2018-8367)
- [CVE-2018-8373](#cve-2018-8373)
- [CVE-2018-8383](#cve-2018-8383)
- [CVE-2018-8414](#cve-2018-8414)
- [CVE-2018-8420](#cve-2018-8420)
- [CVE-2018-8440](#cve-2018-8440)
- [CVE-2018-8495](#cve-2018-8495)
- [CVE-2018-8532](#cve-2018-8532)
- [CVE-2018-8589](#cve-2018-8589)
- [CVE-2018-8611](#cve-2018-8611)
- [CVE-2018-8639](#cve-2018-8639)
- [CVE-2018-8719](#cve-2018-8719)
- [CVE-2018-8733](#cve-2018-8733)
- [CVE-2018-8734](#cve-2018-8734)
- [CVE-2018-8735](#cve-2018-8735)
- [CVE-2018-8736](#cve-2018-8736)
- [CVE-2018-8778](#cve-2018-8778)
- [CVE-2018-8819](#cve-2018-8819)
- [CVE-2018-8897](#cve-2018-8897)
- [CVE-2018-8955](#cve-2018-8955)
- [CVE-2018-9206](#cve-2018-9206)
- [CVE-2018-9341](#cve-2018-9341)
- [CVE-2018-9359](#cve-2018-9359)
- [CVE-2018-9360](#cve-2018-9360)
- [CVE-2018-9361](#cve-2018-9361)
- [CVE-2018-9411](#cve-2018-9411)
- [CVE-2018-9445](#cve-2018-9445)
- [CVE-2018-9995](#cve-2018-9995)
- [CVE-2018-10115](#cve-2018-10115)
- [CVE-2018-10172](#cve-2018-10172)
- [CVE-2018-10468](#cve-2018-10468)
- [CVE-2018-10561](#cve-2018-10561)
- [CVE-2018-10562](#cve-2018-10562)
- [CVE-2018-10641](#cve-2018-10641)
- [CVE-2018-10666](#cve-2018-10666)
- [CVE-2018-10676](#cve-2018-10676)
- [CVE-2018-10895](#cve-2018-10895)
- [CVE-2018-10933](#cve-2018-10933)
- [CVE-2018-10944](#cve-2018-10944)
- [CVE-2018-10956](#cve-2018-10956)
- [CVE-2018-10994](#cve-2018-10994)
- [CVE-2018-11101](#cve-2018-11101)
- [CVE-2018-11235](#cve-2018-11235)
- [CVE-2018-11411](#cve-2018-11411)
- [CVE-2018-11689](#cve-2018-11689)
- [CVE-2018-11759](#cve-2018-11759)
- [CVE-2018-11776](#cve-2018-11776)
- [CVE-2018-11784](#cve-2018-11784)
- [CVE-2018-11788](#cve-2018-11788)
- [CVE-2018-11882](#cve-2018-11882)
- [CVE-2018-12015](#cve-2018-12015)
- [CVE-2018-12020](#cve-2018-12020)
- [CVE-2018-12034](#cve-2018-12034)
- [CVE-2018-12035](#cve-2018-12035)
- [CVE-2018-12056](#cve-2018-12056)
- [CVE-2018-12386](#cve-2018-12386)
- [CVE-2018-12387](#cve-2018-12387)
- [CVE-2018-12454](#cve-2018-12454)
- [CVE-2018-12885](#cve-2018-12885)
- [CVE-2018-13149](#cve-2018-13149)
- [CVE-2018-13452](#cve-2018-13452)
- [CVE-2018-14327](#cve-2018-14327)
- [CVE-2018-14634](#cve-2018-14634)
- [CVE-2018-14665](#cve-2018-14665)
- [CVE-2018-14667](#cve-2018-14667)
- [CVE-2018-14686](#cve-2018-14686)
- [CVE-2018-14715](#cve-2018-14715)
- [CVE-2018-14847](#cve-2018-14847)
- [CVE-2018-15473](#cve-2018-15473)
- [CVE-2018-15685](#cve-2018-15685)
- [CVE-2018-15705](#cve-2018-15705)
- [CVE-2018-15706](#cve-2018-15706)
- [CVE-2018-15707](#cve-2018-15707)
- [CVE-2018-15715](#cve-2018-15715)
- [CVE-2018-15869](#cve-2018-15869)
- [CVE-2018-15961](#cve-2018-15961)
- [CVE-2018-15982](#cve-2018-15982)
- [CVE-2018-16323](#cve-2018-16323)
- [CVE-2018-16384](#cve-2018-16384)
- [CVE-2018-16509](#cve-2018-16509)
- [CVE-2018-16946](#cve-2018-16946)
- [CVE-2018-17082](#cve-2018-17082)
- [CVE-2018-17144](#cve-2018-17144)
- [CVE-2018-17182](#cve-2018-17182)
- [CVE-2018-17780](#cve-2018-17780)
- [CVE-2018-19276](#cve-2018-19276)
- [CVE-2018-19788](#cve-2018-19788)
- [CVE-2018-20250](#cve-2018-20250)
- [CVE-2018-20714](#cve-2018-20714)
- [CVE-2018-1000006](#cve-2018-1000006)
- [CVE-2018-1000094](#cve-2018-1000094)
- [CVE-2018-1000129](#cve-2018-1000129)
- [CVE-2018-1000130](#cve-2018-1000130)
- [CVE-2018-1000136](#cve-2018-1000136)
- [CVE-2018-1002105](#cve-2018-1002105)
- [CVE-2019-0193](#cve-2019-0193)
- [CVE-2019-0211](#cve-2019-0211)
- [CVE-2019-0232](#cve-2019-0232)
- [CVE-2019-0539](#cve-2019-0539)
- [CVE-2019-0604](#cve-2019-0604)
- [CVE-2019-0708](#cve-2019-0708)
- [CVE-2019-0797](#cve-2019-0797)
- [CVE-2019-0808](#cve-2019-0808)
- [CVE-2019-0841](#cve-2019-0841)
- [CVE-2019-1306](#cve-2019-1306)
- [CVE-2019-1388](#cve-2019-1388)
- [CVE-2019-1414](#cve-2019-1414)
- [CVE-2019-1458](#cve-2019-1458)
- [CVE-2019-2588](#cve-2019-2588)
- [CVE-2019-2618](#cve-2019-2618)
- [CVE-2019-2725](#cve-2019-2725)
- [CVE-2019-2888](#cve-2019-2888)
- [CVE-2019-2890](#cve-2019-2890)
- [CVE-2020-3187](#cve-2020-3187)
- [CVE-2019-3394](#cve-2019-3394)
- [CVE-2019-3396](#cve-2019-3396)
- [CVE-2019-3560](#cve-2019-3560)
- [CVE-2019-3921](#cve-2019-3921)
- [CVE-2019-5241](#cve-2019-5241)
- [CVE-2019-5418](#cve-2019-5418)
- [CVE-2019-5624](#cve-2019-5624)
- [CVE-2019-5736](#cve-2019-5736)
- [CVE-2019-5790](#cve-2019-5790)
- [CVE-2019-6251](#cve-2019-6251)
- [CVE-2019-7192](#cve-2019-7192)
- [CVE-2019-7193](#cve-2019-7193)
- [CVE-2019-7194](#cve-2019-7194)
- [CVE-2019-7195](#cve-2019-7195)
- [CVE-2019-7238](#cve-2019-7238)
- [CVE-2019-7286](#cve-2019-7286)
- [CVE-2019-7609](#cve-2019-7609)
- [CVE-2019-8451](#cve-2019-8451)
- [CVE-2019-8518](#cve-2019-8518)
- [CVE-2019-8565](#cve-2019-8565)
- [CVE-2019-9213](#cve-2019-9213)
- [CVE-2019-10038](#cve-2019-10038)
- [CVE-2019-10392](#cve-2019-10392)
- [CVE-2019-11043](#cve-2019-11043)
- [CVE-2019-11354](#cve-2019-11354)
- [CVE-2019-11358](#cve-2019-11358)
- [CVE-2019-11510](#cve-2019-11510)
- [CVE-2019-11580](#cve-2019-11580)
- [CVE-2019-11581](#cve-2019-11581)
- [CVE-2019-12384](#cve-2019-12384)
- [CVE-2019-12409](#cve-2019-12409)
- [CVE-2019-12415](#cve-2019-12415)
- [CVE-2019-12526](#cve-2019-12526)
- [CVE-2019-12527](#cve-2019-12527)
- [CVE-2019-13272](#cve-2019-13272)
- [CVE-2019-13720](#cve-2019-13720)
- [CVE-2019-14234](#cve-2019-14234)
- [CVE-2019-14994](#cve-2019-14994)
- [CVE-2019-15107](#cce-2019-15107)
- [CVE-2019-15126](#cve-2019-15126)
- [CVE-2019-15642](#cve-2019-15642)
- [CVE-2019-16278](#cve-2019-16278)
- [CVE-2019-16384](#cve-2019-16384)
- [CVE-2019-16385](#cve-2019-16385)
- [CVE-2019-16759](#cve-2019-16759)
- [CVE-2019-17564](#cve-2019-17564)
- [CVE-2019-18683](#cve-2019-18683)
- [CVE-2019-18935](#cve-2019-18935)
- [CVE-2019-19781](#cve-2019-19781)
- [CVE-2019-20197](#cve-2019-20197)
- [CVE-2020-0601](#cve-2020-0601)
- [CVE-2020-0609](#cve-2020-0609)
- [CVE-2020-0610](#cve-2020-0610)
- [CVE-2020-0668](#cve-2020-0668)
- [CVE-2020-0683](#cve-2020-0683)
- [CVE-2020-0688](#cve-2020-0688)
- [CVE-2020-0787](#cve-2020-0787)
- [CVE-2020-0796](#cve-2020-0796)
- [CVE-2020-0863](#cve-2020-0863)
- [CVE-2020-0932](#cve-2020-0932)
- [CVE-2020-0984](#cve-2020-0984)
- [CVE-2020-1181](#cve-2020-1181)
- [CVE-2020-1206](#cve-2020-1206)
- [CVE-2020-1938](#cve-2020-1938)
- [CVE-2020-2096](#cve-2020-2096)
- [CVE-2020-2551](#cve-2020-2551)
- [CVE-2020-2555](#cve-2020-2555)
- [CVE-2020-3452](#cve-2020-3452)
- [CVE-2020-3882](#cve-2020-3882)
- [CVE-2020-3950](#cve-2020-3950)
- [CVE-2020-3956](#cve-2020-3956)
- [CVE-2020-5398](#cve-2020-5398)
- [CVE-2020-5902](#cve-2020-5902)
- [CVE-2020-6418](#cve-2020-6418)
- [CVE-2020-7961](#cve-2020-7961)
- [CVE-2020-8840](#cve-2020-8840)
- [CVE-2020-9471](#cve-2020-9471)
- [CVE-2020-9472](#cve-2020-9472)
- [CVE-2020-9484](#cve-2020-9484)
- [CVE-2020-9546](#cve-2020-9546)
- [CVE-2020-9547](#cve-2020-9547)
- [CVE-2020-9548](#cve-2020-9548)
- [CVE-2020-10673](#cve-2020-10673)
- [CVE-2020-11108](#cve-2020-11108)
- [CVE-2020-11932](#cve-2020-11932)
- [CVE-2020-28948](#cve-2020-28948)
- [CVE-2020-28949](#cve-2020-28949)

## Resource

### [CVE-2011-2856](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2011-2856)

- Google V8, as used in Google Chrome before 14.0.835.163, allows remote attackers to bypass the Same Origin Policy via unspecified vectors.

### [CVE-2011-3243](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2011-3243)

- Cross-site scripting (XSS) vulnerability in WebKit, as used in Apple iOS before 5 and Safari before 5.1.1, allows remote attackers to inject arbitrary web script or HTML via vectors involving inactive DOM windows.

### [CVE-2013-2618](https://blog.trendmicro.com/trendlabs-security-intelligence/cryptocurrency-miner-distributed-via-php-weathermap-vulnerability-targets-linux-servers/)

- Cross-site scripting (XSS) vulnerability in editor.php in Network Weathermap before 0.97b allows remote attackers to inject arbitrary web script or HTML via the map_title parameter.

### [CVE-2013-6632](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2013-6632.md)

- Integer overflow in Google Chrome before 31.0.1650.57 allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via unspecified vectors, as demonstrated during a Mobile Pwn2Own competition at PacSec 2013.

### [CVE-2014-1701](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2014-1701)

- The GenerateFunction function in bindings/scripts/code_generator_v8.pm in Blink, as used in Google Chrome before 33.0.1750.149, does not implement a certain cross-origin restriction for the EventTarget::dispatchEvent function, which allows remote attackers to conduct Universal XSS (UXSS) attacks via vectors involving events.

### [CVE-2014-1705](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2014-1705.md)

- Google V8, as used in Google Chrome before 33.0.1750.152 on OS X and Linux and before 33.0.1750.154 on Windows, allows remote attackers to cause a denial of service (memory corruption) or possibly have unspecified other impact via unknown vectors.

### [CVE-2014-1747](https://github.com/Metnew/uxss-db/blob/master/chrome/CVE-2014-1747)

- Cross-site scripting (XSS) vulnerability in the DocumentLoader::maybeCreateArchive function in core/loader/DocumentLoader.cpp in Blink, as used in Google Chrome before 35.0.1916.114, allows remote attackers to inject arbitrary web script or HTML via crafted MHTML content, aka "Universal XSS (UXSS)."

### [CVE-2014-3176](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2014-3176.md)

- Google Chrome before 37.0.2062.94 does not properly handle the interaction of extensions, IPC, the sync API, and Google V8, which allows remote attackers to execute arbitrary code via unspecified vectors, a different vulnerability than CVE-2014-3177.

### [CVE-2014-6332](https://gist.github.com/worawit/84ab41358b8465966224)

- OleAut32.dll in OLE in Microsoft Windows Server 2003 SP2, Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, and Windows RT Gold and 8.1 allows remote attackers to execute arbitrary code via a crafted web site, as demonstrated by an array-redimensioning attempt that triggers improper handling of a size value in the SafeArrayDimen function, aka "Windows OLE Automation Array Remote Code Execution Vulnerability."

### [CVE-2014-7927](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2014-7927.md)

- The SimplifiedLowering::DoLoadBuffer function in compiler/simplified-lowering.cc in Google V8, as used in Google Chrome before 40.0.2214.91, does not properly choose an integer data type, which allows remote attackers to cause a denial of service (memory corruption) or possibly have unspecified other impact via crafted JavaScript code.

### [CVE-2014-7928](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2014-7928.md)

- hydrogen.cc in Google V8, as used Google Chrome before 40.0.2214.91, does not properly handle arrays with holes, which allows remote attackers to cause a denial of service (memory corruption) or possibly have unspecified other impact via crafted JavaScript code that triggers an array copy.

### [CVE-2015-0072](https://github.com/dbellavista/uxss-poc)

- Cross-site scripting (XSS) vulnerability in Microsoft Internet Explorer 9 through 11 allows remote attackers to bypass the Same Origin Policy and inject arbitrary web script or HTML via vectors involving an IFRAME element that triggers a redirect, a second IFRAME element that does not trigger a redirect, and an eval of a WindowProxy object, aka "Universal XSS (UXSS)."

### [CVE-2015-0235](https://github.com/geekben/cve-collections/blob/master/cve20150235poc.c)

- Heap-based buffer overflow in the __nss_hostname_digits_dots function in glibc 2.2, and other 2.x versions before 2.18, allows context-dependent attackers to execute arbitrary code via vectors related to the (1) gethostbyname or (2) gethostbyname2 function, aka "GHOST".

### [CVE-2015-0240](https://gist.github.com/worawit/051e881fc94fe4a49295)

- The Netlogon server implementation in smbd in Samba 3.5.x and 3.6.x before 3.6.25, 4.0.x before 4.0.25, 4.1.x before 4.1.17, and 4.2.x before 4.2.0rc5 performs a free operation on an uninitialized stack pointer, which allows remote attackers to execute arbitrary code via crafted Netlogon packets that use the ServerPasswordSet RPC API, as demonstrated by packets reaching the _netr_ServerPasswordSet function in rpc_server/netlogon/srv_netlog_nt.c.

### [CVE-2015-1233](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2015-1233.md)

- Google Chrome before 41.0.2272.118 does not properly handle the interaction of IPC, the Gamepad API, and Google V8, which allows remote attackers to execute arbitrary code via unspecified vectors.

### [CVE-2015-1242](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2015-1242.md)

- The ReduceTransitionElementsKind function in hydrogen-check-elimination.cc in Google V8 before 4.2.77.8, as used in Google Chrome before 42.0.2311.90, allows remote attackers to cause a denial of service or possibly have unspecified other impact via crafted JavaScript code that leverages "type confusion" in the check-elimination optimization.

### [CVE-2015-1268](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2015-1268)

- bindings/scripts/v8_types.py in Blink, as used in Google Chrome before 43.0.2357.130, does not properly select a creation context for a return value's DOM wrapper, which allows remote attackers to bypass the Same Origin Policy via crafted JavaScript code, as demonstrated by use of a data: URL.

### [CVE-2015-1635](https://gist.github.com/worawit/54f2e5a7a1a028191f76)

- HTTP.sys in Microsoft Windows 7 SP1, Windows Server 2008 R2 SP1, Windows 8, Windows 8.1, and Windows Server 2012 Gold and R2 allows remote attackers to execute arbitrary code via crafted HTTP requests, aka "HTTP.sys Remote Code Execution Vulnerability."

### [CVE-2015-1830](https://github.com/ysrc/xunfeng/blob/master/vulscan/vuldb/activemq_upload.py)

- Directory traversal vulnerability in the fileserver upload/download functionality for blob messages in Apache ActiveMQ 5.x before 5.11.2 for Windows allows remote attackers to create JSP files in arbitrary directories via unspecified vectors.

### [CVE-2015-2177](https://www.exploit-db.com/exploits/44802/)

- Siemens SIMATIC S7-300 CPU devices allow remote attackers to cause a denial of service (defect-mode transition) via crafted packets on (1) TCP port 102 or (2) Profibus.

### [CVE-2015-3306](https://www.exploit-db.com/exploits/36803/)

- The mod_copy module in ProFTPD 1.3.5 allows remote attackers to read and write to arbitrary files via the site cpfr and site cpto commands.

### [CVE-2015-5119](https://www.mdsec.co.uk/2018/02/adobe-flash-exploitation-then-and-now-from-cve-2015-5119-to-cve-2018-4878/)

- Use-after-free vulnerability in the ByteArray class in the ActionScript 3 (AS3) implementation in Adobe Flash Player 13.x through 13.0.0.296 and 14.x through 18.0.0.194 on Windows and OS X and 11.x through 11.2.202.468 on Linux allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via crafted Flash content that overrides a valueOf function, as exploited in the wild in July 2015.

### [CVE-2015-5254](https://github.com/jas502n/CVE-2015-5254)

- Apache ActiveMQ 5.x before 5.13.0 does not restrict the classes that can be serialized in the broker, which allows remote attackers to execute arbitrary code via a crafted serialized Java Message Service (JMS) ObjectMessage object.

### [CVE-2015-5531](https://github.com/nixawk/labs/tree/master/CVE-2015-5531)

- Directory traversal vulnerability in Elasticsearch before 1.6.1 allows remote attackers to read arbitrary files via unspecified vectors related to snapshot API calls.

### [CVE-2015-6086](https://github.com/payatu/CVE-2015-6086)

- Microsoft Internet Explorer 9 through 11 allows remote attackers to obtain sensitive information from process memory via a crafted web site, aka "Internet Explorer Information Disclosure Vulnerability."

### [CVE-2015-6755](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2015-6755)

- The ContainerNode::parserInsertBefore function in core/dom/ContainerNode.cpp in Blink, as used in Google Chrome before 46.0.2490.71, proceeds with a DOM tree insertion in certain cases where a parent node no longer contains a child node, which allows remote attackers to bypass the Same Origin Policy via crafted JavaScript code.

### [CVE-2015-6764](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2015-6764.md)

- The BasicJsonStringifier::SerializeJSArray function in json-stringifier.h in the JSON stringifier in Google V8, as used in Google Chrome before 47.0.2526.73, improperly loads array elements, which allows remote attackers to cause a denial of service (out-of-bounds memory access) or possibly have unspecified other impact via crafted JavaScript code.

### [CVE-2015-6769](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2015-6769)

- The provisional-load commit implementation in WebKit/Source/bindings/core/v8/WindowProxy.cpp in Google Chrome before 47.0.2526.73 allows remote attackers to bypass the Same Origin Policy by leveraging a delay in window proxy clearing.

### [CVE-2015-6770](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2015-6770)

- The DOM implementation in Google Chrome before 47.0.2526.73 allows remote attackers to bypass the Same Origin Policy via unspecified vectors, a different vulnerability than CVE-2015-6768.

### [CVE-2015-6771](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2015-6771.md)

- js/array.js in Google V8, as used in Google Chrome before 47.0.2526.73, improperly implements certain map and filter operations for arrays, which allows remote attackers to cause a denial of service (out-of-bounds memory access) or possibly have unspecified other impact via crafted JavaScript code.

### [CVE-2015-7450](https://cxsecurity.com/issue/WLB-2017030142)

- Serialized-object interfaces in certain IBM analytics, business solutions, cognitive, IT infrastructure, and mobile and social products allow remote attackers to execute arbitrary commands via a crafted serialized Java object, related to the InvokerTransformer class in the Apache Commons Collections library.

### [CVE-2015-7501](https://github.com/joaomatosf/JavaDeserH2HC)

- Red Hat JBoss A-MQ 6.x; BPM Suite (BPMS) 6.x; BRMS 6.x and 5.x; Data Grid (JDG) 6.x; Data Virtualization (JDV) 6.x and 5.x; Enterprise Application Platform 6.x, 5.x, and 4.3.x; Fuse 6.x; Fuse Service Works (FSW) 6.x; Operations Network (JBoss ON) 3.x; Portal 6.x; SOA Platform (SOA-P) 5.x; Web Server (JWS) 3.x; Red Hat OpenShift/xPAAS 3.x; and Red Hat Subscription Asset Manager 1.3 allow remote attackers to execute arbitrary commands via a crafted serialized Java object, related to the Apache Commons Collections (ACC) library.

### [CVE-2015-7545](https://hackmd.io/s/SkKL68GIe#🍊-web-300-git)

- The (1) git-remote-ext and (2) unspecified other remote helper programs in Git before 2.3.10, 2.4.x before 2.4.10, 2.5.x before 2.5.4, and 2.6.x before 2.6.1 do not properly restrict the allowed protocols, which might allow remote attackers to execute arbitrary code via a URL in a (a) .gitmodules file or (b) unknown other sources in a submodule.

### [CVE-2015-8584](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2015-8548.md)

- JSON, OOB.

### [CVE-2016-0040](https://github.com/de7ec7ed/CVE-2016-0040)

- The kernel in Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, and Windows 7 SP1 allows local users to gain privileges via a crafted application, aka "Windows Elevation of Privilege Vulnerability."

### [CVE-2016-0450](https://redr2e.com/cve-to-poc-cve-2016-0450/)

- Unspecified vulnerability in the Oracle GoldenGate component in Oracle GoldenGate 11.2 and 12.1.2 allows remote attackers to affect availability via unknown vectors.

### [CVE-2016-0451](https://redr2e.com/cve-to-poc-cve-2016-0451/)

- Unspecified vulnerability in the Oracle GoldenGate component in Oracle GoldenGate 11.2 and 12.1.2 allows remote attackers to affect confidentiality, integrity, and availability via unknown vectors, a different vulnerability than CVE-2016-0452.

### [CVE-2016-0728](https://github.com/geekben/cve-collections/blob/master/cve20160728poc.c)

- The join_session_keyring function in security/keys/process_keys.c in the Linux kernel before 4.4.1 mishandles object references in a certain error case, which allows local users to gain privileges or cause a denial of service (integer overflow and use-after-free) via crafted keyctl commands.

### [CVE-2016-0788](https://blog.csdn.net/u011721501/article/details/78548997)

- The remoting module in Jenkins before 1.650 and LTS before 1.642.2 allows remote attackers to execute arbitrary code by opening a JRMP listener.

### [CVE-2016-0792](https://github.com/jpiechowka/jenkins-cve-2016-0792)

- Multiple unspecified API endpoints in Jenkins before 1.650 and LTS before 1.642.2 allow remote authenticated users to execute arbitrary code via serialized data in an XML file, related to XStream and groovy.util.Expando.

### [CVE-2016-0856](https://github.com/thezdi/PoC/tree/master/CVE-2016-0856)

- Multiple stack-based buffer overflows in Advantech WebAccess before 8.1 allow remote attackers to execute arbitrary code via unspecified vectors.

### [CVE-2016-1631](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2016-1631)

- The PPB_Flash_MessageLoop_Impl::InternalRun function in content/renderer/pepper/ppb_flash_message_loop_impl.cc in the Pepper plugin in Google Chrome before 49.0.2623.75 mishandles nested message loops, which allows remote attackers to bypass the Same Origin Policy via a crafted web site.

### [CVE-2016-1646](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-1646.md)

- The Array.prototype.concat implementation in builtins.cc in Google V8, as used in Google Chrome before 49.0.2623.108, does not properly consider element data types, which allows remote attackers to cause a denial of service (out-of-bounds read) or possibly have unspecified other impact via crafted JavaScript code.

### [CVE-2016-1653](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-1653.md)

- The LoadBuffer implementation in Google V8, as used in Google Chrome before 50.0.2661.75, mishandles data types, which allows remote attackers to cause a denial of service or possibly have unspecified other impact via crafted JavaScript code that triggers an out-of-bounds write operation, related to compiler/pipeline.cc and compiler/simplified-lowering.cc.

### [CVE-2016-1665](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-1665.md)

- The JSGenericLowering class in compiler/js-generic-lowering.cc in Google V8, as used in Google Chrome before 50.0.2661.94, mishandles comparison operators, which allows remote attackers to obtain sensitive information via crafted JavaScript code.

### [CVE-2016-1667](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2016-1667)

- The TreeScope::adoptIfNeeded function in WebKit/Source/core/dom/TreeScope.cpp in the DOM implementation in Blink, as used in Google Chrome before 50.0.2661.102, does not prevent script execution during node-adoption operations, which allows remote attackers to bypass the Same Origin Policy via a crafted web site.

### [CVE-2016-1668](https://github.com/Metnew/uxss-db/blob/master/chrome/CVE-2016-1668)

- The forEachForBinding function in WebKit/Source/bindings/core/v8/Iterable.h in the V8 bindings in Blink, as used in Google Chrome before 50.0.2661.102, uses an improper creation context, which allows remote attackers to bypass the Same Origin Policy via a crafted web site.

### [CVE-2016-1669](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-1669.md)

- The Zone::New function in zone.cc in Google V8 before 5.0.71.47, as used in Google Chrome before 50.0.2661.102, does not properly determine when to expand certain memory allocations, which allows remote attackers to cause a denial of service (buffer overflow) or possibly have unspecified other impact via crafted JavaScript code.

### [CVE-2016-1672](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2016-1672)

- The ModuleSystem::RequireForJsInner function in extensions/renderer/module_system.cc in the extension bindings in Google Chrome before 51.0.2704.63 mishandles properties, which allows remote attackers to conduct bindings-interception attacks and bypass the Same Origin Policy via unspecified vectors.

### [CVE-2016-1673](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2016-1673)

- Blink, as used in Google Chrome before 51.0.2704.63, allows remote attackers to bypass the Same Origin Policy via unspecified vectors.

### [CVE-2016-1674](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2016-1674)

- The extensions subsystem in Google Chrome before 51.0.2704.63 allows remote attackers to bypass the Same Origin Policy via unspecified vectors.

### [CVE-2016-1675](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2016-1675)

- Blink, as used in Google Chrome before 51.0.2704.63, allows remote attackers to bypass the Same Origin Policy by leveraging the mishandling of Document reattachment during destruction, related to FrameLoader.cpp and LocalFrame.cpp.

### [CVE-2016-1676](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2016-1676)

- extensions/renderer/resources/binding.js in the extension bindings in Google Chrome before 51.0.2704.63 does not properly use prototypes, which allows remote attackers to bypass the Same Origin Policy via unspecified vectors.

### [CVE-2016-1677](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-1677.md)

- uri.js in Google V8 before 5.1.281.26, as used in Google Chrome before 51.0.2704.63, uses an incorrect array type, which allows remote attackers to obtain sensitive information by calling the decodeURI function and leveraging "type confusion".

### [CVE-2016-1688](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-1688.md)

- The regexp (aka regular expression) implementation in Google V8 before 5.0.71.40, as used in Google Chrome before 51.0.2704.63, mishandles external string sizes, which allows remote attackers to cause a denial of service (out-of-bounds read) via crafted JavaScript code.

### [CVE-2016-1697](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2016-1697)

- The FrameLoader::startLoad function in WebKit/Source/core/loader/FrameLoader.cpp in Blink, as used in Google Chrome before 51.0.2704.79, does not prevent frame navigations during DocumentLoader detach operations, which allows remote attackers to bypass the Same Origin Policy via crafted JavaScript code.

### [CVE-2016-1710](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2016-1710)

- The ChromeClientImpl::createWindow method in WebKit/Source/web/ChromeClientImpl.cpp in Blink, as used in Google Chrome before 52.0.2743.82, does not prevent window creation by a deferred frame, which allows remote attackers to bypass the Same Origin Policy via a crafted web site.

### [CVE-2016-1711](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2016-1711)

- WebKit/Source/core/loader/FrameLoader.cpp in Blink, as used in Google Chrome before 52.0.2743.82, does not disable frame navigation during a detach operation on a DocumentLoader object, which allows remote attackers to bypass the Same Origin Policy via a crafted web site.

### [CVE-2016-1779](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2016-1779)

- WebKit in Apple iOS before 9.3 and Safari before 9.1 allows remote attackers to bypass the Same Origin Policy and obtain physical-location data via a crafted geolocation request.

### [CVE-2016-1857](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2016-1857.md)

- WebKit, as used in Apple iOS before 9.3.2, Safari before 9.1.1, and tvOS before 9.2.1, allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, a different vulnerability than CVE-2016-1854, CVE-2016-1855, and CVE-2016-1856.

### [CVE-2016-1910](https://github.com/vah13/SAP_exploit)

- The User Management Engine (UME) in SAP NetWeaver 7.4 allows attackers to decrypt unspecified data via unknown vectors, aka SAP Security Note 2191290.

### [CVE-2016-2384](https://github.com/xairy/kernel-exploits/tree/master/CVE-2016-2384)

- Double free vulnerability in the snd_usbmidi_create function in sound/usb/midi.c in the Linux kernel before 4.5 allows physically proximate attackers to cause a denial of service (panic) or possibly have unspecified other impact via vectors involving an invalid USB descriptor.

### [CVE-2016-2386](https://github.com/vah13/SAP_exploit)

- SQL injection vulnerability in the UDDI server in SAP NetWeaver J2EE Engine 7.40 allows remote attackers to execute arbitrary SQL commands via unspecified vectors, aka SAP Security Note 2101079.

### [CVE-2016-2388](https://github.com/vah13/SAP_exploit)

- The Universal Worklist Configuration in SAP NetWeaver 7.4 allows remote attackers to obtain sensitive user information via a crafted HTTP request, aka SAP Security Note 2256846.

### [CVE-2016-3087](https://github.com/nixawk/labs/tree/master/CVE-2016-3087)

- Apache Struts 2.3.20.x before 2.3.20.3, 2.3.24.x before 2.3.24.3, and 2.3.28.x before 2.3.28.1, when Dynamic Method Invocation is enabled, allow remote attackers to execute arbitrary code via vectors related to an ! (exclamation mark) operator to the REST Plugin.

### [CVE-2016-3088](https://github.com/coffeehb/Some-PoC-oR-ExP/tree/master/ActiveMQExP)

- The Fileserver web application in Apache ActiveMQ 5.x before 5.14.0 allows remote attackers to upload and execute arbitrary files via an HTTP PUT followed by an HTTP MOVE request.

### [CVE-2016-3309](https://siberas.de/blog/2017/10/05/exploitation_case_study_wild_pool_overflow_CVE-2016-3309_reloaded.html)

- The kernel-mode drivers in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607 allow local users to gain privileges via a crafted application, aka "Win32k Elevation of Privilege Vulnerability," a different vulnerability than CVE-2016-3308, CVE-2016-3310, and CVE-2016-3311.

### [CVE-2016-3371](https://github.com/WindowsExploits/Exploits/tree/master/CVE-2016-3371)

- The kernel API in Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, and Windows 10 Gold, 1511, and 1607 does not properly enforce permissions, which allows local users to obtain sensitive information via a crafted application, aka "Windows Kernel Elevation of Privilege Vulnerability."

### [CVE-2016-3386](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-3386.md)

- The Chakra JavaScript engine in Microsoft Edge allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-3389, CVE-2016-7190, and CVE-2016-7194.

### [CVE-2016-3714](https://mukarramkhalid.com/imagemagick-imagetragick-exploit/)

- The (1) EPHEMERAL, (2) HTTPS, (3) MVG, (4) MSL, (5) TEXT, (6) SHOW, (7) WIN, and (8) PLT coders in ImageMagick before 6.9.3-10 and 7.x before 7.0.1-1 allow remote attackers to execute arbitrary code via shell metacharacters in a crafted image, aka "ImageTragick."

### [CVE-2016-4338](https://github.com/nixawk/labs/tree/master/CVE-2016-4338)

- The mysql user parameter configuration script (userparameter_mysql.conf) in the agent in Zabbix before 2.0.18, 2.2.x before 2.2.13, and 3.0.x before 3.0.3, when used with a shell other than bash, allows context-dependent attackers to execute arbitrary code or SQL commands via the mysql.size parameter.

### [CVE-2016-4437](https://github.com/jas502n/SHIRO-550)

- Apache Shiro before 1.2.5, when a cipher key has not been configured for the "remember me" feature, allows remote attackers to execute arbitrary code or bypass intended access restrictions via an unspecified request parameter.

### [CVE-2016-4622](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2016-4622.md)

- WebKit in Apple iOS before 9.3.3, Safari before 9.1.2, and tvOS before 9.2.2 allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, a different vulnerability than CVE-2016-4589, CVE-2016-4623, and CVE-2016-4624.

### [CVE-2016-4734](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2016-4734.md)

- WebKit in Apple iOS before 10, Safari before 10, and tvOS before 10 allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, a different vulnerability than CVE-2016-4611, CVE-2016-4730, CVE-2016-4733, and CVE-2016-4735.

### [CVE-2016-4971](https://github.com/KINGSABRI/CVE-in-Ruby/tree/master/CVE-2016-4971)

- GNU wget before 1.18 allows remote servers to write to arbitrary files by redirecting a request from HTTP to a crafted FTP resource.

### [CVE-2016-5129](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-5129.md)

- Google V8 before 5.2.361.32, as used in Google Chrome before 52.0.2743.82, does not properly process left-trimmed objects, which allows remote attackers to cause a denial of service (memory corruption) or possibly have unspecified other impact via crafted JavaScript code.

### [CVE-2016-5172](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-5172.md)

- The parser in Google V8, as used in Google Chrome before 53.0.2785.113, mishandles scopes, which allows remote attackers to obtain sensitive information from arbitrary memory locations via crafted JavaScript code.

### [CVE-2016-5195](https://github.com/nixawk/labs/tree/master/CVE-2016-5195)

- Race condition in mm/gup.c in the Linux kernel 2.x through 4.x before 4.8.3 allows local users to gain privileges by leveraging incorrect handling of a copy-on-write (COW) feature to write to a read-only memory mapping, as exploited in the wild in October 2016, aka "Dirty COW."

### [CVE-2016-5198](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-5198.md)

- V8 in Google Chrome prior to 54.0.2840.90 for Linux, and 54.0.2840.85 for Android, and 54.0.2840.87 for Windows and Mac included incorrect optimisation assumptions, which allowed a remote attacker to perform arbitrary read/write operations, leading to code execution, via a crafted HTML page.

### [CVE-2016-5200](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-5200.md)

- V8 in Google Chrome prior to 54.0.2840.98 for Mac, and 54.0.2840.99 for Windows, and 54.0.2840.100 for Linux, and 55.0.2883.84 for Android incorrectly applied type rules, which allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page.

### [CVE-2016-5204](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2016-5204)

- Leaking of an SVG shadow tree leading to corruption of the DOM tree in Blink in Google Chrome prior to 55.0.2883.75 for Mac, Windows and Linux, and 55.0.2883.84 for Android allowed a remote attacker to inject arbitrary scripts or HTML (UXSS) via a crafted HTML page.

### [CVE-2016-5207](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2016-5207)

- In Blink in Google Chrome prior to 55.0.2883.75 for Mac, Windows and Linux, and 55.0.2883.84 for Android, corruption of the DOM tree could occur during the removal of a full screen element, which allowed a remote attacker to achieve arbitrary code execution via a crafted HTML page.

### [CVE-2016-5346](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2016-5346)

- An Information Disclosure vulnerability exists in the Google Pixel/Pixel SL Qualcomm Avtimer Driver due to a NULL pointer dereference when processing an accept system call by the user process on AF_MSM_IPC sockets, which could let a local malicious user obtain sensitive information (Android Bug ID A-32551280).

### [CVE-2016-5610](https://github.com/renorobert/virtualbox-nat-dhcp-bugs/tree/master/CVE-2016-5610)

- Unspecified vulnerability in the Oracle VM VirtualBox component before 5.0.28 and 5.1.x before 5.1.8 in Oracle Virtualization allows local users to affect confidentiality, integrity, and availability via vectors related to Core.

### [CVE-2016-5611](https://github.com/renorobert/virtualbox-nat-dhcp-bugs/tree/master/CVE-2016-5611)

- Unspecified vulnerability in the Oracle VM VirtualBox component before 5.0.28 and 5.1.x before 5.1.8 in Oracle Virtualization allows local users to affect confidentiality via vectors related to Core.

### [CVE-2016-5734](https://github.com/coffeehb/Some-PoC-oR-ExP/blob/master/PhpMyAdmin/phpmyadmin4.6.2_RCE.py)

- phpMyAdmin 4.0.x before 4.0.10.16, 4.4.x before 4.4.15.7, and 4.6.x before 4.6.3 does not properly choose delimiters to prevent use of the preg_replace e (aka eval) modifier, which might allow remote attackers to execute arbitrary PHP code via a crafted string, as demonstrated by the table search-and-replace implementation.

### [CVE-2016-6210](https://github.com/KINGSABRI/CVE-in-Ruby/tree/master/CVE-2016-6210)

- sshd in OpenSSH before 7.3, when SHA256 or SHA512 are used for user password hashing, uses BLOWFISH hashing on a static password when the username does not exist, which allows remote attackers to enumerate users by leveraging the timing difference between responses when a large password is provided.

### [CVE-2016-6277](https://github.com/nixawk/labs/tree/master/CVE-2016-6277)

- NETGEAR R6250 before 1.0.4.6.Beta, R6400 before 1.0.1.18.Beta, R6700 before 1.0.1.14.Beta, R6900, R7000 before 1.0.7.6.Beta, R7100LG before 1.0.0.28.Beta, R7300DST before 1.0.0.46.Beta, R7900 before 1.0.1.8.Beta, R8000 before 1.0.3.26.Beta, D6220, D6400, D7000, and possibly other routers allow remote attackers to execute arbitrary commands via shell metacharacters in the path info to cgi-bin/.

### [CVE-2016-6415](https://github.com/nixawk/labs/tree/master/CVE-2016-6415)

- The server IKEv1 implementation in Cisco IOS 12.2 through 12.4 and 15.0 through 15.6, IOS XE through 3.18S, IOS XR 4.3.x and 5.0.x through 5.2.x, and PIX before 7.0 allows remote attackers to obtain sensitive information from device memory via a Security Association (SA) negotiation request, aka Bug IDs CSCvb29204 and CSCvb36055 or BENIGNCERTAIN.

### [CVE-2016-6662](https://github.com/MaYaSeVeN/CVE-2016-6662)

- Oracle MySQL through 5.5.52, 5.6.x through 5.6.33, and 5.7.x through 5.7.15; MariaDB before 5.5.51, 10.0.x before 10.0.27, and 10.1.x before 10.1.17; and Percona Server before 5.5.51-38.1, 5.6.x before 5.6.32-78.0, and 5.7.x before 5.7.14-7 allow local users to create arbitrary configurations and bypass certain protection mechanisms by setting general_log_file to a my.cnf configuration. NOTE: this can be leveraged to execute arbitrary code with root privileges by setting malloc_lib. NOTE: the affected MySQL version information is from Oracle's October 2016 CPU. Oracle has not commented on third-party claims that the issue was silently patched in MySQL 5.5.52, 5.6.33, and 5.7.15.

### [CVE-2016-6700](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2016-6700)

- An elevation of privilege vulnerability in libzipfile in Android 4.x before 4.4.4, 5.0.x before 5.0.2, and 5.1.x before 5.1.1 could enable a local malicious application to execute arbitrary code within the context of a privileged process. This issue is rated as Critical due to the possibility of a local permanent device compromise, which may require reflashing the operating system to repair the device. Android ID: A-30916186.

### [CVE-2016-6702](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2016-6702)

- A remote code execution vulnerability in libjpeg in Android 4.x before 4.4.4, 5.0.x before 5.0.2, and 5.1.x before 5.1.1 could enable an attacker using a specially crafted file to execute arbitrary code in the context of an unprivileged process. This issue is rated as High due to the possibility of remote code execution in an application that uses libjpeg. Android ID: A-30259087.

### [CVE-2016-6762](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2016-6762)

- An elevation of privilege vulnerability in the libziparchive library could enable a local malicious application to execute arbitrary code within the context of a privileged process. This issue is rated as High because it could be used to gain local access to elevated capabilities, which are not normally accessible to a third-party application. Product: Android. Versions: 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0. Android ID: A-31251826.

### [CVE-2016-6787](https://hardenedlinux.github.io/system-security/2017/10/16/Exploiting-on-CVE-2016-6787.html)

- kernel/events/core.c in the performance subsystem in the Linux kernel before 4.0 mismanages locks during certain migrations, which allows local users to gain privileges via a crafted application, aka Android internal bug 31095224.

### [CVE-2016-7124](http://0x48.pw/2016/09/13/0x22/)

- ext/standard/var_unserializer.c in PHP before 5.6.25 and 7.x before 7.0.10 mishandles certain invalid objects, which allows remote attackers to cause a denial of service or possibly have unspecified other impact via crafted serialized data that leads to a (1) __destruct call or (2) magic method call.

### [CVE-2016-7189](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7189.md)

- The Chakra JavaScript engine in Microsoft Edge allows remote attackers to execute arbitrary code via a crafted web site, aka "Scripting Engine Remote Code Execution Vulnerability".

### [CVE-2016-7190](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7190.md)

- The Chakra JavaScript engine in Microsoft Edge allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-3386, CVE-2016-3389, and CVE-2016-7194.

### [CVE-2016-7194](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7194.md)

- The Chakra JavaScript engine in Microsoft Edge allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-3386, CVE-2016-3389, and CVE-2016-7190.

### [CVE-2016-7200](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7200.md)

- The Chakra JavaScript scripting engine in Microsoft Edge allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-7201, CVE-2016-7202, CVE-2016-7203, CVE-2016-7208, CVE-2016-7240, CVE-2016-7242, and CVE-2016-7243.

### [CVE-2016-7201](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7201.md)

- The Chakra JavaScript scripting engine in Microsoft Edge allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-7200, CVE-2016-7202, CVE-2016-7203, CVE-2016-7208, CVE-2016-7240, CVE-2016-7242, and CVE-2016-7243.

### [CVE-2016-7202](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7202.md)

- The scripting engines in Microsoft Internet Explorer 9 through 11 and Microsoft Edge allow remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," as demonstrated by the Chakra JavaScript engine, a different vulnerability than CVE-2016-7200, CVE-2016-7201, CVE-2016-7203, CVE-2016-7208, CVE-2016-7240, CVE-2016-7242, and CVE-2016-7243.

### [CVE-2016-7203](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7203.md)

- The Chakra JavaScript scripting engine in Microsoft Edge allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-7200, CVE-2016-7201, CVE-2016-7202, CVE-2016-7208, CVE-2016-7240, CVE-2016-7242, and CVE-2016-7243.

### [CVE-2016-7240](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7240.md)

- The Chakra JavaScript scripting engine in Microsoft Edge allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-7200, CVE-2016-7201, CVE-2016-7202, CVE-2016-7203, CVE-2016-7208, CVE-2016-7242, and CVE-2016-7243.

### [CVE-2016-7241](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7241.md)

- Microsoft Internet Explorer 11 and Microsoft Edge allow remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Microsoft Browser Memory Corruption Vulnerability".

### [CVE-2016-7255](https://github.com/mwrlabs/CVE-2016-7255)

- The kernel-mode drivers in Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, Windows 10 Gold, 1511, and 1607, and Windows Server 2016 allow local users to gain privileges via a crafted application, aka "Win32k Elevation of Privilege Vulnerability."

### [CVE-2016-7286](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7286.md)

- The scripting engines in Microsoft Edge allow remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-7288, CVE-2016-7296, and CVE-2016-7297.

### [CVE-2016-7287](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7287.md)

- The scripting engines in Microsoft Internet Explorer 11 and Microsoft Edge allow remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability".

### [CVE-2016-7288](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7288.md)

- The scripting engines in Microsoft Edge allow remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-7286, CVE-2016-7296, and CVE-2016-7297.

### [CVE-2016-7547](https://gist.github.com/malerisch/b8764501d299f2ec9eb145258d404e5f)

- A command execution flaw on the Trend Micro Threat Discovery Appliance 2.6.1062r1 exists with the timezone parameter in the admin_sys_time.cgi interface.

### [CVE-2016-7552](https://gist.github.com/malerisch/5de8b408443ee9253b3954a62a8d97b4)

- On the Trend Micro Threat Discovery Appliance 2.6.1062r1, directory traversal when processing a session_id cookie allows a remote, unauthenticated attacker to delete arbitrary files as root. This can be used to bypass authentication or cause a DoS.

### [CVE-2016-8413](https://github.com/derrekr/android_security/blob/master/CVE-2016-8413/msm_infoleak_main.c)

- An information disclosure vulnerability in the Qualcomm camera driver could enable a local malicious application to access data outside of its permission levels. This issue is rated as Moderate because it first requires compromising a privileged process. Product: Android. Versions: Kernel-3.10, Kernel-3.18. Android ID: A-32709702. References: QC-CR#518731.

### [CVE-2016-8477](https://github.com/derrekr/android_security/blob/master/CVE-2016-8477/msm_eeprom_name_infoleak_main.c)

- An information disclosure vulnerability in the Qualcomm camera driver could enable a local malicious application to access data outside of its permission levels. This issue is rated as Moderate because it first requires compromising a privileged process. Product: Android. Versions: Kernel-3.10, Kernel-3.18. Android ID: A-32720522. References: QC-CR#1090007.

### [CVE-2016-8584](https://gist.github.com/malerisch/0b8ecfcb03a2c2f26e5f649cf1df8d33)

- Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier uses predictable session values, which allows remote attackers to bypass authentication by guessing the value.

### [CVE-2016-8585](https://gist.github.com/malerisch/91239147d4fceffa63006974889ef1af)

- admin_sys_time.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code as the root user via shell metacharacters in the timezone parameter.

### [CVE-2016-8586](https://gist.github.com/malerisch/97c160aa4e8219c7c9ad25107444a280)

- detected_potential_files.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code as the root user via shell metacharacters in the cache_id parameter.

### [CVE-2016-8587](https://gist.github.com/malerisch/aac1ad3e6f3bfd70b35ba6538ecbff23)

- dlp_policy_upload.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code via an archive file containing a symlink to /eng_ptn_stores/prod/sensorSDK/data/ or /eng_ptn_stores/prod/sensorSDK/backup_pol/.

### [CVE-2016-8588](https://gist.github.com/malerisch/93be2141dfc5709159468762937f2853)

- The hotfix_upload.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code via shell metacharacters in the file name of an uploaded file.

### [CVE-2016-8589](https://gist.github.com/malerisch/3bbb6d0b235fa5af2ba6f05826fe3846)

- log_query_dae.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code as the root user via shell metacharacters in the cache_id parameter.

### [CVE-2016-8590](https://gist.github.com/malerisch/7b84a4bd6eee0a3a591677f421653a2e)

- log_query_dlp.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code as the root user via shell metacharacters in the cache_id parameter.

### [CVE-2016-8591](https://gist.github.com/malerisch/5dd838a723b342bb04121f29a8333e00)

- log_query.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code as the root user via shell metacharacters in the cache_id parameter.

### [CVE-2016-8592](https://gist.github.com/malerisch/0c78e49124561524fd59d6635007eefd)

- log_query_system.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code as the root user via shell metacharacters in the cache_id parameter.

### [CVE-2016-8593](https://gist.github.com/malerisch/c59ab650c8e226ef22cdfbfeeee6d4ec)

- log_query_system.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code as the root user via shell metacharacters in the cache_id parameter.

### [CVE-2016-9651](https://github.com/secmob/pwnfest2016/)

- A missing check for whether a property of a JS object is private in V8 in Google Chrome prior to 55.0.2883.75 allowed a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page.

### [CVE-2016-9793](https://github.com/xairy/kernel-exploits/tree/master/CVE-2016-9793)

- The sock_setsockopt function in net/core/sock.c in the Linux kernel before 4.8.14 mishandles negative values of sk_sndbuf and sk_rcvbuf, which allows local users to cause a denial of service (memory corruption and system crash) or possibly have unspecified other impact by leveraging the CAP_NET_ADMIN capability for a crafted setsockopt system call with the (1) SO_SNDBUFFORCE or (2) SO_RCVBUFFORCE option.

### [CVE-2016-10033](https://exploitbox.io/vuln/WordPress-Exploit-4-6-RCE-CODE-EXEC-CVE-2016-10033.html)

- The mailSend function in the isMail transport in PHPMailer before 5.2.18 might allow remote attackers to pass extra parameters to the mail command and consequently execute arbitrary code via a \" (backslash double quote) in a crafted Sender property.

### [CVE-2016-10191](https://www.secfree.com/article-396.html)

- Heap-based buffer overflow in libavformat/rtmppkt.c in FFmpeg before 2.8.10, 3.0.x before 3.0.5, 3.1.x before 3.1.6, and 3.2.x before 3.2.2 allows remote attackers to execute arbitrary code by leveraging failure to check for RTMP packet size mismatches.

### [CVE-2016-10277](https://alephsecurity.com/2017/05/23/nexus6-initroot/)

- An elevation of privilege vulnerability in the Motorola bootloader could enable a local malicious application to execute arbitrary code within the context of the bootloader. This issue is rated as Critical due to the possibility of a local permanent device compromise, which may require reflashing the operating system to repair the device. Product: Android. Versions: Kernel-3.10, Kernel-3.18. Android ID: A-33840490.

### [CVE-2016-10370](https://alephsecurity.com/2017/05/11/oneplus-ota/)

- An issue was discovered on OnePlus devices such as the 3T. The OnePlus OTA Updater pushes the signed-OTA image over HTTP without TLS. While it does not allow for installation of arbitrary OTAs (due to the digital signature), it unnecessarily increases the attack surface, and allows for remote exploitation of other vulnerabilities such as CVE-2017-5948, CVE-2017-8850, and CVE-2017-8851.

### [CVE-2017-0015](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-0015.md)

- A remote code execution vulnerability exists in the way affected Microsoft scripting engines render when handling objects in memory in Microsoft browsers. These vulnerabilities could corrupt memory in such a way that an attacker could execute arbitrary code in the context of the current user. An attacker who successfully exploited the vulnerability could gain the same user rights as the current user. If the current user is logged on with administrative user rights, an attacker who successfully exploited the vulnerability could take control of an affected system. An attacker could then install programs; view, change, or delete data; or create new accounts with full user rights. This vulnerability is different from those described in CVE-2017-0010, CVE-2017-0032, CVE-2017-0035, CVE-2017-0067, CVE-2017-0070, CVE-2017-0071, CVE-2017-0094, CVE-2017-0131, CVE-2017-0132, CVE-2017-0133, CVE-2017-0134, CVE-2017-0136, CVE-2017-0137, CVE-2017-0138, CVE-2017-0141, CVE-2017-0150, and CVE-2017-0151.

### [CVE-2017-0037](https://redr2e.com/cve-to-poc-cve-2017-0037/)

- Microsoft Internet Explorer 10 and 11 and Microsoft Edge have a type confusion issue in the Layout::MultiColumnBoxBuilder::HandleColumnBreakOnColumnSpanningElement function in mshtml.dll, which allows remote attackers to execute arbitrary code via vectors involving a crafted Cascading Style Sheets (CSS) token sequence and crafted JavaScript code that operates on a TH element.

### [CVE-2017-0059](https://redr2e.com/cve-to-poc-cve-2017-0059/)

- Microsoft Internet Explorer 9 through 11 allow remote attackers to obtain sensitive information from process memory via a crafted web site, aka "Internet Explorer Information Disclosure Vulnerability." This vulnerability is different from those described in CVE-2017-0008 and CVE-2017-0009.

### [CVE-2017-0070](CVE-2017-0070.md)

- A remote code execution vulnerability exists in the way affected Microsoft scripting engines render when handling objects in memory in Microsoft browsers. These vulnerabilities could corrupt memory in such a way that an attacker could execute arbitrary code in the context of the current user. An attacker who successfully exploited the vulnerability could gain the same user rights as the current user. If the current user is logged on with administrative user rights, an attacker who successfully exploited the vulnerability could take control of an affected system. An attacker could then install programs; view, change, or delete data; or create new accounts with full user rights. This vulnerability is different from those described in CVE-2017-0010, CVE-2017-0015, CVE-2017-0032, CVE-2017-0035, CVE-2017-0067, CVE-2017-0071, CVE-2017-0094, CVE-2017-0131, CVE-2017-0132, CVE-2017-0133, CVE-2017-0134, CVE-2017-0136, CVE-2017-0137, CVE-2017-0138, CVE-2017-0141, CVE-2017-0150, and CVE-2017-0151.

### [CVE-2017-0071](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-0071.md)

- A remote code execution vulnerability exists in the way affected Microsoft scripting engines render when handling objects in memory in Microsoft browsers. These vulnerabilities could corrupt memory in such a way that an attacker could execute arbitrary code in the context of the current user. An attacker who successfully exploited the vulnerability could gain the same user rights as the current user. If the current user is logged on with administrative user rights, an attacker who successfully exploited the vulnerability could take control of an affected system. An attacker could then install programs; view, change, or delete data; or create new accounts with full user rights. This vulnerability is different from those described in CVE-2017-0010, CVE-2017-0015, CVE-2017-0032, CVE-2017-0035, CVE-2017-0067, CVE-2017-0070, CVE-2017-0094, CVE-2017-0131, CVE-2017-0132, CVE-2017-0133, CVE-2017-0134, CVE-2017-0136, CVE-2017-0137, CVE-2017-0138, CVE-2017-0141, CVE-2017-0150, and CVE-2017-0151.

### [CVE-2017-0134](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-0134.md)

- A remote code execution vulnerability exists in the way affected Microsoft scripting engines render when handling objects in memory in Microsoft browsers. These vulnerabilities could corrupt memory in such a way that an attacker could execute arbitrary code in the context of the current user. An attacker who successfully exploited the vulnerability could gain the same user rights as the current user. If the current user is logged on with administrative user rights, an attacker who successfully exploited the vulnerability could take control of an affected system. An attacker could then install programs; view, change, or delete data; or create new accounts with full user rights. This vulnerability is different from those described in CVE-2017-0010, CVE-2017-0015, CVE-2017-0032, CVE-2017-0035, CVE-2017-0067, CVE-2017-0070, CVE-2017-0071, CVE-2017-0094, CVE-2017-0131, CVE-2017-0132, CVE-2017-0133, CVE-2017-0136, CVE-2017-0137, CVE-2017-0138, CVE-2017-0141, CVE-2017-0150, and CVE-2017-0151.

### [CVE-2017-0135](https://medium.com/bugbountywriteup/bypass-csp-by-abusing-xss-filter-in-edge-43e9106a9754)

- Microsoft Edge allows remote attackers to bypass the Same Origin Policy for HTML elements in other browser windows, aka "Microsoft Edge Security Feature Bypass Vulnerability." This vulnerability is different from those described in CVE-2017-0066 and CVE-2017-0140.

### [CVE-2017-0141](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-0141.md)

- A remote code execution vulnerability exists in the way affected Microsoft scripting engines render when handling objects in memory in Microsoft browsers. These vulnerabilities could corrupt memory in such a way that an attacker could execute arbitrary code in the context of the current user. An attacker who successfully exploited the vulnerability could gain the same user rights as the current user. If the current user is logged on with administrative user rights, an attacker who successfully exploited the vulnerability could take control of an affected system. An attacker could then install programs; view, change, or delete data; or create new accounts with full user rights. This vulnerability is different from those described in CVE-2017-0010, CVE-2017-0015, CVE-2017-0032, CVE-2017-0035, CVE-2017-0067, CVE-2017-0070, CVE-2017-0071, CVE-2017-0094, CVE-2017-0131, CVE-2017-0132, CVE-2017-0133, CVE-2017-0134, CVE-2017-0136, CVE-2017-0137, CVE-2017-0138, CVE-2017-0150, and CVE-2017-0151.

### [CVE-2017-0143](MS17-010.md)

- The SMBv1 server in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607; and Windows Server 2016 allows remote attackers to execute arbitrary code via crafted packets, aka "Windows SMB Remote Code Execution Vulnerability." This vulnerability is different from those described in CVE-2017-0144, CVE-2017-0145, CVE-2017-0146, and CVE-2017-0148.

### [CVE-2017-0144](MS17-010.md)

- The SMBv1 server in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607; and Windows Server 2016 allows remote attackers to execute arbitrary code via crafted packets, aka "Windows SMB Remote Code Execution Vulnerability." This vulnerability is different from those described in CVE-2017-0143, CVE-2017-0145, CVE-2017-0146, and CVE-2017-0148.

### [CVE-2017-0145](MS17-010.md)

- The SMBv1 server in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607; and Windows Server 2016 allows remote attackers to execute arbitrary code via crafted packets, aka "Windows SMB Remote Code Execution Vulnerability." This vulnerability is different from those described in CVE-2017-0143, CVE-2017-0144, CVE-2017-0146, and CVE-2017-0148.

### [CVE-2017-0146](MS17-010.md)

- The SMBv1 server in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607; and Windows Server 2016 allows remote attackers to execute arbitrary code via crafted packets, aka "Windows SMB Remote Code Execution Vulnerability." This vulnerability is different from those described in CVE-2017-0143, CVE-2017-0144, CVE-2017-0145, and CVE-2017-0148.

### [CVE-2017-0147](MS17-010.md)

- The SMBv1 server in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607; and Windows Server 2016 allows remote attackers to obtain sensitive information from process memory via a crafted packets, aka "Windows SMB Information Disclosure Vulnerability."

### [CVE-2017-0148](MS17-010.md)

- The SMBv1 server in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607; and Windows Server 2016 allows remote attackers to execute arbitrary code via crafted packets, aka "Windows SMB Remote Code Execution Vulnerability." This vulnerability is different from those described in CVE-2017-0143, CVE-2017-0144, CVE-2017-0145, and CVE-2017-0146.

### [CVE-2017-0199](CVE-2017-0199.md)

- Microsoft Office 2007 SP3, Microsoft Office 2010 SP2, Microsoft Office 2013 SP1, Microsoft Office 2016, Microsoft Windows Vista SP2, Windows Server 2008 SP2, Windows 7 SP1, Windows 8.1 allow remote attackers to execute arbitrary code via a crafted document, aka "Microsoft Office/WordPad Remote Code Execution Vulnerability w/Windows API."

### [CVE-2017-0213](https://github.com/WindowsExploits/Exploits/tree/master/CVE-2017-0213)

- Windows COM Aggregate Marshaler in Microsoft Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, Windows 10 Gold, 1511, 1607, and 1703, and Windows Server 2016 allows an elevation privilege vulnerability when an attacker runs a specially crafted application, aka "Windows COM Elevation of Privilege Vulnerability". This CVE ID is unique from CVE-2017-0214.

### [CVE-2017-0234](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-0234.md)

- A remote code execution vulnerability exists in Microsoft Edge in the way that the Chakra JavaScript engine renders when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability." This CVE ID is unique from CVE-2017-0224, CVE-2017-0228, CVE-2017-0229, CVE-2017-0230, CVE-2017-0235, CVE-2017-0236, and CVE-2017-0238.

### [CVE-2017-0236](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-0236.md)

- A remote code execution vulnerability exists in Microsoft Edge in the way that the Chakra JavaScript engine renders when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability." This CVE ID is unique from CVE-2017-0224, CVE-2017-0228, CVE-2017-0229, CVE-2017-0230, CVE-2017-0234, CVE-2017-0235, and CVE-2017-0238.

### [CVE-2017-0263](https://www.exploit-db.com/exploits/44478/)

- The kernel-mode drivers in Microsoft Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allow local users to gain privileges via a crafted application, aka "Win32k Elevation of Privilege Vulnerability."

### [CVE-2017-0283](https://0patch.blogspot.tw/2017/07/0patching-quick-brown-fox-of-cve-2017.html)

- Uniscribe in Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, Windows 10 Gold, 1511, 1607, Windows Server 2016, Microsoft Office 2007 SP3, Microsoft Office 2010 SP2, Microsoft Office Word Viewer, Microsoft Lync 2013 SP1, Skype for Business 2016, Microsoft Silverlight 5 Developer Runtime when installed on Microsoft Windows, and Microsoft Silverlight 5 when installed on Microsoft Windows allows a remote code execution vulnerability due to the way it handles objects in memory, aka "Windows Uniscribe Remote Code Execution Vulnerability". This CVE ID is unique from CVE-2017-8528.

### [CVE-2017-0290](CVE-2017-0290.md)

- NScript in mpengine in Microsoft Malware Protection Engine with Engine Version before 1.1.13704.0, as used in Windows Defender and other products, allows remote attackers to execute arbitrary code or cause a denial of service (type confusion and application crash) via crafted JavaScript code within any file scanned by this engine.

### [CVE-2017-0392](https://github.com/derrekr/android_security/blob/master/CVE-2017-0392)

- A denial of service vulnerability in VBRISeeker.cpp in libstagefright in Mediaserver could enable a remote attacker to use a specially crafted file to cause a device hang or reboot. This issue is rated as High due to the possibility of remote denial of service. Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1. Android ID: A-32577290.

### [CVE-2017-0474](https://github.com/V-E-O/PoC/tree/master/CVE-2017-0474)

- A remote code execution vulnerability in Mediaserver could enable an attacker using a specially crafted file to cause memory corruption during media file and data processing. This issue is rated as Critical due to the possibility of remote code execution within the context of the Mediaserver process. Product: Android. Versions: 7.0, 7.1.1. Android ID: A-32589224.

### [CVE-2017-0475](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0475)

- An elevation of privilege vulnerability in the recovery verifier could enable a local malicious application to execute arbitrary code within the context of the kernel. This issue is rated as Critical due to the possibility of a local permanent device compromise, which may require reflashing the operating system to repair the device. Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1. Android ID: A-31914369.

### [CVE-2017-0497](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0497)

- A denial of service vulnerability in Mediaserver could enable an attacker to use a specially crafted file to cause a device hang or reboot. This issue is rated as Moderate because it requires an uncommon device configuration. Product: Android. Versions: 7.0, 7.1.1. Android ID: A-33300701.

### [CVE-2017-0521](https://github.com/derrekr/android_security/tree/master/CVE-2017-0521)

- An elevation of privilege vulnerability in the Qualcomm camera driver could enable a local malicious application to execute arbitrary code within the context of the kernel. This issue is rated as High because it first requires compromising a privileged process. Product: Android. Versions: Kernel-3.10, Kernel-3.18. Android ID: A-32919951. References: QC-CR#1097709.

### [CVE-2017-0531](https://github.com/derrekr/android_security/blob/master/CVE-2017-0531/msm_lsm_client_lab_main.c)

- An information disclosure vulnerability in the Qualcomm Wi-Fi driver could enable a local malicious application to access data outside of its permission levels. This issue is rated as Moderate because it first requires compromising a privileged process. Product: Android. Versions: Kernel-3.10, Kernel-3.18. Android ID: A-32877245. References: QC-CR#1087469.

### [CVE-2017-0541](https://github.com/JiounDai/CVE-2017-0541)

- A remote code execution vulnerability in sonivox in Mediaserver could enable an attacker using a specially crafted file to cause memory corruption during media file and data processing. This issue is rated as Critical due to the possibility of remote code execution within the context of the Mediaserver process. Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1. Android ID: A-34031018.

### [CVE-2017-0548](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0548)

- A remote denial of service vulnerability in libskia could enable an attacker to use a specially crafted file to cause a device hang or reboot. This issue is rated as High severity due to the possibility of remote denial of service. Product: Android. Versions: 7.0, 7.1.1. Android ID: A-33251605.

### [CVE-2017-0576](https://github.com/derrekr/android_security/blob/master/CVE-2017-0576/qcom_qcedev_byteoffset_overflow.c)

- An elevation of privilege vulnerability in the Qualcomm crypto engine driver could enable a local malicious application to execute arbitrary code within the context of the kernel. This issue is rated as High because it first requires compromising a privileged process. Product: Android. Versions: Kernel-3.10, Kernel-3.18. Android ID: A-33544431. References: QC-CR#1103089.

### [CVE-2017-0641](https://github.com/V-E-O/PoC/tree/master/CVE-2017-0641)

- A remote denial of service vulnerability in libvpx in Mediaserver could enable an attacker to use a specially crafted file to cause a device hang or reboot. This issue is rated as High severity due to the possibility of remote denial of service. Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-34360591.

### [CVE-2017-0678](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0678)

- A remote code execution vulnerability in the Android media framework. Product: Android. Versions: 7.0, 7.1.1, 7.1.2. Android ID: A-36576151.

### [CVE-2017-0714](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0714)

- A remote code execution vulnerability in the Android media framework (h263 decoder). Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-36492637.

### [CVE-2017-0718](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0718)

- A remote code execution vulnerability in the Android media framework (mpeg2 decoder). Product: Android. Versions: 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-37273547.

### [CVE-2017-0719](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0719)

- A remote code execution vulnerability in the Android media framework (mpeg2 decoder). Product: Android. Versions: 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-37273673.

### [CVE-2017-0720](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0720)

- A remote code execution vulnerability in the Android media framework (libhevc). Product: Android. Versions: 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-37430213.

### [CVE-2017-0722](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0722)

- A remote code execution vulnerability in the Android media framework (h263 decoder). Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-37660827.

### [CVE-2017-0745](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0745)

- A remote code execution vulnerability in the Android media framework (avc decoder). Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-37079296.

### [CVE-2017-0758](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0758)

- A remote code execution vulnerability in the Android media framework (libhevc). Product: Android. Versions: 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-36492741.

### [CVE-2017-0760](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0760)

- A remote code execution vulnerability in the Android media framework (libstagefright). Product: Android. Versions: 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-37237396.

### [CVE-2017-0761](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0761)

- A remote code execution vulnerability in the Android media framework (libavc). Product: Android. Versions: 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2, 8.0. Android ID: A-38448381.

### [CVE-2017-0764](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0764)

- A remote code execution vulnerability in the Android media framework (libvorbis). Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2, 8.0. Android ID: A-62872015.

### [CVE-2017-0776](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0776)

- A information disclosure vulnerability in the Android media framework (n/a). Product: Android. Versions: 7.0, 7.1.1, 7.1.2, 8.0. Android ID: A-38496660.

### [CVE-2017-0777](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0777)

- A information disclosure vulnerability in the Android media framework (n/a). Product: Android. Versions: 7.0, 7.1.1, 7.1.2. Android ID: A-38342499.

### [CVE-2017-0778](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0778)

- A information disclosure vulnerability in the Android media framework (n/a). Product: Android. Versions: 7.0, 7.1.1, 7.1.2. Android ID: A-62133227.

### [CVE-2017-0781](CVE-2017-0781.md)

- A remote code execution vulnerability in the Android system (bluetooth). Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2, 8.0. Android ID: A-63146105.

### [CVE-2017-0785](https://github.com/ojasookert/CVE-2017-0785)

- A information disclosure vulnerability in the Android system (bluetooth). Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2, 8.0. Android ID: A-63146698.

### [CVE-2017-0813](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0813)

- A denial of service vulnerability in the Android media framework (libstagefright). Product: Android. Versions: 7.0, 7.1.1, 7.1.2. Android ID: A-36531046.

### [CVE-2017-0814](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0814)

- An information disclosure vulnerability in the Android media framework (n/a). Product: Android. Versions: 7.0, 7.1.1, 7.1.2, 8.0. Android ID: A-62800140.

### [CVE-2017-0820](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0820)

- A vulnerability in the Android media framework (n/a). Product: Android. Versions: 7.0, 7.1.1, 7.1.2, 8.0. Android ID: A-62187433.

### [CVE-2017-1082](Stack-Clash.md)

- In FreeBSD 11.x before 11.1-RELEASE and 10.x before 10.4-RELEASE, the qsort algorithm has a deterministic recursion pattern. Feeding a pathological input to the algorithm can lead to excessive stack usage and potential overflow. Applications that use qsort to handle large data set may crash if the input follows the pathological pattern.

### [CVE-2017-1083](Stack-Clash.md)

- In FreeBSD before 11.2-RELEASE, a stack guard-page is available but is disabled by default. This results in the possibility a poorly written process could be cause a stack overflow.

### [CVE-2017-1084](Stack-Clash.md)

- In FreeBSD before 11.2-RELEASE, multiple issues with the implementation of the stack guard-page reduce the protections afforded by the guard-page. This results in the possibility a poorly written process could be cause a stack overflow.

### [CVE-2017-1085](Stack-Clash.md)

- In FreeBSD before 11.2-RELEASE, an application which calls setrlimit() to increase RLIMIT_STACK may turn a read-only memory region below the stack into a read-write region. A specially crafted executable could be exploited to execute arbitrary code in the user context.

### [CVE-2017-2363](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2017-2363)

- An issue was discovered in certain Apple products. iOS before 10.2.1 is affected. Safari before 10.0.3 is affected. tvOS before 10.1.1 is affected. watchOS before 3.1.3 is affected. The issue involves the "WebKit" component. It allows remote attackers to bypass the Same Origin Policy and obtain sensitive information via a crafted web site.

### [CVE-2017-2364](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2017-2364)

- An issue was discovered in certain Apple products. iOS before 10.2.1 is affected. Safari before 10.0.3 is affected. The issue involves the "WebKit" component. It allows remote attackers to bypass the Same Origin Policy and obtain sensitive information via a crafted web site.

### [CVE-2017-2365](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2017-2365)

- An issue was discovered in certain Apple products. iOS before 10.2.1 is affected. Safari before 10.0.3 is affected. tvOS before 10.1.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to bypass the Same Origin Policy and obtain sensitive information via a crafted web site.

### [CVE-2017-2367](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2017-2367)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to bypass the Same Origin Policy and obtain sensitive information via a crafted web site.

### [CVE-2017-2416](https://blog.flanker017.me/cve-2017-2416-gif-remote-exec/)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. macOS before 10.12.4 is affected. tvOS before 10.2 is affected. watchOS before 3.2 is affected. The issue involves the "ImageIO" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted image file.

### [CVE-2017-2419](http://blog.talosintelligence.com/2017/09/vulnerability-spotlight-content.html)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to bypass a Content Security Policy protection mechanism via unspecified vectors.

### [CVE-2017-2426](https://s1gnalcha0s.github.io/ibooks/epub/2017/03/27/This-book-reads-you-using-JavaScript.html)

- An issue was discovered in certain Apple products. macOS before 10.12.4 is affected. The issue involves the "iBooks" component. It allows remote attackers to obtain sensitive information from local files via a file: URL in an iBooks file.

### [CVE-2017-2442](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2017-2442)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. The issue involves the "WebKit JavaScript Bindings" component. It allows remote attackers to bypass the Same Origin Policy and obtain sensitive information via a crafted web site.

### [CVE-2017-2445](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2017-2445)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to conduct Universal XSS (UXSS) attacks via crafted frame objects.

### [CVE-2017-2446](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2446.md)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code via a crafted web site that leverages the mishandling of strict mode functions.

### [CVE-2017-2447](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2447.md)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to obtain sensitive information or cause a denial of service (memory corruption) via a crafted web site.

### [CVE-2017-2460](http://www.uaf.li/2018/02/three-uaf-when-iterating-through.html)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-2464](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2464.md)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-2468](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2017-2468)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-2475](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2017-2475)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to conduct Universal XSS (UXSS) attacks via crafted use of frames on a web site.

### [CVE-2017-2479](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2017-2479)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. iCloud before 6.2 on Windows is affected. iTunes before 12.6 on Windows is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to bypass the Same Origin Policy and obtain sensitive information via a crafted web site.

### [CVE-2017-2480](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2017-2480)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. iCloud before 6.2 on Windows is affected. iTunes before 12.6 on Windows is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to bypass the Same Origin Policy and obtain sensitive information via a crafted web site.

### [CVE-2017-2491](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2491.md)

- Use after free vulnerability in the String.replace method JavaScriptCore in Apple Safari in iOS before 10.3 allows remote attackers to execute arbitrary code via a crafted web page, or a crafted file.

### [CVE-2017-2493](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2017-2493)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. iCloud before 6.2 on Windows is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to bypass the Same Origin Policy and obtain sensitive information via a crafted elements on a web site.

### [CVE-2017-2504](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2017-2504)

- An issue was discovered in certain Apple products. iOS before 10.3.2 is affected. Safari before 10.1.1 is affected. tvOS before 10.2.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to conduct Universal XSS (UXSS) attacks via a crafted web site that improperly interacts with WebKit Editor commands.

### [CVE-2017-2508](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2017-2508)

- An issue was discovered in certain Apple products. iOS before 10.3.2 is affected. Safari before 10.1.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to conduct Universal XSS (UXSS) attacks via a crafted web site that improperly interacts with container nodes.

### [CVE-2017-2510](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2017-2510)

- An issue was discovered in certain Apple products. iOS before 10.3.2 is affected. Safari before 10.1.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to conduct Universal XSS (UXSS) attacks via a crafted web site that improperly interacts with pageshow events.

### [CVE-2017-2521](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2521.md)

- An issue was discovered in certain Apple products. iOS before 10.3.2 is affected. Safari before 10.1.1 is affected. tvOS before 10.2.1 is affected. watchOS before 3.2.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-2528](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2017-2528)

- An issue was discovered in certain Apple products. iOS before 10.3.2 is affected. Safari before 10.1.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to conduct Universal XSS (UXSS) attacks via a crafted web site that improperly interacts with cached frames.

### [CVE-2017-2531](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2531.md)

- An issue was discovered in certain Apple products. iOS before 10.3.2 is affected. Safari before 10.1.1 is affected. tvOS before 10.2.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-2536](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2536.md)

- An issue was discovered in certain Apple products. iOS before 10.3.2 is affected. Safari before 10.1.1 is affected. tvOS before 10.2.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-2540](https://github.com/theori-io/zer0con2018_singi)

- An issue was discovered in certain Apple products. macOS before 10.12.5 is affected. The issue involves the "WindowServer" component. It allows attackers to bypass intended memory-read restrictions via a crafted app.

### [CVE-2017-2541](https://github.com/theori-io/zer0con2018_singi)

- An issue was discovered in certain Apple products. macOS before 10.12.5 is affected. The issue involves the "WindowServer" component. It allows attackers to execute arbitrary code in a privileged context or cause a denial of service (memory corruption) via a crafted app.

### [CVE-2017-2547](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2547.md)

- An issue was discovered in certain Apple products. iOS before 10.3.2 is affected. Safari before 10.1.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-2636](https://a13xp0p0v.github.io/2017/03/24/CVE-2017-2636.html)

- Race condition in drivers/tty/n_hdlc.c in the Linux kernel through 4.10.1 allows local users to gain privileges or cause a denial of service (double free) by setting the HDLC line discipline.

### [CVE-2017-2641](http://netanelrub.in/2017/03/20/moodle-remote-code-execution/)

- In Moodle 2.x and 3.x, SQL injection can occur via user preferences.

### [CVE-2017-3066](https://github.com/codewhitesec/ColdFusionPwn)

- Adobe ColdFusion 2016 Update 3 and earlier, ColdFusion 11 update 11 and earlier, ColdFusion 10 Update 22 and earlier have a Java deserialization vulnerability in the Apache BlazeDS library. Successful exploitation could lead to arbitrary code execution.

### [CVE-2017-3248](https://github.com/quentinhardy/scriptsAndExploits)

- Vulnerability in the Oracle WebLogic Server component of Oracle Fusion Middleware (subcomponent: Core Components). Supported versions that are affected are 10.3.6.0, 12.1.3.0, 12.2.1.0 and 12.2.1.1. Easily exploitable vulnerability allows unauthenticated attacker with network access via T3 to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS v3.0 Base Score 9.8 (Confidentiality, Integrity and Availability impacts).

### [CVE-2017-3506](https://www.anquanke.com/post/id/92003)

- Vulnerability in the Oracle WebLogic Server component of Oracle Fusion Middleware (subcomponent: Web Services). Supported versions that are affected are 10.3.6.0, 12.1.3.0, 12.2.1.0, 12.2.1.1 and 12.2.1.2. Difficult to exploit vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in unauthorized creation, deletion or modification access to critical data or all Oracle WebLogic Server accessible data as well as unauthorized access to critical data or complete access to all Oracle WebLogic Server accessible data. CVSS 3.0 Base Score 7.4 (Confidentiality and Integrity impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:H/PR:N/UI:N/S:U/C:H/I:H/A:N).

### [CVE-2017-3599](https://github.com/SECFORCE/CVE-2017-3599/blob/master/cve-2017-3599_poc.py)

- Vulnerability in the MySQL Server component of Oracle MySQL (subcomponent: Server: Pluggable Auth). Supported versions that are affected are 5.6.35 and earlier and 5.7.17 and earlier. Easily "exploitable" vulnerability allows unauthenticated attacker with network access via multiple protocols to compromise MySQL Server. Successful attacks of this vulnerability can result in unauthorized ability to cause a hang or frequently repeatable crash (complete DOS) of MySQL Server. CVSS 3.0 Base Score 7.5 (Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H). NOTE: the previous information is from the April 2017 CPU. Oracle has not commented on third-party claims that this issue is an integer overflow in sql/auth/sql_authentication.cc which allows remote attackers to cause a denial of service via a crafted authentication packet.

### [CVE-2017-3629](Stack-Clash.md)

- Vulnerability in the Solaris component of Oracle Sun Systems Products Suite (subcomponent: Kernel). Supported versions that are affected are 10 and 11. Easily exploitable vulnerability allows low privileged attacker with logon to the infrastructure where Solaris executes to compromise Solaris. Successful attacks of this vulnerability can result in takeover of Solaris. CVSS 3.0 Base Score 7.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H).

### [CVE-2017-3630](Stack-Clash.md)

- Vulnerability in the Solaris component of Oracle Sun Systems Products Suite (subcomponent: Kernel). Supported versions that are affected are 10 and 11. Easily exploitable vulnerability allows low privileged attacker with logon to the infrastructure where Solaris executes to compromise Solaris. Successful attacks of this vulnerability can result in unauthorized update, insert or delete access to some of Solaris accessible data as well as unauthorized read access to a subset of Solaris accessible data and unauthorized ability to cause a partial denial of service (partial DOS) of Solaris. CVSS 3.0 Base Score 5.3 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L).

### [CVE-2017-3631](Stack-Clash.md)

- Vulnerability in the Solaris component of Oracle Sun Systems Products Suite (subcomponent: Kernel). The supported version that is affected is 11. Easily exploitable vulnerability allows low privileged attacker with logon to the infrastructure where Solaris executes to compromise Solaris. Successful attacks of this vulnerability can result in unauthorized update, insert or delete access to some of Solaris accessible data as well as unauthorized read access to a subset of Solaris accessible data and unauthorized ability to cause a partial denial of service (partial DOS) of Solaris. CVSS 3.0 Base Score 5.3 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L).

### [CVE-2017-3881](https://github.com/artkond/cisco-rce)

- A vulnerability in the Cisco Cluster Management Protocol (CMP) processing code in Cisco IOS and Cisco IOS XE Software could allow an unauthenticated, remote attacker to cause a reload of an affected device or remotely execute code with elevated privileges. The Cluster Management Protocol utilizes Telnet internally as a signaling and command protocol between cluster members. The vulnerability is due to the combination of two factors: (1) the failure to restrict the use of CMP-specific Telnet options only to internal, local communications between cluster members and instead accept and process such options over any Telnet connection to an affected device; and (2) the incorrect processing of malformed CMP-specific Telnet options. An attacker could exploit this vulnerability by sending malformed CMP-specific Telnet options while establishing a Telnet session with an affected Cisco device configured to accept Telnet connections. An exploit could allow an attacker to execute arbitrary code and obtain full control of the device or cause a reload of the affected device. This affects Catalyst switches, Embedded Service 2020 switches, Enhanced Layer 2 EtherSwitch Service Module, Enhanced Layer 2/3 EtherSwitch Service Module, Gigabit Ethernet Switch Module (CGESM) for HP, IE Industrial Ethernet switches, ME 4924-10GE switch, RF Gateway 10, and SM-X Layer 2/3 EtherSwitch Service Module. Cisco Bug IDs: CSCvd48893.

### [CVE-2017-4901](https://github.com/unamer/vmware_escape)

- The drag-and-drop (DnD) function in VMware Workstation 12.x before version 12.5.4 and Fusion 8.x before version 8.5.5 has an out-of-bounds memory access vulnerability. This may allow a guest to execute code on the operating system that runs Workstation or Fusion.

### [CVE-2017-4914](https://www.exploit-db.com/exploits/42152/)

- VMware vSphere Data Protection (VDP) 6.1.x, 6.0.x, 5.8.x, and 5.5.x contains a deserialization issue. Exploitation of this issue may allow a remote attacker to execute commands on the appliance.

### [CVE-2017-4915](https://www.exploit-db.com/exploits/43449/)

- VMware Workstation Pro/Player contains an insecure library loading vulnerability via ALSA sound driver configuration files. Successful exploitation of this issue may allow unprivileged host users to escalate their privileges to root in a Linux host machine.

### [CVE-2017-4918](https://bogner.sh/2017/07/cve-2017-4918-code-injection-in-vmware-horizons-macos-client/)

- VMware Horizon View Client (2.x, 3.x and 4.x prior to 4.5.0) contains a command injection vulnerability in the service startup script. Successful exploitation of this issue may allow unprivileged users to escalate their privileges to root on the Mac OSX system where the client is installed.

### [CVE-2017-4933](https://www.talosintelligence.com/reports/TALOS-2017-0368)

- VMware ESXi (6.5 before ESXi650-201710401-BG), Workstation (12.x before 12.5.8), and Fusion (8.x before 8.5.9) contain a vulnerability that could allow an authenticated VNC session to cause a heap overflow via a specific set of VNC packets resulting in heap corruption. Successful exploitation of this issue could result in remote code execution in a virtual machine via the authenticated VNC session. Note: In order for exploitation to be possible in ESXi, VNC must be manually enabled in a virtual machine's .vmx configuration file. In addition, ESXi must be configured to allow VNC traffic through the built-in firewall.

### [CVE-2017-4946](https://gosecure.net/2018/01/10/vmware-horizon-v4h-v4pa-desktop-agent-privilege-escalation-vulnerability-cve-2017-4946/)

- The VMware V4H and V4PA desktop agents (6.x before 6.5.1) contain a privilege escalation vulnerability. Successful exploitation of this issue could result in a low privileged windows user escalating their privileges to SYSTEM.

### [CVE-2017-4971](http://bobao.360.cn/learning/detail/3963.html)

- An issue was discovered in Pivotal Spring Web Flow through 2.4.4. Applications that do not change the value of the MvcViewFactoryCreator useSpringBinding property which is disabled by default (i.e., set to 'false') can be vulnerable to malicious EL expressions in view states that process form submissions but do not have a sub-element to declare explicit data binding property mappings.

### [CVE-2017-5007](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2017-5007)

- Blink in Google Chrome prior to 56.0.2924.76 for Linux, Windows and Mac, and 56.0.2924.87 for Android, incorrectly handled the sequence of events when closing a page, which allowed a remote attacker to inject arbitrary scripts or HTML (UXSS) via a crafted HTML page.

### [CVE-2017-5008](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2017-5008)

- Blink in Google Chrome prior to 56.0.2924.76 for Linux, Windows and Mac, and 56.0.2924.87 for Android, allowed attacker controlled JavaScript to be run during the invocation of a private script method, which allowed a remote attacker to inject arbitrary scripts or HTML (UXSS) via a crafted HTML page.

### [CVE-2017-5010](https://github.com/Metnew/uxss-db/tree/master/chrome/CVE-2017-5010)

- Blink in Google Chrome prior to 56.0.2924.76 for Linux, Windows and Mac, and 56.0.2924.87 for Android, resolved promises in an inappropriate context, which allowed a remote attacker to inject arbitrary scripts or HTML (UXSS) via a crafted HTML page.

### [CVE-2017-5030](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5030.md)

- Incorrect handling of complex species in V8 in Google Chrome prior to 57.0.2987.98 for Linux, Windows, and Mac and 57.0.2987.108 for Android allowed a remote attacker to execute arbitrary code via a crafted HTML page.

### [CVE-2017-5033](http://blog.talosintelligence.com/2017/09/vulnerability-spotlight-content.html)

- Blink in Google Chrome prior to 57.0.2987.98 for Mac, Windows, and Linux and 57.0.2987.108 for Android failed to correctly propagate CSP restrictions to local scheme pages, which allowed a remote attacker to bypass content security policy via a crafted HTML page.

### [CVE-2017-5040](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5040.md)

- V8 in Google Chrome prior to 57.0.2987.98 for Mac, Windows, and Linux and 57.0.2987.108 for Android was missing a neutering check, which allowed a remote attacker to read values in memory via a crafted HTML page.

### [CVE-2017-5053](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5053.md)

- An out-of-bounds read in V8 in Google Chrome prior to 57.0.2987.133 for Linux, Windows, and Mac, and 57.0.2987.132 for Android, allowed a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page, related to Array.prototype.indexOf.

### [CVE-2017-5070](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5070.md)

- Type confusion in V8 in Google Chrome prior to 59.0.3071.86 for Linux, Windows, and Mac, and 59.0.3071.92 for Android, allowed a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page.

### [CVE-2017-5071](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5071.md)

- Insufficient validation of untrusted input in V8 in Google Chrome prior to 59.0.3071.86 for Linux, Windows and Mac, and 59.0.3071.92 for Android allowed a remote attacker to perform an out of bounds memory read via a crafted HTML page.

### [CVE-2017-5088](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5088.md)

- Insufficient validation of untrusted input in V8 in Google Chrome prior to 59.0.3071.104 for Mac, Windows, and Linux, and 59.0.3071.117 for Android, allowed a remote attacker to perform out of bounds memory access via a crafted HTML page.

### [CVE-2017-5098](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5098.md)

- A use after free in V8 in Google Chrome prior to 60.0.3112.78 for Mac, Windows, Linux, and Android allowed a remote attacker to perform an out of bounds memory read via a crafted HTML page.

### [CVE-2017-5115](https://zon8.re/posts/exploiting-an-accidentally-discovered-v8-rce/)

- Type confusion in V8 in Google Chrome prior to 61.0.3163.79 for Windows allowed a remote attacker to potentially exploit object corruption via a crafted HTML page.

### [CVE-2017-5116](CVE-2017-5116.md)

- Type confusion in V8 in Google Chrome prior to 61.0.3163.79 for Mac, Windows, and Linux, and 61.0.3163.81 for Android, allowed a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page.

### [CVE-2017-5121](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5121.md)

- Inappropriate use of JIT optimisation in V8 in Google Chrome prior to 61.0.3163.100 for Linux, Windows, and Mac allowed a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page, related to the escape analysis phase.

### [CVE-2017-5122](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5122.md)

- Inappropriate use of table size handling in V8 in Google Chrome prior to 61.0.3163.100 for Windows allowed a remote attacker to trigger out-of-bounds access via a crafted HTML page.

### [CVE-2017-5123](CVE-2017-5123.md)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-5124](https://github.com/Bo0oM/CVE-2017-5124/)

- Incorrect application of sandboxing in Blink in Google Chrome prior to 62.0.3202.62 allowed a remote attacker to inject arbitrary scripts or HTML (UXSS) via a crafted MHTML page.

### [CVE-2017-5126](https://bugs.chromium.org/p/chromium/issues/detail?id=760455)

- A use after free in PDFium in Google Chrome prior to 62.0.3202.62 allowed a remote attacker to potentially exploit heap corruption via a crafted PDF file.

### [CVE-2017-5127](https://bugs.chromium.org/p/chromium/issues/detail?id=765384)

- Use after free in PDFium in Google Chrome prior to 62.0.3202.62 allowed a remote attacker to potentially exploit heap corruption via a crafted PDF file.

### [CVE-2017-5128](https://bugs.chromium.org/p/chromium/issues/detail?id=765469)

- Heap buffer overflow in Blink in Google Chrome prior to 62.0.3202.62 allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page, related to WebGL.

### [CVE-2017-5129](https://bugs.chromium.org/p/chromium/issues/detail?id=765495)

- A use after free in WebAudio in Blink in Google Chrome prior to 62.0.3202.62 allowed a remote attacker to perform an out of bounds memory read via a crafted HTML page.

### [CVE-2017-5133](https://bugs.chromium.org/p/chromium/issues/detail?id=762106)

- Off-by-one read/write on the heap in Blink in Google Chrome prior to 62.0.3202.62 allowed a remote attacker to corrupt memory and possibly leak information and potentiality execute code via a crafted PDF file.

### [CVE-2017-5135](https://stringbleed.github.io/)

- Certain Technicolor devices have an SNMP access-control bypass, possibly involving an ISP customization in some cases. The Technicolor (formerly Cisco) DPC3928SL with firmware D3928SL-P15-13-A386-c3420r55105-160127a could be reached by any SNMP community string from the Internet; also, you can write in the MIB because it provides write properties, aka Stringbleed. NOTE: the string-bleed/StringBleed-CVE-2017-5135 GitHub repository is not a valid reference as of 2017-04-27; it contains Trojan horse code purported to exploit this vulnerability.

### [CVE-2017-5622](https://alephsecurity.com/2017/03/26/oneplus3t-adb-charger/)

- With OxygenOS before 4.0.3, when a charger is connected to a powered-off OnePlus 3 or 3T device, the platform starts with adbd enabled. Therefore, a malicious charger or a physical attacker can open up, without authorization, an ADB session with the device, in order to further exploit other vulnerabilities and/or exfiltrate sensitive information.

### [CVE-2017-5624](https://alephsecurity.com/2017/02/08/oneplus3-bootloader-vulns/)

- An issue was discovered in OxygenOS before 4.0.3 for OnePlus 3 and 3T. The attacker can persistently make the (locked) bootloader start the platform with dm-verity disabled, by issuing the 'fastboot oem disable_dm_verity' command. Having dm-verity disabled, the kernel will not verify the system partition (and any other dm-verity protected partition), which may allow for persistent code execution and privilege escalation.

### [CVE-2017-5626](https://alephsecurity.com/2017/02/08/oneplus3-bootloader-vulns/)

- OxygenOS before version 4.0.2, on OnePlus 3 and 3T, has two hidden fastboot oem commands (4F500301 and 4F500302) that allow the attacker to lock/unlock the bootloader, disregarding the 'OEM Unlocking' checkbox, without user confirmation and without a factory reset. This allows for persistent code execution with high privileges (kernel/root) with complete access to user data.

### [CVE-2017-5638](CVE-2017-5638.md)

- The Jakarta Multipart parser in Apache Struts 2 2.3.x before 2.3.32 and 2.5.x before 2.5.10.1 mishandles file upload, which allows remote attackers to execute arbitrary commands via a #cmd= string in a crafted Content-Type HTTP header, as exploited in the wild in March 2017.

### [CVE-2017-5641](http://seclists.org/fulldisclosure/2018/Apr/40)

- Previous versions of Apache Flex BlazeDS (4.7.2 and earlier) did not restrict which types were allowed for AMF(X) object deserialization by default. During the deserialization process code is executed that for several known types has undesired side-effects. Other, unknown types may also exhibit such behaviors. One vector in the Java standard library exists that allows an attacker to trigger possibly further exploitable Java deserialization of untrusted data. Other known vectors in third party libraries can be used to trigger remote code execution.

### [CVE-2017-5689](CVE-2017-5689.md)

- An unprivileged network attacker could gain system privileges to provisioned Intel manageability SKUs: Intel Active Management Technology (AMT) and Intel Standard Manageability (ISM). An unprivileged local attacker could provision manageability features gaining unprivileged network or local system privileges on Intel manageability SKUs: Intel Active Management Technology (AMT), Intel Standard Manageability (ISM), and Intel Small Business Technology (SBT).

### [CVE-2017-5715](CVE-2017-5715.md)

- Systems with microprocessors utilizing speculative execution and indirect branch prediction may allow unauthorized disclosure of information to an attacker with local user access via a side-channel analysis.

### [CVE-2017-5753](CVE-2017-5753.md)

- Systems with microprocessors utilizing speculative execution and branch prediction may allow unauthorized disclosure of information to an attacker with local user access via a side-channel analysis.

### [CVE-2017-5754](CVE-2017-5754.md)

- Systems with microprocessors utilizing speculative execution and indirect branch prediction may allow unauthorized disclosure of information to an attacker with local user access via a side-channel analysis of the data cache.

### [CVE-2017-5891](https://wwws.nightwatchcybersecurity.com/2017/05/09/multiple-vulnerabilities-in-asus-routers/)

- ASUS RT-AC* and RT-N* devices with firmware before 3.0.0.4.380.7378 have Login Page CSRF and Save Settings CSRF.

### [CVE-2017-5892](https://wwws.nightwatchcybersecurity.com/2017/05/09/multiple-vulnerabilities-in-asus-routers/)

- ASUS RT-AC* and RT-N* devices with firmware before 3.0.0.4.380.7378 allow JSONP Information Disclosure such as a network map.

### [CVE-2017-5948](https://alephsecurity.com/2017/05/11/oneplus-ota/)

- An issue was discovered on OnePlus One, X, 2, 3, and 3T devices. OxygenOS and HydrogenOS are vulnerable to downgrade attacks. This is due to a lenient 'updater-script' in OTAs that does not check that the current version is lower than or equal to the given image's. Downgrades can occur even on locked bootloaders and without triggering a factory reset, allowing for exploitation of now-patched vulnerabilities with access to user data. This vulnerability can be exploited by a Man-in-the-Middle (MiTM) attacker targeting the update process. This is possible because the update transaction does not occur over TLS (CVE-2016-10370). In addition, a physical attacker can reboot the phone into recovery, and then use 'adb sideload' to push the OTA (on OnePlus 3/3T 'Secure Start-up' must be off).

### [CVE-2017-6008](https://github.com/cbayet/Exploit-CVE-2017-6008)

- A kernel pool overflow in the driver hitmanpro37.sys in Sophos SurfRight HitmanPro before 3.7.20 Build 286 (included in the HitmanPro.Alert solution and Sophos Clean) allows local users to escalate privileges via a malformed IOCTL call.

### [CVE-2017-6074](https://github.com/xairy/kernel-exploits/tree/master/CVE-2017-6074)

- The dccp_rcv_state_process function in net/dccp/input.c in the Linux kernel through 4.9.11 mishandles DCCP_PKT_REQUEST packet data structures in the LISTEN state, which allows local users to obtain root privileges or cause a denial of service (double free) via an application that makes an IPV6_RECVPKTINFO setsockopt system call.

### [CVE-2017-6178](http://bobao.360.cn/learning/detail/3935.html)

- The IofCallDriver function in USBPcap 1.1.0.0 allows local users to gain privileges via a crafted 0x00090028 IOCTL call, which triggers a NULL pointer dereference.

### [CVE-2017-6198](https://devco.re/blog/2018/01/26/Sandstorm-Security-Review-CVE-2017-6200/)

- The Supervisor in Sandstorm doesn't set and enforce the resource limits of a process. This allows remote attackers to cause a denial of service by launching a fork bomb in the sandbox, or by using a large amount of disk space.

### [CVE-2017-6199](https://sandstorm.io/news/2017-03-02-security-review)

- A remote attacker could bypass the Sandstorm organization restriction before build 0.203 via a comma in an email-address field.

### [CVE-2017-6200](https://sandstorm.io/news/2017-03-02-security-review)

- Sandstorm before build 0.203 allows remote attackers to read any specified file under /etc or /run via the sandbox backup function. The root cause is that the findFilesToZip function doesn't filter Line Feed (\n) characters in a directory name.

### [CVE-2017-6201](https://sandstorm.io/news/2017-03-02-security-review)

- A Server Side Request Forgery vulnerability exists in the install app process in Sandstorm before build 0.203. A remote attacker may exploit this issue by providing a URL. It could bypass access control such as firewalls that prevent the attackers from accessing the URLs directly.

### [CVE-2017-6326](https://pentest.blog/unexpected-journey-5-from-weak-password-to-rce-on-symantec-messaging-gateway/)

- The Symantec Messaging Gateway can encounter an issue of remote code execution, which describes a situation whereby an individual may obtain the ability to execute commands remotely on a target machine or in a target process.

### [CVE-2017-6327](http://seclists.org/fulldisclosure/2017/Aug/28)

- The Symantec Messaging Gateway before 10.6.3-267 can encounter an issue of remote code execution, which describes a situation whereby an individual may obtain the ability to execute commands remotely on a target machine or in a target process. In this type of occurrence, after gaining access to the system, the attacker may attempt to elevate their privileges.

### [CVE-2017-6736](https://github.com/artkond/cisco-snmp-rce)

- The Simple Network Management Protocol (SNMP) subsystem of Cisco IOS 12.0 through 12.4 and 15.0 through 15.6 and IOS XE 2.2 through 3.17 contains multiple vulnerabilities that could allow an authenticated, remote attacker to remotely execute code on an affected system or cause an affected system to reload. An attacker could exploit these vulnerabilities by sending a crafted SNMP packet to an affected system via IPv4 or IPv6. Only traffic directed to an affected system can be used to exploit these vulnerabilities. The vulnerabilities are due to a buffer overflow condition in the SNMP subsystem of the affected software. The vulnerabilities affect all versions of SNMP: Versions 1, 2c, and 3. To exploit these vulnerabilities via SNMP Version 2c or earlier, the attacker must know the SNMP read-only community string for the affected system. To exploit these vulnerabilities via SNMP Version 3, the attacker must have user credentials for the affected system. All devices that have enabled SNMP and have not explicitly excluded the affected MIBs or OIDs should be considered vulnerable. Cisco Bug IDs: CSCve57697.

### [CVE-2017-6980](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-6980.md)

- An issue was discovered in certain Apple products. iOS before 10.3.2 is affected. Safari before 10.1.1 is affected. tvOS before 10.2.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-6984](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-6984.md)

- An issue was discovered in certain Apple products. iOS before 10.3.2 is affected. Safari before 10.1.1 is affected. iTunes before 12.6.1 on Windows is affected. tvOS before 10.2.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-7037](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2017-7037)

- An issue was discovered in certain Apple products. iOS before 10.3.3 is affected. Safari before 10.1.2 is affected. iCloud before 6.2.2 on Windows is affected. iTunes before 12.6.2 on Windows is affected. tvOS before 10.2.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-7056](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-7056.md)

- An issue was discovered in certain Apple products. iOS before 10.3.3 is affected. Safari before 10.1.2 is affected. iCloud before 6.2.2 on Windows is affected. iTunes before 12.6.2 on Windows is affected. tvOS before 10.2.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-7061](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-7061.md)

- An issue was discovered in certain Apple products. iOS before 10.3.3 is affected. Safari before 10.1.2 is affected. iCloud before 6.2.2 on Windows is affected. iTunes before 12.6.2 on Windows is affected. tvOS before 10.2.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-7089](https://github.com/Bo0oM/CVE-2017-7089)

- An issue was discovered in certain Apple products. iOS before 11 is affected. Safari before 11 is affected. iCloud before 7.0 on Windows is affected. The issue involves the "WebKit" component. It allows remote attackers to conduct Universal XSS (UXSS) attacks via a crafted web site that is mishandled during parent-tab processing.

### [CVE-2017-7092](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-7092.md)

- An issue was discovered in certain Apple products. iOS before 11 is affected. Safari before 11 is affected. iCloud before 7.0 on Windows is affected. iTunes before 12.7 on Windows is affected. tvOS before 11 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-7115](https://www.exploit-db.com/exploits/42996/)

- An issue was discovered in certain Apple products. iOS before 11 is affected. tvOS before 11 is affected. The issue involves the "Wi-Fi" component. It might allow remote attackers to execute arbitrary code in a privileged context or cause a denial of service (memory corruption) via crafted Wi-Fi traffic that leverages a race condition.

### [CVE-2017-7117](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-7117.md)

- An issue was discovered in certain Apple products. iOS before 11 is affected. Safari before 11 is affected. iCloud before 7.0 on Windows is affected. iTunes before 12.7 on Windows is affected. tvOS before 11 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-7150](https://objective-see.com/talks/Wardle_SyScan2018.pdf)

- An issue was discovered in certain Apple products. macOS before 10.13 Supplemental Update is affected. The issue involves the "Security" component. It allows attackers to bypass the keychain access prompt, and consequently extract passwords, via a synthetic click.

### [CVE-2017-7219](https://blog.scrt.ch/2017/04/26/heap-overflow-vulnerability-in-citrix-netscaler-gateway-cve-2017-7219/)

- A heap overflow vulnerability in Citrix NetScaler Gateway versions 10.1 before 135.8/135.12, 10.5 before 65.11, 11.0 before 70.12, and 11.1 before 52.13 allows a remote authenticated attacker to run arbitrary commands via unspecified vectors.

### [CVE-2017-7269](https://github.com/zcgonvh/cve-2017-7269-tool)

- Buffer overflow in the ScStoragePathFromUrl function in the WebDAV service in Internet Information Services (IIS) 6.0 in Microsoft Windows Server 2003 R2 allows remote attackers to execute arbitrary code via a long header beginning with "If: <http://" in a PROPFIND request, as exploited in the wild in July or August 2016.

### [CVE-2017-7279](https://rhinosecuritylabs.com/research/remote-code-execution-bug-hunting-chapter-1/)

- An unprivileged user of the Unitrends Enterprise Backup before 9.0.0 web server can escalate to root privileges by modifying the "token" cookie issued at login.

### [CVE-2017-7280](https://rhinosecuritylabs.com/research/remote-code-execution-bug-hunting-chapter-1/)

- An issue was discovered in api/includes/systems.php in Unitrends Enterprise Backup before 9.0.0. User input is not properly filtered before being sent to a popen function. This allows for remote code execution by sending a specially crafted user variable.

### [CVE-2017-7281](https://rhinosecuritylabs.com/research/remote-code-execution-bug-hunting-chapter-1/)

- An issue was discovered in Unitrends Enterprise Backup before 9.1.2. A lack of sanitization of user input in the createReportName and saveReport functions in recoveryconsole/bpl/reports.php allows for an authenticated user to create a randomly named file on disk with a user-controlled extension, contents, and path, leading to remote code execution, aka Unrestricted File Upload.

### [CVE-2017-7282](https://rhinosecuritylabs.com/research/remote-code-execution-bug-hunting-chapter-2/)

- An issue was discovered in Unitrends Enterprise Backup before 9.1.1. The function downloadFile in api/includes/restore.php blindly accepts any filename passed to /api/restore/download as valid. This allows an authenticated attacker to read any file in the filesystem that the web server has access to, aka Local File Inclusion (LFI).

### [CVE-2017-7283](https://rhinosecuritylabs.com/research/remote-code-execution-bug-hunting-chapter-2/)

- An authenticated user of Unitrends Enterprise Backup before 9.1.2 can execute arbitrary OS commands by sending a specially crafted filename to the /api/restore/download-files endpoint, related to the downloadFiles function in api/includes/restore.php.

### [CVE-2017-7293](CVE-2017-7293.md)

- The DAX2API service installed as part of the Realtek Audio Driver on Windows 10 is vulnerable to a privilege escalation vulnerability which allows a normal user to get arbitrary system privileges.

### [CVE-2017-7308](https://github.com/xairy/kernel-exploits/tree/master/CVE-2017-7308)

- The packet_set_ring function in net/packet/af_packet.c in the Linux kernel through 4.10.6 does not properly validate certain block-size data, which allows local users to cause a denial of service (integer signedness error and out-of-bounds write), or gain privileges (if the CAP_NET_RAW capability is held), via crafted system calls.

### [CVE-2017-7344](https://securite.intrinsec.com/2017/12/22/cve-2017-7344-fortinet-forticlient-windows-privilege-escalation-at-logon/)

- A privilege escalation in Fortinet FortiClient Windows 5.4.3 and earlier as well as 5.6.0 allows attacker to gain privilege via exploiting the Windows "security alert" dialog thereby popping up when the "VPN before logon" feature is enabled and an untrusted certificate chain.

### [CVE-2017-7442](https://github.com/rapid7/metasploit-framework/blob/master/modules/exploits/windows/fileformat/nitro_reader_jsapi.rb)

- Nitro Pro 11.0.3.173 allows remote attackers to execute arbitrary code via saveAs and launchURL calls with directory traversal sequences.

### [CVE-2017-7494](CVE-2017-7494.md)

- Samba since version 3.5.0 is vulnerable to remote code execution vulnerability, allowing a malicious client to upload a shared library to a writable share, and then cause the server to load and execute it.

### [CVE-2017-7504](https://github.com/joaomatosf/JavaDeserH2HC)

- HTTPServerILServlet.java in JMS over HTTP Invocation Layer of the JbossMQ implementation, which is enabled by default in Red Hat Jboss Application Server <= Jboss 4.X does not restrict the classes for which it performs deserialization, which allows remote attackers to execute arbitrary code via crafted serialized data.

### [CVE-2017-7525](https://www.secfree.com/article-617.html)

- A deserialization flaw was discovered in the jackson-databind, versions before 2.6.7.1, 2.7.9.1 and 2.8.9, which could allow an unauthenticated user to perform code execution by sending the maliciously crafted input to the readValue method of the ObjectMapper.

### [CVE-2017-7529](https://cert.360.cn/detailnews.html?id=b879782fbad4a7f773b6c18490d67ac7)

- Nginx versions since 0.5.6 up to and including 1.13.2 are vulnerable to integer overflow vulnerability in nginx range filter module resulting into leak of potentially sensitive information triggered by specially crafted request.

### [CVE-2017-7533](https://github.com/hardenedlinux/offensive_poc/tree/master/CVE-2017-7533)

- Race condition in the fsnotify implementation in the Linux kernel through 4.12.4 allows local users to gain privileges or cause a denial of service (memory corruption) via a crafted application that leverages simultaneous execution of the inotify_handle_event and vfs_rename functions.

### [CVE-2017-8046](https://tech.meituan.com/Spring_Data_REST_远程代码执行漏洞(CVE-2017-8046)_分析与复现.html)

- Malicious PATCH requests submitted to spring-data-rest servers in Pivotal Spring Data REST versions prior to 2.5.12, 2.6.7, 3.0 RC3, Spring Boot versions prior to 2.0.0M4, and Spring Data release trains prior to Kay-RC3 can use specially crafted JSON data to run arbitrary Java code.

### [CVE-2017-8291](https://github.com/rapid7/metasploit-framework/blob/master/modules/exploits/unix/fileformat/ghostscript_type_confusion.rb)

- Artifex Ghostscript through 2017-04-26 allows -dSAFER bypass and remote command execution via .rsdparams type confusion with a "/OutputFile (%pipe%" substring in a crafted .eps document that is an input to the gs program, as exploited in the wild in April 2017.

### [CVE-2017-8295](https://github.com/cyberheartmi9/CVE-2017-8295)

- WordPress through 4.7.4 relies on the Host HTTP header for a password-reset e-mail message, which makes it easier for remote attackers to reset arbitrary passwords by making a crafted wp-login.php?action=lostpassword request and then arranging for this message to bounce or be resent, leading to transmission of the reset key to a mailbox on an attacker-controlled SMTP server. This is related to problematic use of the SERVER_NAME variable in wp-includes/pluggable.php in conjunction with the PHP mail function. Exploitation is not achievable in all cases because it requires at least one of the following: (1) the attacker can prevent the victim from receiving any e-mail messages for an extended period of time (such as 5 days), (2) the victim's e-mail system sends an autoresponse containing the original message, or (3) the victim manually composes a reply containing the original message.

### [CVE-2017-8386](https://insinuator.net/2017/05/git-shell-bypass-by-abusing-less-cve-2017-8386/)

- git-shell in git before 2.4.12, 2.5.x before 2.5.6, 2.6.x before 2.6.7, 2.7.x before 2.7.5, 2.8.x before 2.8.5, 2.9.x before 2.9.4, 2.10.x before 2.10.3, 2.11.x before 2.11.2, and 2.12.x before 2.12.3 might allow remote authenticated users to gain privileges via a repository name that starts with a - (dash) character.

### [CVE-2017-8464](CVE-2017-8464.md)

- Windows Shell in Microsoft Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows local users or remote attackers to execute arbitrary code via a crafted .LNK file, which is not properly handled during icon display in Windows Explorer or any other application that parses the icon of the shortcut. aka "LNK Remote Code Execution Vulnerability."

### [CVE-2017-8514](http://respectxss.blogspot.tw/2017/06/a-look-at-cve-2017-8514-sharepoints.html)

- An information disclosure vulnerability exists when Microsoft SharePoint software fails to properly sanitize a specially crafted requests, aka "Microsoft SharePoint Reflective XSS Vulnerability".

### [CVE-2017-8543](http://adlab.venustech.com.cn/article.html?type=vuln_analysis&date=20170718)

- Microsoft Windows XP SP3, Windows XP x64 XP2, Windows Server 2003 SP2, Windows Vista, Windows 7 SP1, Windows Server 2008 SP2 and R2 SP1, Windows 8, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, and 1703, and Windows Server 2016 allow an attacker to take control of the affected system when Windows Search fails to handle objects in memory, aka "Windows Search Remote Code Execution Vulnerability".

### [CVE-2017-8548](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8548.md)

- Microsoft Edge in Microsoft Windows 10 Gold, 1511, 1607, and 1703, and Windows Server 2016 allows an attacker to obtain information to further compromise the user's system when Microsoft Edge improperly handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8499, CVE-2017-8520, CVE-2017-8521, and CVE-2017-8549.

### [CVE-2017-8570](https://mp.weixin.qq.com/s/dMqovzZ70SJgdnfAZtcZMg)

- Microsoft Office allows a remote code execution vulnerability due to the way that it handles objects in memory, aka "Microsoft Office Remote Code Execution Vulnerability". This CVE ID is unique from CVE-2017-0243.

### [CVE-2017-8601](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8601.md)

- Microsoft Edge in Microsoft Windows 10 Gold, 1511, 1607, and 1703, and Windows Server 2016 allow an attacker to execute arbitrary code in the context of the current user when the JavaScript engine fails to render when handling objects in memory in Microsoft Edge, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8596, CVE-2017-8610, CVE-2017-8618, CVE-2017-8619, CVE-2017-8603, CVE-2017-8604, CVE-2017-8605, CVE-2017-8606, CVE-2017-8607, CVE-2017-8608, CVE-2017-8598 and CVE-2017-8609.

### [CVE-2017-8625](https://msitpros.com/?p=3909)

- Internet Explorer in Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows an attacker to bypass Device Guard User Mode Code Integrity (UMCI) policies due to Internet Explorer failing to validate UMCI policies, aka "Internet Explorer Security Feature Bypass Vulnerability".

### [CVE-2017-8634](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8634.md)

- Microsoft Edge in Microsoft Windows 10 1703 allows an attacker to execute arbitrary code in the context of the current user due to the way that Microsoft browser JavaScript engines render content when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8635, CVE-2017-8636, CVE-2017-8638, CVE-2017-8639, CVE-2017-8640, CVE-2017-8641, CVE-2017-8645, CVE-2017-8646, CVE-2017-8647, CVE-2017-8655, CVE-2017-8656, CVE-2017-8657, CVE-2017-8670, CVE-2017-8671, CVE-2017-8672, and CVE-2017-8674.

### [CVE-2017-8636](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8636.md)

- Microsoft browsers in Microsoft Windows 7 SP1, Windows Server 2008 R2 SP1, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allow an attacker to execute arbitrary code in the context of the current user due to the way that Microsoft browser JavaScript engines render content when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8634, CVE-2017-8635, CVE-2017-8638, CVE-2017-8639, CVE-2017-8640, CVE-2017-8641, CVE-2017-8645, CVE-2017-8646, CVE-2017-8647, CVE-2017-8655, CVE-2017-8656, CVE-2017-8657, CVE-2017-8670, CVE-2017-8671, CVE-2017-8672, and CVE-2017-8674.

### [CVE-2017-8640](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8640.md)

- Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user due to the way that Microsoft browser JavaScript engines render content when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8634, CVE-2017-8635, CVE-2017-8636, CVE-2017-8638, CVE-2017-8639, CVE-2017-8641, CVE-2017-8645, CVE-2017-8646, CVE-2017-8647, CVE-2017-8655, CVE-2017-8656, CVE-2017-8657, CVE-2017-8670, CVE-2017-8671, CVE-2017-8672, and CVE-2017-8674.

### [CVE-2017-8645](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8645.md)

- Microsoft Edge in Windows 10 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user due to the way that Microsoft browser JavaScript engines render content when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8634, CVE-2017-8635, CVE-2017-8636, CVE-2017-8638, CVE-2017-8639, CVE-2017-8640, CVE-2017-8641, CVE-2017-8646, CVE-2017-8647, CVE-2017-8655, CVE-2017-8656, CVE-2017-8657, CVE-2017-8670, CVE-2017-8671, CVE-2017-8672, and CVE-2017-8674.

### [CVE-2017-8646](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8646.md)

- Microsoft Edge in Windows 10 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user due to the way that Microsoft browser JavaScript engines render content when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8634, CVE-2017-8635, CVE-2017-8636, CVE-2017-8638, CVE-2017-8639, CVE-2017-8640, CVE-2017-8641, CVE-2017-8645, CVE-2017-8647, CVE-2017-8655, CVE-2017-8656, CVE-2017-8657, CVE-2017-8670, CVE-2017-8671, CVE-2017-8672, and CVE-2017-8674.

### [CVE-2017-8656](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8656.md)

- Microsoft Edge in Microsoft Windows 10 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user due to the way that Microsoft browser JavaScript engines render content when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8634, CVE-2017-8635, CVE-2017-8636, CVE-2017-8638, CVE-2017-8639, CVE-2017-8640, CVE-2017-8641, CVE-2017-8645, CVE-2017-8646, CVE-2017-8647, CVE-2017-8655, CVE-2017-8657, CVE-2017-8670, CVE-2017-8671, CVE-2017-8672, and CVE-2017-8674.

### [CVE-2017-8670](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8670.md)

- Microsoft Edge in Microsoft Windows 10 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user due to the way that Microsoft browser JavaScript engines render content when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8634, CVE-2017-8635, CVE-2017-8636, CVE-2017-8638, CVE-2017-8639, CVE-2017-8640, CVE-2017-8641, CVE-2017-8645, CVE-2017-8646, CVE-2017-8647, CVE-2017-8655, CVE-2017-8656, CVE-2017-8657, CVE-2017-8671, CVE-2017-8672, and CVE-2017-8674.

### [CVE-2017-8671](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8671.md)

- Microsoft Edge in Microsoft Windows 10 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user due to the way that Microsoft browser JavaScript engines render content when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8634, CVE-2017-8635, CVE-2017-8636, CVE-2017-8638, CVE-2017-8639, CVE-2017-8640, CVE-2017-8641, CVE-2017-8645, CVE-2017-8646, CVE-2017-8647, CVE-2017-8655, CVE-2017-8656, CVE-2017-8657, CVE-2017-8670, CVE-2017-8672, and CVE-2017-8674.

### [CVE-2017-8729](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8729.md)

- Microsoft Edge in Microsoft Windows 10 1703 allows an attacker to execute arbitrary code in the context of the current user, due to the way that the Microsoft Edge scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8649, CVE-2017-8660, CVE-2017-8738, CVE-2017-8740, CVE-2017-8741, CVE-2017-8748, CVE-2017-8752, CVE-2017-8753, CVE-2017-8755, CVE-2017-8756, and CVE-2017-11764.

### [CVE-2017-8740](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8740.md)

- Microsoft Edge in Microsoft Windows 10 1703 allows an attacker to execute arbitrary code in the context of the current user, due to the way that the Microsoft Edge scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8649, CVE-2017-8660, CVE-2017-8729, CVE-2017-8738, CVE-2017-8740, CVE-2017-8741, CVE-2017-8748, CVE-2017-8752, CVE-2017-8753, CVE-2017-8755, CVE-2017-8756, and CVE-2017-11764.

### [CVE-2017-8751](https://github.com/tunz/js-vuln-db/blob/426a829e18e07d48ac7beaf7cc05c819f5658939/chakra/CVE-2017-8751.md)

- Microsoft Edge in Microsoft Windows 1703 allows an attacker to execute arbitrary code in the context of the current user, due to the way that Microsoft Edge accesses objects in memory, aka "Microsoft Edge Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8731, CVE-2017-8734, and CVE-2017-11766.

### [CVE-2017-8755](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8755.md)

- Microsoft Edge in Microsoft Windows 10 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to the way that the scripting engine handles objects in memory in Microsoft Edge, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8649, CVE-2017-8649, CVE-2017-8660, CVE-2017-8729, CVE-2017-8738, CVE-2017-8740, CVE-2017-8741, CVE-2017-8748, CVE-2017-8752, CVE-2017-8753, CVE-2017-8756, and CVE-2017-11764.

### [CVE-2017-8759](https://github.com/Voulnet/CVE-2017-8759-Exploit-sample)

- Microsoft .NET Framework 2.0, 3.5, 3.5.1, 4.5.2, 4.6, 4.6.1, 4.6.2 and 4.7 allow an attacker to execute code remotely via a malicious document or application, aka ".NET Framework Remote Code Execution Vulnerability."

### [CVE-2017-8817](https://curl.haxx.se/docs/adv_2017-ae72.html)

- The FTP wildcard function in curl and libcurl before 7.57.0 allows remote attackers to cause a denial of service (out-of-bounds read and application crash) or possibly have unspecified other impact via a string that ends with an '[' character.

### [CVE-2017-8850](https://alephsecurity.com/2017/05/11/oneplus-ota/)

- An issue was discovered on OnePlus One, X, 2, 3, and 3T devices. Due to a lenient updater-script in the OnePlus OTA images, and the fact that both ROMs use the same OTA verification keys, attackers can install HydrogenOS over OxygenOS and vice versa, even on locked bootloaders, which allows for exploitation of vulnerabilities patched on one image but not on the other, in addition to expansion of the attack surface. This vulnerability can be exploited by Man-in-the-Middle (MiTM) attackers targeting the update process. This is possible because the update transaction does not occur over TLS (CVE-2016-10370). In addition, physical attackers can reboot the phone into recovery, and then use 'adb sideload' to push the OTA (on OnePlus 3/3T 'Secure Start-up' must be off).

### [CVE-2017-8851](https://alephsecurity.com/2017/05/11/oneplus-ota/)

- An issue was discovered on OnePlus One and X devices. Due to a lenient updater-script on the OnePlus One and X OTA images, the fact that both products use the same OTA verification keys, and the fact that both products share the same 'ro.build.product' system property, attackers can install OTAs of one product over the other, even on locked bootloaders. That could theoretically allow for exploitation of vulnerabilities patched on one image but not on the other, in addition to expansion of the attack surface. Moreover, the vulnerability may result in having the device unusable until a Factory Reset is performed. This vulnerability can be exploited by Man-in-the-Middle (MiTM) attackers targeting the update process. This is possible because the update transaction does not occur over TLS (CVE-2016-10370). In addition, physical attackers can reboot the phone into recovery, and then use 'adb sideload' to push the OTA.

### [CVE-2017-8877](https://wwws.nightwatchcybersecurity.com/2017/05/09/multiple-vulnerabilities-in-asus-routers/)

- ASUS RT-AC* and RT-N* devices with firmware through 3.0.0.4.380.7378 allow JSONP Information Disclosure such as the SSID.

### [CVE-2017-8878](https://wwws.nightwatchcybersecurity.com/2017/05/09/multiple-vulnerabilities-in-asus-routers/)

- ASUS RT-AC* and RT-N* devices with firmware before 3.0.0.4.380.7378 allow remote authenticated users to discover the Wi-Fi password via WPS_info.xml.

### [CVE-2017-8890](https://github.com/hardenedlinux/offensive_poc/tree/master/CVE-2017-8890)

- The inet_csk_clone_lock function in net/ipv4/inet_connection_sock.c in the Linux kernel through 4.10.15 allows attackers to cause a denial of service (double free) or possibly have unspecified other impact by leveraging use of the accept system call.

### [CVE-2017-8912](https://osandamalith.com/2017/05/11/cmsms-2-1-6-multiple-vulnerabilities/)

- ** DISPUTED ** CMS Made Simple (CMSMS) 2.1.6 allows remote authenticated administrators to execute arbitrary PHP code via the code parameter to admin/editusertag.php, related to the CreateTagFunction and CallUserTag functions. NOTE: the vendor reportedly has stated this is "a feature, not a bug."

### [CVE-2017-8917](https://blog.sucuri.net/2017/05/sql-injection-vulnerability-joomla-3-7.html)

- SQL injection vulnerability in Joomla! 3.7.x before 3.7.1 allows attackers to execute arbitrary SQL commands via unspecified vectors.

### [CVE-2017-9417](http://boosterok.com/blog/broadpwn2/)

- Broadcom BCM43xx Wi-Fi chips allow remote attackers to execute arbitrary code via unspecified vectors, aka the "Broadpwn" issue.

### [CVE-2017-9791](CVE-2017-9791.md)

- The Struts 1 plugin in Apache Struts 2.3.x might allow remote code execution via a malicious field value passed in a raw message to the ActionMessage.

### [CVE-2017-9798](https://blog.fuzzing-project.org/60-Optionsbleed-HTTP-OPTIONS-method-can-leak-Apaches-server-memory.html)

- Apache httpd allows remote attackers to read secret data from process memory if the Limit directive can be set in a user's .htaccess file, or if httpd.conf has certain misconfigurations, aka Optionsbleed. This affects the Apache HTTP Server through 2.2.34 and 2.4.x through 2.4.27. The attacker sends an unauthenticated OPTIONS HTTP request when attempting to read secret data. This is a use-after-free issue and thus secret data is not always sent, and the specific data depends on many factors including configuration. Exploitation with .htaccess can be blocked with a patch to the ap_limit_section function in server/core.c.

### [CVE-2017-9805](CVE-2017-9805.md)

- The REST Plugin in Apache Struts 2.1.2 through 2.3.x before 2.3.34 and 2.5.x before 2.5.13 uses an XStreamHandler with an instance of XStream for deserialization without any type filtering, which can lead to Remote Code Execution when deserializing XML payloads.

### [CVE-2017-9822](https://cert.360.cn/warning/detail?id=e689288863456481733e01b093c986b6)

- DNN (aka DotNetNuke) before 9.1.1 has Remote Code Execution via a cookie, aka "2017-08 (Critical) Possible remote code execution on DNN sites."

### [CVE-2017-9948](https://www.vulnerability-lab.com/get_content.php?id=2071)

- A stack buffer overflow vulnerability has been discovered in Microsoft Skype 7.2, 7.35, and 7.36 before 7.37, involving MSFTEDIT.DLL mishandling of remote RDP clipboard content within the message box.

### [CVE-2017-9993](CVE-2017-9993.md)

- FFmpeg before 2.8.12, 3.0.x and 3.1.x before 3.1.9, 3.2.x before 3.2.6, and 3.3.x before 3.3.2 does not properly restrict HTTP Live Streaming filename extensions and demuxer names, which allows attackers to read arbitrary files via crafted playlist data.

### [CVE-2017-10271](CVE-2017-10271.md)

- Vulnerability in the Oracle WebLogic Server component of Oracle Fusion Middleware (subcomponent: WLS Security). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.1.0 and 12.2.1.2.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.0 Base Score 7.5 (Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H).

### [CVE-2017-10661](http://bbs.pediy.com/thread-220490.htm)

- Race condition in fs/timerfd.c in the Linux kernel before 4.10.15 allows local users to gain privileges or cause a denial of service (list corruption or use-after-free) via simultaneous file-descriptor operations that leverage improper might_cancel queueing.

### [CVE-2017-11105](https://alephsecurity.com/vulns/aleph-2017026)

- The OnePlus 2 Primary Bootloader (PBL) does not validate the SBL1 partition before executing it, although it contains a certificate. This allows attackers with write access to that partition to disable signature validation.

### [CVE-2017-11120](https://bugs.chromium.org/p/project-zero/issues/detail?id=1289)

- On Broadcom BCM4355C0 Wi-Fi chips 9.44.78.27.0.1.56 and other chips, an attacker can craft a malformed RRM neighbor report frame to trigger an internal buffer overflow in the Wi-Fi firmware, aka B-V2017061204.

### [CVE-2017-11421](http://news.dieweltistgarnichtso.net/posts/gnome-thumbnailer-msi-fail.html)

- gnome-exe-thumbnailer before 0.9.5 is prone to a VBScript Injection when generating thumbnails for MSI files, aka the "Bad Taste" issue. There is a local attack if the victim uses the GNOME Files file manager, and navigates to a directory containing a .msi file with VBScript code in its filename.

### [CVE-2017-11444](http://mp.weixin.qq.com/s/89mCnjUCvmptLsKaeVlC9Q)

- Subrion CMS before 4.1.5.10 has a SQL injection vulnerability in /front/search.php via the $_GET array.

### [CVE-2017-11610](https://github.com/ysrc/xunfeng/blob/master/vulscan/vuldb/crack_supervisor_web.py)

- The XML-RPC server in supervisor before 3.0.1, 3.1.x before 3.1.4, 3.2.x before 3.2.4, and 3.3.x before 3.3.3 allows remote authenticated users to execute arbitrary commands via a crafted XML-RPC request, related to nested supervisord namespace lookups.

### [CVE-2017-11764](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11764.md)

- Microsoft Edge in Microsoft Windows 10 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to the way that the Microsoft Edge scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8649, CVE-2017-8660, CVE-2017-8729, CVE-2017-8738, CVE-2017-8740, CVE-2017-8741, CVE-2017-8748, CVE-2017-8752, CVE-2017-8753, CVE-2017-8755, and CVE-2017-8756.

### [CVE-2017-11774](https://sensepost.com/blog/2017/outlook-home-page-another-ruler-vector/)

- Microsoft Outlook 2010 SP2, Outlook 2013 SP1 and RT SP1, and Outlook 2016 allow an attacker to execute arbitrary commands, due to how Microsoft Office handles objects in memory, aka "Microsoft Outlook Security Feature Bypass Vulnerability."

### [CVE-2017-11779](https://www.bishopfox.com/blog/2017/10/a-bug-has-no-name-multiple-heap-buffer-overflows-in-the-windows-dns-client/)

- The Microsoft Windows Domain Name System (DNS) DNSAPI.dll on Microsoft Windows 8.1, Windows Server 2012 R2, Windows RT 8.1, Windows 10 Gold, 1511, 1607, and 1703, and Windows Server 2016 allows a remote code execution vulnerability when it fails to properly handle DNS responses, aka "Windows DNSAPI Remote Code Execution Vulnerability".

### [CVE-2017-11793](https://github.com/tunz/js-vuln-db/blob/master/jscript/CVE-2017-11793.md)

- Internet Explorer in Microsoft Windows 7 SP1, Windows Server 2008 SP2 and R2 SP1, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11792, CVE-2017-11796, CVE-2017-11798, CVE-2017-11799, CVE-2017-11800, CVE-2017-11801, CVE-2017-11802, CVE-2017-11804, CVE-2017-11805, CVE-2017-11806, CVE-2017-11807, CVE-2017-11808, CVE-2017-11809, CVE-2017-11810, CVE-2017-11811, CVE-2017-11812, and CVE-2017-11821.

### [CVE-2017-11799](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11799.md)

- ChakraCore and Microsoft Edge in Microsoft Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11792, CVE-2017-11793, CVE-2017-11796, CVE-2017-11797, CVE-2017-11798, CVE-2017-11800, CVE-2017-11801, CVE-2017-11802, CVE-2017-11804, CVE-2017-11805, CVE-2017-11806, CVE-2017-11807, CVE-2017-11808, CVE-2017-11809, CVE-2017-11810, CVE-2017-11811, CVE-2017-11812, and CVE-2017-11821.

### [CVE-2017-11802](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11802.md)

- ChakraCore and Microsoft Edge in Microsoft Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11792, CVE-2017-11793, CVE-2017-11796, CVE-2017-11797, CVE-2017-11798, CVE-2017-11799, CVE-2017-11800, CVE-2017-11801, CVE-2017-11804, CVE-2017-11805, CVE-2017-11806, CVE-2017-11807, CVE-2017-11808, CVE-2017-11809, CVE-2017-11810, CVE-2017-11811, CVE-2017-11812, and CVE-2017-11821.

### [CVE-2017-11809](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11809.md)

- ChakraCore and Microsoft Edge in Microsoft Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11792, CVE-2017-11793, CVE-2017-11796, CVE-2017-11797, CVE-2017-11798, CVE-2017-11799, CVE-2017-11800, CVE-2017-11801, CVE-2017-11802, CVE-2017-11804, CVE-2017-11805, CVE-2017-11806, CVE-2017-11807, CVE-2017-11808, CVE-2017-11810, CVE-2017-11811, CVE-2017-11812, and CVE-2017-11821.

### [CVE-2017-11811](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11811.md)

- ChakraCore and Microsoft Edge in Microsoft Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11792, CVE-2017-11793, CVE-2017-11796, CVE-2017-11797, CVE-2017-11798, CVE-2017-11799, CVE-2017-11800, CVE-2017-11801, CVE-2017-11802, CVE-2017-11804, CVE-2017-11805, CVE-2017-11806, CVE-2017-11807, CVE-2017-11808, CVE-2017-11809, CVE-2017-11810, CVE-2017-11812, and CVE-2017-11821.

### [CVE-2017-11812](https://www.zerodayinitiative.com/blog/2017/12/22/a-matching-pair-of-use-after-free-bugs-in-chakra-asmjs)

- ChakraCore and Microsoft Edge in Microsoft Windows 10 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11792, CVE-2017-11793, CVE-2017-11796, CVE-2017-11797, CVE-2017-11798, CVE-2017-11799, CVE-2017-11800, CVE-2017-11801, CVE-2017-11802, CVE-2017-11804, CVE-2017-11805, CVE-2017-11806, CVE-2017-11807, CVE-2017-11808, CVE-2017-11809, CVE-2017-11810, CVE-2017-11812, and CVE-2017-11821.

### [CVE-2017-11839](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11839.md)

- Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, Windows Server 2016 and Windows Server, version 1709 allows an attacker to take control of an affected system, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11836, CVE-2017-11837, CVE-2017-11838, CVE-2017-11840, CVE-2017-11841, CVE-2017-11843, CVE-2017-11846, CVE-2017-11858, CVE-2017-11859, CVE-2017-11861, CVE-2017-11862, CVE-2017-11866, CVE-2017-11869, CVE-2017-11870, CVE-2017-11871, and CVE-2017-11873.

### [CVE-2017-11840](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11840.md)

- ChakraCore and Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, Windows Server 2016 and Windows Server, version 1709 allows an attacker to gain the same user rights as the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11836, CVE-2017-11837, CVE-2017-11838, CVE-2017-11839, CVE-2017-11841, CVE-2017-11843, CVE-2017-11846, CVE-2017-11858, CVE-2017-11859, CVE-2017-11861, CVE-2017-11862, CVE-2017-11866, CVE-2017-11869, CVE-2017-11870, CVE-2017-11871, and CVE-2017-11873.

### [CVE-2017-11841](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11841.md)

- ChakraCore and Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, Windows Server 2016 and Windows Server, version 1709 allows an attacker to gain the same user rights as the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11836, CVE-2017-11837, CVE-2017-11838, CVE-2017-11839, CVE-2017-11840, CVE-2017-11843, CVE-2017-11846, CVE-2017-11858, CVE-2017-11859, CVE-2017-11861, CVE-2017-11862, CVE-2017-11866, CVE-2017-11869, CVE-2017-11870, CVE-2017-11871, and CVE-2017-11873.

### [CVE-2017-11855](https://github.com/tunz/js-vuln-db/blob/master/jscript/CVE-2017-11855.md)

- Internet Explorer in Microsoft Windows 7 SP1, Windows Server 2008 SP2 and R2 SP1, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703, 1709, Windows Server 2016 and Windows Server, version 1709 allows an attacker to gain the same user rights as the current user, due to how Internet Explorer handles objects in memory, aka "Internet Explorer Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11856.

### [CVE-2017-11861](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11861.md)

- Microsoft Edge in Windows 10 1607, 1703, 1709, Windows Server 2016 and Windows Server, version 1709 allows an attacker to gain the same user rights as the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11836, CVE-2017-11837, CVE-2017-11838, CVE-2017-11839, CVE-2017-11840, CVE-2017-11841, CVE-2017-11843, CVE-2017-11846, CVE-2017-11858, CVE-2017-11859, CVE-2017-11862, CVE-2017-11866, CVE-2017-11869, CVE-2017-11870, CVE-2017-11871, and CVE-2017-11873.

### [CVE-2017-11870](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11870.md)

- ChakraCore and Microsoft Edge in Windows 10 1703, 1709, and Windows Server, version 1709 allows an attacker to gain the same user rights as the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11836, CVE-2017-11837, CVE-2017-11838, CVE-2017-11839, CVE-2017-11840, CVE-2017-11841, CVE-2017-11843, CVE-2017-11846, CVE-2017-11858, CVE-2017-11859, CVE-2017-11861, CVE-2017-11862, CVE-2017-11866, CVE-2017-11869, CVE-2017-11871, and CVE-2017-11873.

### [CVE-2017-11873](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11873.md)

- ChakraCore and Microsoft Edge in Windows 10 1511, 1607, 1703, 1709, Windows Server 2016 and Windows Server, version 1709 allows an attacker to gain the same user rights as the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11836, CVE-2017-11837, CVE-2017-11838, CVE-2017-11839, CVE-2017-11840, CVE-2017-11841, CVE-2017-11843, CVE-2017-11846, CVE-2017-11858, CVE-2017-11859, CVE-2017-11861, CVE-2017-11862, CVE-2017-11866, CVE-2017-11869, CVE-2017-11870, and CVE-2017-11871.

### [CVE-2017-11882](https://github.com/Ridter/CVE-2017-11882)

- Microsoft Office 2007 Service Pack 3, Microsoft Office 2010 Service Pack 2, Microsoft Office 2013 Service Pack 1, and Microsoft Office 2016 allow an attacker to run arbitrary code in the context of the current user by failing to properly handle objects in memory, aka "Microsoft Office Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11884.

### [CVE-2017-11890](https://github.com/tunz/js-vuln-db/blob/master/jscript/CVE-2017-11890.md)

- Microsoft Windows 7 SP1, Windows Server 2008 and R2 SP1, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allow an attacker to execute arbitrary code in the context of the current user, due to how Internet Explorer handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11886, CVE-2017-11889, CVE-2017-11893, CVE-2017-11894, CVE-2017-11895, CVE-2017-11901, CVE-2017-11903, CVE-2017-11905, CVE-2017-11907, CVE-2017-11908, CVE-2017-11909, CVE-2017-11910, CVE-2017-11911, CVE-2017-11912, CVE-2017-11913, CVE-2017-11914, CVE-2017-11916, CVE-2017-11918, and CVE-2017-11930.

### [CVE-2017-11893](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11893.md)

- ChakraCore and Microsoft Edge in Windows 10 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11886, CVE-2017-11889, CVE-2017-11890, CVE-2017-11894, CVE-2017-11895, CVE-2017-11901, CVE-2017-11903, CVE-2017-11905, CVE-2017-11907, CVE-2017-11908, CVE-2017-11909, CVE-2017-11910, CVE-2017-11911, CVE-2017-11912, CVE-2017-11913, CVE-2017-11914, CVE-2017-11916, CVE-2017-11918, and CVE-2017-11930.

### [CVE-2017-11903](https://github.com/tunz/js-vuln-db/blob/master/jscript/CVE-2017-11903.md)

- Internet Explorer in Microsoft Windows 7 SP1, Windows Server 2008 and R2 SP1, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to gain the same user rights as the current user, due to how Internet Explorer handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11886, CVE-2017-11889, CVE-2017-11890, CVE-2017-11893, CVE-2017-11894, CVE-2017-11895, CVE-2017-11901, CVE-2017-11905, CVE-2017-11907, CVE-2017-11908, CVE-2017-11909, CVE-2017-11910, CVE-2017-11911, CVE-2017-11912, CVE-2017-11913, CVE-2017-11914, CVE-2017-11916, CVE-2017-11918, and CVE-2017-11930.

### [CVE-2017-11906](https://github.com/tunz/js-vuln-db/blob/master/jscript/CVE-2017-11906.md)

- Internet Explorer in Microsoft Windows 7 SP1, Windows Server 2008 and R2 SP1, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, and Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to obtain information to further compromise the user's system, due to how Internet Explorer handles objects in memory, aka "Scripting Engine Information Disclosure Vulnerability". This CVE ID is unique from CVE-2017-11887 and CVE-2017-11919.

### [CVE-2017-11907](https://github.com/tunz/js-vuln-db/blob/master/jscript/CVE-2017-11907.md)

- Internet Explorer in Microsoft Windows 7 SP1, Windows Server 2008 and R2 SP1, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to gain the same user rights as the current user, due to how Internet Explorer handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11886, CVE-2017-11889, CVE-2017-11890, CVE-2017-11893, CVE-2017-11894, CVE-2017-11895, CVE-2017-11901, CVE-2017-11903, CVE-2017-11905, CVE-2017-11905, CVE-2017-11908, CVE-2017-11909, CVE-2017-11910, CVE-2017-11911, CVE-2017-11912, CVE-2017-11913, CVE-2017-11914, CVE-2017-11916, CVE-2017-11918, and CVE-2017-11930.

### [CVE-2017-11909](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11909.md)

- ChakraCore and Windows 10 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11886, CVE-2017-11889, CVE-2017-11890, CVE-2017-11893, CVE-2017-11894, CVE-2017-11895, CVE-2017-11901, CVE-2017-11903, CVE-2017-11905, CVE-2017-11905, CVE-2017-11907, CVE-2017-11908, CVE-2017-11910, CVE-2017-11911, CVE-2017-11912, CVE-2017-11913, CVE-2017-11914, CVE-2017-11916, CVE-2017-11918, and CVE-2017-11930.

### [CVE-2017-11911](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11911.md)

- ChakraCore and Windows 10 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11886, CVE-2017-11889, CVE-2017-11890, CVE-2017-11893, CVE-2017-11894, CVE-2017-11895, CVE-2017-11901, CVE-2017-11903, CVE-2017-11905, CVE-2017-11905, CVE-2017-11907, CVE-2017-11908, CVE-2017-11909, CVE-2017-11910, CVE-2017-11912, CVE-2017-11913, CVE-2017-11914, CVE-2017-11916, CVE-2017-11918, and CVE-2017-11930.

### [CVE-2017-11914](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11914.md)

- ChakraCore and Microsoft Edge in Windows 10 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to gain the same user rights as the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11886, CVE-2017-11889, CVE-2017-11890, CVE-2017-11893, CVE-2017-11894, CVE-2017-11895, CVE-2017-11901, CVE-2017-11903, CVE-2017-11905, CVE-2017-11905, CVE-2017-11907, CVE-2017-11908, CVE-2017-11909, CVE-2017-11910, CVE-2017-11911, CVE-2017-11912, CVE-2017-11913, CVE-2017-11916, CVE-2017-11918, and CVE-2017-11930.

### [CVE-2017-11918](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11918.md)

- ChakraCore and Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to gain the same user rights as the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11886, CVE-2017-11889, CVE-2017-11890, CVE-2017-11893, CVE-2017-11894, CVE-2017-11895, CVE-2017-11901, CVE-2017-11903, CVE-2017-11905, CVE-2017-11905, CVE-2017-11907, CVE-2017-11908, CVE-2017-11909, CVE-2017-11910, CVE-2017-11911, CVE-2017-11912, CVE-2017-11913, CVE-2017-11914, CVE-2017-11916, and CVE-2017-11930.

### [CVE-2017-12097](https://www.talosintelligence.com/reports/TALOS-2017-0449)

- An exploitable cross site scripting (XSS) vulnerability exists in the filter functionality of the delayed_job_web rails gem version 1.4. A specially crafted URL can cause an XSS flaw resulting in an attacker being able to execute arbitrary javascript on the victim's browser. An attacker can phish an authenticated user to trigger this vulnerability.

### [CVE-2017-12098](https://www.talosintelligence.com/reports/TALOS-2017-0450)

- An exploitable cross site scripting (XSS) vulnerability exists in the add filter functionality of the rails_admin rails gem version 1.2.0. A specially crafted URL can cause an XSS flaw resulting in an attacker being able to execute arbitrary javascript on the victim's browser. An attacker can phish an authenticated user to trigger this vulnerability.

### [CVE-2017-12149](https://github.com/joaomatosf/JavaDeserH2HC)

- In Jboss Application Server as shipped with Red Hat Enterprise Application Platform 5.2, it was found that the doFilter method in the ReadOnlyAccessFilter of the HTTP Invoker does not restrict classes for which it performs deserialization and thus allowing an attacker to execute arbitrary code via crafted serialized data.

### [CVE-2017-12542](https://github.com/airbus-seclab/ilo4_toolbox)

- A authentication bypass and execution of code vulnerability in HPE Integrated Lights-out 4 (iLO 4) version prior to 2.53 was found.

### [CVE-2017-12581](https://blog.doyensec.com/2017/08/03/electron-framework-security.html)

- GitHub Electron before 1.6.8 allows remote command execution because of a nodeIntegration bypass vulnerability. This also affects all applications that bundle Electron code equivalent to 1.6.8 or earlier. Bypassing the Same Origin Policy (SOP) is a precondition; however, recent Electron versions do not have strict SOP enforcement. Combining an SOP bypass with a privileged URL internally used by Electron, it was possible to execute native Node.js primitives in order to run OS commands on the user's host. Specifically, a chrome-devtools://devtools/bundled/inspector.html window could be used to eval a Node.js child_process.execFile API call.

### [CVE-2017-12611](CVE-2017-12611.md)

- In Apache Struts 2.0.1 through 2.3.33 and 2.5 through 2.5.10, using an unintentional expression in a Freemarker tag instead of string literals can lead to a RCE attack.

### [CVE-2017-12615](https://www.secfree.com/article-399.html)

- When running Apache Tomcat 7.0.0 to 7.0.79 on Windows with HTTP PUTs enabled (e.g. via setting the readonly initialisation parameter of the Default to false) it was possible to upload a JSP file to the server via a specially crafted request. This JSP could then be requested and any code it contained would be executed by the server.

### [CVE-2017-12617](http://www.freebuf.com/vuls/150203.html)

- When running Apache Tomcat versions 9.0.0.M1 to 9.0.0, 8.5.0 to 8.5.22, 8.0.0.RC1 to 8.0.46 and 7.0.0 to 7.0.81 with HTTP PUTs enabled (e.g. via setting the readonly initialisation parameter of the Default servlet to false) it was possible to upload a JSP file to the server via a specially crafted request. This JSP could then be requested and any code it contained would be executed by the server.

### [CVE-2017-13089](https://paper.seebug.org/525/)

- The http.c:skip_short_body() function is called in some circumstances, such as when processing redirects. When the response is sent chunked in wget before 1.19.2, the chunk parser uses strtol() to read each chunk's length, but doesn't check that the chunk length is a non-negative number. The code then tries to skip the chunk in pieces of 512 bytes by using the MIN() macro, but ends up passing the negative chunk length to connect.c:fd_read(). As fd_read() takes an int argument, the high 32 bits of the chunk length are discarded, leaving fd_read() with a completely attacker controlled length argument.

### [CVE-2017-13156](https://github.com/V-E-O/PoC/tree/master/CVE-2017-13156)

- An elevation of privilege vulnerability in the Android system (art). Product: Android. Versions: 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2, 8.0. Android ID A-64211847.

### [CVE-2017-13253](https://blog.zimperium.com/cve-2017-13253-buffer-overflow-multiple-android-drm-services/)

- In CryptoPlugin::decrypt of CryptoPlugin.cpp, there is a possible out of bounds write due to a missing bounds check. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is needed for exploitation. Product: Android. Versions: 8.0, 8.1. Android ID: A-71389378.

### [CVE-2017-13258](https://blog.quarkslab.com/android-bluetooth-vulnerabilities-in-the-march-2018-security-bulletin.html)

- In bnep_data_ind of bnep_main.cc, there is a possible out of bounds read due to a missing bounds check. This could lead to remote information disclosure with no additional execution privileges needed. User interaction is not needed for exploitation. Product: Android. Versions: 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2, 8.0, 8.1. Android ID: A-67863755.

### [CVE-2017-13260](https://blog.quarkslab.com/android-bluetooth-vulnerabilities-in-the-march-2018-security-bulletin.html)

- In bnep_data_ind of bnep_main.cc, there is a possible out of bounds read due to a missing bounds check. This could lead to remote information disclosure with no additional execution privileges needed. User interaction is not needed for exploitation. Product: Android. Versions: 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2, 8.0, 8.1. Android ID: A-69177251.

### [CVE-2017-13261](https://blog.quarkslab.com/android-bluetooth-vulnerabilities-in-the-march-2018-security-bulletin.html)

- In bnep_process_control_packet of bnep_utils.cc, there is a possible out of bounds read due to a missing bounds check. This could lead to remote information disclosure with no additional execution privileges needed. User interaction is not needed for exploitation. Product: Android. Versions: 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2, 8.0, 8.1. Android ID: A-69177292.

### [CVE-2017-13262](https://blog.quarkslab.com/android-bluetooth-vulnerabilities-in-the-march-2018-security-bulletin.html)

- In bnep_data_ind of bnep_main.cc, there is a possible out of bounds read due to a missing length decrement operation. This could lead to remote information disclosure with no additional execution privileges needed. User interaction is not needed for exploitation. Product: Android. Versions: 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2, 8.0, 8.1. Android ID: A-69271284.

### [CVE-2017-13791](http://www.uaf.li/2018/02/three-uaf-when-iterating-through.html)

- An issue was discovered in certain Apple products. iOS before 11.1 is affected. Safari before 11.0.1 is affected. iCloud before 7.1 on Windows is affected. iTunes before 12.7.1 on Windows is affected. tvOS before 11.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-13792](http://www.uaf.li/2018/02/cve-2017-13792-uaf-in.html)

- An issue was discovered in certain Apple products. iOS before 11.1 is affected. Safari before 11.0.1 is affected. iCloud before 7.1 on Windows is affected. iTunes before 12.7.1 on Windows is affected. tvOS before 11.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-14135](https://the-infosec.com/2017/07/05/from-shodan-to-rce-opendreambox-2-0-0-code-execution/)

- enigma2-plugins/blob/master/webadmin/src/WebChilds/Script.py in the webadmin plugin for opendreambox 2.0.0 allows remote attackers to execute arbitrary OS commands via shell metacharacters in the command parameter to the /script URI.	

### [CVE-2017-14335](https://blogs.securiteam.com/index.php/archives/3420)

- On Beijing Hanbang Hanbanggaoke devices, because user-controlled input is not sufficiently sanitized, sending a PUT request to /ISAPI/Security/users/1 allows an admin password change.

### [CVE-2017-14491](https://github.com/google/security-research-pocs/blob/master/vulnerabilities/dnsmasq/CVE-2017-14491.py)

- Heap-based buffer overflow in dnsmasq before 2.78 allows remote attackers to cause a denial of service (crash) or execute arbitrary code via a crafted DNS response.

### [CVE-2017-14492](https://github.com/google/security-research-pocs/blob/master/vulnerabilities/dnsmasq/CVE-2017-14492.py)

- Heap-based buffer overflow in dnsmasq before 2.78 allows remote attackers to cause a denial of service (crash) or execute arbitrary code via a crafted IPv6 router advertisement request.

### [CVE-2017-14493](https://github.com/google/security-research-pocs/blob/master/vulnerabilities/dnsmasq/CVE-2017-14493.py)

- Stack-based buffer overflow in dnsmasq before 2.78 allows remote attackers to cause a denial of service (crash) or execute arbitrary code via a crafted DHCPv6 request.

### [CVE-2017-14494](https://github.com/google/security-research-pocs/blob/master/vulnerabilities/dnsmasq/CVE-2017-14494.py)

- dnsmasq before 2.78, when configured as a relay, allows remote attackers to obtain sensitive memory information via vectors involving handling DHCPv6 forwarded requests.

### [CVE-2017-14495](https://github.com/google/security-research-pocs/blob/master/vulnerabilities/dnsmasq/CVE-2017-14495.py)

- Memory leak in dnsmasq before 2.78, when the --add-mac, --add-cpe-id or --add-subnet option is specified, allows remote attackers to cause a denial of service (memory consumption) via vectors involving DNS response creation.

### [CVE-2017-14496](https://github.com/google/security-research-pocs/blob/master/vulnerabilities/dnsmasq/CVE-2017-14496.py)

- Integer underflow in the add_pseudoheader function in dnsmasq before 2.78 , when the --add-mac, --add-cpe-id or --add-subnet option is specified, allows remote attackers to cause a denial of service via a crafted DNS request.

### [CVE-2017-14904](https://android-developers.googleblog.com/2018/01/android-security-ecosystem-investments.html)

- In Android for MSM, Firefox OS for MSM, QRD Android, with all Android releases from CAF using the Linux kernel, a crafted binder request can cause an arbitrary unmap in MediaServer.

### [CVE-2017-15277](https://github.com/neex/gifoeb)

- ReadGIFImage in coders/gif.c in ImageMagick 7.0.6-1 and GraphicsMagick 1.3.26 leaves the palette uninitialized when processing a GIF file that has neither a global nor local palette. If the affected product is used as a library loaded into a process that operates on interesting data, this data sometimes can be leaked via the uninitialized palette.

### [CVE-2017-15303](https://github.com/hfiref0x/Stryker)

- In CPUID CPU-Z before 1.43, there is an arbitrary memory write that results directly in elevation of privileges, because any program running on the local machine (while CPU-Z is running) can issue an ioctl 0x9C402430 call to the kernel-mode driver (e.g., cpuz141_x64.sys for version 1.41).

### [CVE-2017-15361](https://crocs.fi.muni.cz/public/papers/rsa_ccs17)

- The Infineon RSA library 1.02.013 in Infineon Trusted Platform Module (TPM) firmware, such as versions before 0000000000000422 - 4.34, before 000000000000062b - 6.43, and before 0000000000008521 - 133.33, mishandles RSA key generation, which makes it easier for attackers to defeat various cryptographic protection mechanisms via targeted attacks, aka ROCA. Examples of affected technologies include BitLocker with TPM 1.2, YubiKey 4 (before 4.3.5) PGP key generation, and the Cached User Data encryption feature in Chrome OS.

### [CVE-2017-15388](https://bugs.chromium.org/p/chromium/issues/detail?id=756563)

- Iteration through non-finite points in Skia in Google Chrome prior to 62.0.3202.62 allowed a remote attacker to perform an out of bounds memory read via a crafted HTML page.

### [CVE-2017-15396](https://bugs.chromium.org/p/chromium/issues/detail?id=770452)

- A stack buffer overflow in NumberingSystem in International Components for Unicode (ICU) for C/C++ before 60.2, as used in V8 in Google Chrome prior to 62.0.3202.75 and other products, allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page.

### [CVE-2017-15398](https://bugs.chromium.org/p/chromium/issues/detail?id=777728)

- A stack buffer overflow in the QUIC networking stack in Google Chrome prior to 62.0.3202.89 allowed a remote attacker to gain code execution via a malicious server.

### [CVE-2017-15399](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-15399.md)

- A use after free in V8 in Google Chrome prior to 62.0.3202.89 allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page.

### [CVE-2017-15401](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-15401.md)

- A memory corruption bug in WebAssembly could lead to out of bounds read and write through V8 in WebAssembly in Google Chrome prior to 62.0.3202.62 allowed a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page.

### [CVE-2017-15411](https://bugs.chromium.org/p/chromium/issues/detail?id=770148)

- Use after free in PDFium in Google Chrome prior to 63.0.3239.84 allowed a remote attacker to potentially exploit heap corruption via a crafted PDF file.

### [CVE-2017-15412](https://bugs.chromium.org/p/chromium/issues/detail?id=727039)

- Use after free in libxml2 before 2.9.5, as used in Google Chrome prior to 63.0.3239.84 and other products, allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page.

### [CVE-2017-15415](https://bugs.chromium.org/p/chromium/issues/detail?id=765512)

- Incorrect serialization in IPC in Google Chrome prior to 63.0.3239.84 allowed a remote attacker to leak the value of a pointer via a crafted HTML page.

### [CVE-2017-15428](https://github.com/xuechiyaobai/V8_November_2017/tree/master/CVE-2017-15428)

- Insufficient data validation in V8 builtins string generator could lead to out of bounds read and write access in V8 in Google Chrome prior to 62.0.3202.94 and allowed a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page.

### [CVE-2017-15613](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-interface variable in the cmxddns.lua file.

### [CVE-2017-15614](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-outif variable in the pptp_client.lua file.

### [CVE-2017-15615](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the lcpechointerval variable in the pptp_client.lua file.

### [CVE-2017-15616](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-interface variable in the phddns.lua file.

### [CVE-2017-15617](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the iface variable in the interface_wan.lua file.

### [CVE-2017-15618](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-enable variable in the pptp_client.lua file.

### [CVE-2017-15619](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the pptphellointerval variable in the pptp_client.lua file.

### [CVE-2017-15620](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-zone variable in the ipmac_import.lua file.

### [CVE-2017-15621](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the olmode variable in the interface_wan.lua file.

### [CVE-2017-15622](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-mppeencryption variable in the pptp_client.lua file.

### [CVE-2017-15623](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-enable variable in the pptp_server.lua file.

### [CVE-2017-15624](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-authtype variable in the pptp_server.lua file.

### [CVE-2017-15625](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-olmode variable in the pptp_client.lua file.

### [CVE-2017-15626](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-bindif variable in the pptp_server.lua file.

### [CVE-2017-15627](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-pns variable in the pptp_client.lua file.

### [CVE-2017-15628](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the lcpechointerval variable in the pptp_server.lua file.

### [CVE-2017-15629](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-tunnelname variable in the pptp_client.lua file.

### [CVE-2017-15630](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-remotesubnet variable in the pptp_client.lua file.

### [CVE-2017-15631](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-workmode variable in the pptp_client.lua file.

### [CVE-2017-15632](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-mppeencryption variable in the pptp_server.lua file.

### [CVE-2017-15633](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-ipgroup variable in the session_limits.lua file.

### [CVE-2017-15634](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the name variable in the wportal.lua file.

### [CVE-2017-15635](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the max_conn variable in the session_limits.lua file.

### [CVE-2017-15636](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-time variable in the webfilter.lua file.

### [CVE-2017-15637](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the pptphellointerval variable in the pptp_server.lua file.

### [CVE-2017-15944](https://d0n9.github.io/2018/01/26/CVE-2017-15944%20Palo%20Alto防火墙远程代码执行构造%20EXP/)

- Palo Alto Networks PAN-OS before 6.1.19, 7.0.x before 7.0.19, 7.1.x before 7.1.14, and 8.0.x before 8.0.6 allows remote attackers to execute arbitrary code via vectors involving the management interface.

### [CVE-2017-16544](https://www.twistlock.com/2017/11/20/cve-2017-16544-busybox-autocompletion-vulnerability/)

- In the add_match function in libbb/lineedit.c in BusyBox through 1.27.2, the tab autocomplete feature of the shell, used to get a list of filenames in a directory, does not sanitize filenames and results in executing any escape sequence in the terminal. This could potentially result in code execution, arbitrary file writes, or other attacks.

### [CVE-2017-16584](https://twitter.com/steventseeley/status/930555302013005827)

- This vulnerability allows remote attackers to disclose sensitive information on vulnerable installations of Foxit Reader 8.3.2.25013. User interaction is required to exploit this vulnerability in that the target must visit a malicious page or open a malicious file. The specific flaw exists within util.printf. The issue results from the lack of proper validation of user-supplied data, which can result in a read past the end of an allocated object. An attacker can leverage this in conjunction with other vulnerabilities to execute code in the context of the current process. Was ZDI-CAN-5290.

### [CVE-2017-16716](https://www.exploit-db.com/exploits/43928/)

- A SQL Injection issue was discovered in WebAccess versions prior to 8.3. WebAccess does not properly sanitize its inputs for SQL commands.

### [CVE-2017-16943](https://devco.re/blog/2017/12/11/Exim-RCE-advisory-CVE-2017-16943-en/)

- The receive_msg function in receive.c in the SMTP daemon in Exim 4.88 and 4.89 allows remote attackers to execute arbitrary code or cause a denial of service (use-after-free) via vectors involving BDAT commands.

### [CVE-2017-16944](https://devco.re/blog/2017/12/11/Exim-RCE-advisory-CVE-2017-16943-en/)

- The receive_msg function in receive.c in the SMTP daemon in Exim 4.88 and 4.89 allows remote attackers to cause a denial of service (infinite loop and stack exhaustion) via vectors involving BDAT commands and an improper check for a '.' character signifying the end of the content, related to the bdat_getc function.

### [CVE-2017-16995](CVE-2017-16995.md)

- The check_alu_op function in kernel/bpf/verifier.c in the Linux kernel through 4.14.8 allows local users to cause a denial of service (memory corruption) or possibly have unspecified other impact by leveraging incorrect sign extension.

### [CVE-2017-17033](https://pastebin.com/XAKn6q5Y)

- A buffer overflow vulnerability in password function in QNAP QTS version 4.2.6 build 20171026, 4.3.3.0378 build 20171117, 4.3.4.0387 (Beta 2) build 20171116 and earlier could allow remote attackers to execute arbitrary code on NAS devices.

### [CVE-2017-17107](https://twitter.com/ankit_anubhav/status/950485367215525888)

- Zivif PR115-204-P-RS V2.3.4.2103 web cameras contain a hard-coded cat1029 password for the root user. The SONIX operating system's setup renders this password unchangeable and it can be used to access the device via a TELNET session.

### [CVE-2017-17215](http://xlab.tencent.com/cn/2018/01/05/a-new-way-to-exploit-cve-2017-17215/)

- Huawei HG532 with some customized versions has a remote code execution vulnerability. An authenticated attacker could send malicious packets to port 37215 to launch attacks. Successful exploit could lead to the remote execution of arbitrary code.

### [CVE-2017-17405](https://blog.heroku.com/identifying-ruby-ftp-cve)

- Ruby before 2.4.3 allows Net::FTP command injection. Net::FTP#get, getbinaryfile, gettextfile, put, putbinaryfile, and puttextfile use Kernel#open to open a local file. If the localfile argument starts with the "|" pipe character, the command following the pipe character is executed. The default value of localfile is File.basename(remotefile), so malicious FTP servers could cause arbitrary command execution.

### [CVE-2017-17408](https://github.com/thezdi/PoC/tree/master/CVE-2017-17408/exploit)

- This vulnerability allows remote attackers to execute arbitrary code on vulnerable installations of Bitdefender Internet Security 2018. User interaction is required to exploit this vulnerability in that the target must visit a malicious page or open a malicious file. The specific flaw exists within cevakrnl.xmd. The issue results from the lack of proper validation of user-supplied data, which can result in an integer overflow before allocating a buffer. An attacker can leverage this vulnerability to execute code under the context of SYSTEM. Was ZDI-CAN-5101.

### [CVE-2017-17562](https://www.elttam.com.au/blog/goahead/)

- Embedthis GoAhead before 3.6.5 allows remote code execution if CGI is enabled and a CGI program is dynamically linked. This is a result of initializing the environment of forked CGI scripts using untrusted HTTP request parameters in the cgiHandler function in cgi.c. When combined with the glibc dynamic linker, this behaviour can be abused for remote code execution using special parameter names such as LD_PRELOAD. An attacker can POST their shared object payload in the body of the request, and reference it using /proc/self/fd/0.

### [CVE-2017-17692](https://datarift.blogspot.tw/p/samsung-interent-browser-sop-bypass-cve.html)

- Samsung Internet Browser 5.4.02.3 allows remote attackers to bypass the Same Origin Policy and obtain sensitive information via crafted JavaScript code that redirects to a child tab and rewrites the innerHTML property.

### [CVE-2017-17867](https://neonsea.uk/blog/2017/12/23/rce-inteno-iopsys.html)

- Inteno iopsys 2.0-3.14 and 4.0 devices allow remote authenticated users to execute arbitrary OS commands by modifying the leasetrigger field in the odhcpd configuration to specify an arbitrary program, as demonstrated by a program located on an SMB share. This issue existed because the /etc/uci-defaults directory was not being used to secure the OpenWrt configuration.

### [CVE-2017-17969](https://landave.io/2018/01/7-zip-multiple-memory-corruptions-via-rar-and-zip/)

- Heap-based buffer overflow in the NCompress::NShrink::CDecoder::CodeReal method in 7-Zip before 18.00 and p7zip allows remote attackers to cause a denial of service (out-of-bounds write) or potentially execute arbitrary code via a crafted ZIP archive.

### [CVE-2017-18344](http://www.alunos.dcc.fc.up.pt/~up201407890/CVE-2017-18344.txt)

- The timer_create syscall implementation in kernel/time/posix-timers.c in the Linux kernel before 4.14.8 doesn't properly validate the sigevent->sigev_notify field, which leads to out-of-bounds access in the show_timer function (called when /proc/$PID/timers is read). This allows userspace applications to read arbitrary kernel memory (on a kernel built with CONFIG_POSIX_TIMERS and CONFIG_CHECKPOINT_RESTORE).

### [CVE-2017-1000112](https://github.com/xairy/kernel-exploits/tree/master/CVE-2017-1000112)

- Exploitable memory corruption due to UFO to non-UFO path switch.

### [CVE-2017-1000117](http://bobao.360.cn/learning/detail/4244.html)

- A malicious third-party can give a crafted "ssh://..." URL to an unsuspecting victim, and an attempt to visit the URL can result in any program that exists on the victim's machine being executed. Such a URL could be placed in the .gitmodules file of a malicious project, and an unsuspecting victim could be tricked into running "git clone --recurse-submodules" to trigger the vulnerability.

### [CVE-2017-1000251](https://gitlab.com/marcinguy/blueborne-CVE-2017-1000251)

- The native Bluetooth stack in the Linux Kernel (BlueZ), starting at the Linux kernel version 3.3-rc1 and up to and including 4.13.1, are vulnerable to a stack overflow vulnerability in the processing of L2CAP configuration responses resulting in Remote code execution in kernel space.

### [CVE-2017-1000353](CVE-2017-1000353.md)

- Jenkins Java Deserialization CVE-2017-1000353 Remote Code Execution Vulnerability.

### [CVE-2017-1000364](Stack-Clash.md)

- An issue was discovered in the size of the stack guard page on Linux, specifically a 4k stack guard page is not sufficiently large and can be "jumped" over (the stack guard page is bypassed), this affects Linux Kernel versions 4.11.5 and earlier (the stackguard page was introduced in 2010).

### [CVE-2017-1000365](Stack-Clash.md)

- The Linux Kernel imposes a size restriction on the arguments and environmental strings passed through RLIMIT_STACK/RLIM_INFINITY (1/4 of the size), but does not take the argument and environment pointers into account, which allows attackers to bypass this limitation. This affects Linux Kernel versions 4.11.5 and earlier. It appears that this feature was introduced in the Linux Kernel version 2.6.23.

### [CVE-2017-1000366](Stack-Clash.md)

- glibc contains a vulnerability that allows specially crafted LD_LIBRARY_PATH values to manipulate the heap/stack, causing them to alias, potentially resulting in arbitrary code execution. Please note that additional hardening changes have been made to glibc to prevent manipulation of stack and heap memory but these issues are not directly exploitable, as such they have not been given a CVE. This affects glibc 2.25 and earlier.

### [CVE-2017-1000367](Stack-Clash.md)

- A vulnerability in Sudo's get_process_ttyname() for Linux: this function opens "/proc/[pid]/stat" (man proc) and reads the device number of the tty from field 7 (tty_nr). Unfortunately, these fields are space-separated and field 2 (comm, the filename of the command) can contain spaces (CVE-2017-1000367).

### [CVE-2017-1000369](Stack-Clash.md)

- Exim supports the use of multiple "-p" command line arguments which are malloc()'ed and never free()'ed, used in conjunction with other issues allows attackers to cause arbitrary code execution. This affects exim version 4.89 and earlier. Please note that at this time upstream has released a patch (commit 65e061b76867a9ea7aeeb535341b790b90ae6c21), but it is not known if a new point release is available that addresses this issue at this time.

### [CVE-2017-1000370](Stack-Clash.md)

- The offset2lib patch as used in the Linux Kernel contains a vulnerability that allows a PIE binary to be execve()'ed with 1GB of arguments or environmental strings then the stack occupies the address 0x80000000 and the PIE binary is mapped above 0x40000000 nullifying the protection of the offset2lib patch. This affects Linux Kernel version 4.11.5 and earlier. This is a different issue than CVE-2017-1000371. This issue appears to be limited to i386 based systems.

### [CVE-2017-1000371](Stack-Clash.md)

- The offset2lib patch as used by the Linux Kernel contains a vulnerability, if RLIMIT_STACK is set to RLIM_INFINITY and 1 Gigabyte of memory is allocated (the maximum under the 1/4 restriction) then the stack will be grown down to 0x80000000, and as the PIE binary is mapped above 0x80000000 the minimum distance between the end of the PIE binary's read-write segment and the start of the stack becomes small enough that the stack guard page can be jumped over by an attacker. This affects Linux Kernel version 4.11.5. This is a different issue than CVE-2017-1000370 and CVE-2017-1000365. This issue appears to be limited to i386 based systems.

### [CVE-2017-1000372](Stack-Clash.md)

- A flaw exists in OpenBSD's implementation of the stack guard page that allows attackers to bypass it resulting in arbitrary code execution using setuid binaries such as /usr/bin/at. This affects OpenBSD 6.1 and possibly earlier versions.

### [CVE-2017-1000373](Stack-Clash.md)

- The OpenBSD qsort() function is recursive, and not randomized, an attacker can construct a pathological input array of N elements that causes qsort() to deterministically recurse N/4 times. This allows attackers to consume arbitrary amounts of stack memory and manipulate stack memory to assist in arbitrary code execution attacks. This affects OpenBSD 6.1 and possibly earlier versions.

### [CVE-2017-1000374](Stack-Clash.md)

- A flaw exists in NetBSD's implementation of the stack guard page that allows attackers to bypass it resulting in arbitrary code execution using certain setuid binaries. This affects NetBSD 7.1 and possibly earlier versions.

### [CVE-2017-1000375](Stack-Clash.md)

- NetBSD maps the run-time link-editor ld.so directly below the stack region, even if ASLR is enabled, this allows attackers to more easily manipulate memory leading to arbitrary code execution. This affects NetBSD 7.1 and possibly earlier versions.

### [CVE-2017-1000376](Stack-Clash.md)

- libffi requests an executable stack allowing attackers to more easily trigger arbitrary code execution by overwriting the stack. Please note that libffi is used by a number of other libraries. It was previously stated that this affects libffi version 3.2.1 but this appears to be incorrect. libffi prior to version 3.1 on 32 bit x86 systems was vulnerable, and upstream is believed to have fixed this issue in version 3.1.

### [CVE-2017-1000377](Stack-Clash.md)

- An issue was discovered in the size of the default stack guard page on PAX Linux (originally from GRSecurity but shipped by other Linux vendors), specifically the default stack guard page is not sufficiently large and can be "jumped" over (the stack guard page is bypassed), this affects PAX Linux Kernel versions as of June 19, 2017 (specific version information is not available at this time).

### [CVE-2017-1000378](Stack-Clash.md)

- The NetBSD qsort() function is recursive, and not randomized, an attacker can construct a pathological input array of N elements that causes qsort() to deterministically recurse N/4 times. This allows attackers to consume arbitrary amounts of stack memory and manipulate stack memory to assist in arbitrary code execution attacks. This affects NetBSD 7.1 and possibly earlier versions.

### [CVE-2017-1000379](Stack-Clash.md)

- The Linux Kernel running on AMD64 systems will sometimes map the contents of PIE executable, the heap or ld.so to where the stack is mapped allowing attackers to more easily manipulate the stack. Linux Kernel version 4.11.5 is affected.

### [CVE-2017-1000405](https://medium.com/bindecy/huge-dirty-cow-cve-2017-1000405-110eca132de0)

- The Linux Kernel versions 2.6.38 through 4.14 have a problematic use of pmd_mkdirty() in the touch_pmd() function inside the THP implementation. touch_pmd() can be reached by get_user_pages(). In such case, the pmd will become dirty. This scenario breaks the new can_follow_write_pmd()'s logic - pmd can become dirty without going through a COW cycle. This bug is not as severe as the original "Dirty cow" because an ext4 file (or any other regular file) cannot be mapped using THP. Nevertheless, it does allow us to overwrite read-only huge pages. For example, the zero huge page and sealed shmem files can be overwritten (since their mapping can be populated using THP). Note that after the first write page-fault to the zero page, it will be replaced with a new fresh (and zeroed) thp.

### [CVE-2017-1000424](https://github.com/electron/electron/pull/10008/files)

- Github Electron version 1.6.4 - 1.6.11 and 1.7.0 - 1.7.5 is vulnerable to a URL Spoofing problem when opening PDFs in PDFium resulting loading arbitrary PDFs that a hacker can control.

### [CVE-2017-1000459](https://github.com/leanote/leanote/issues/676)

- Leanote version <= 2.5 is vulnerable to XSS due to not sanitized input in markdown notes.

### [CVE-2017-1002101](https://github.com/bgeesaman/subpath-exploit)

- In Kubernetes versions 1.3.x, 1.4.x, 1.5.x, 1.6.x and prior to versions 1.7.14, 1.8.9 and 1.9.4 containers using subpath volume mounts with any volume type (including non-privileged pods, subject to file permissions) can access files/directories outside of the volume, including the host's filesystem.

### [CVE-2018-0101](https://pastebin.com/YrBcG2Ln)

- A vulnerability in the Secure Sockets Layer (SSL) VPN functionality of the Cisco Adaptive Security Appliance (ASA) Software could allow an unauthenticated, remote attacker to cause a reload of the affected system or to remotely execute code. The vulnerability is due to an attempt to double free a region of memory when the webvpn feature is enabled on the Cisco ASA device. An attacker could exploit this vulnerability by sending multiple, crafted XML packets to a webvpn-configured interface on the affected system. An exploit could allow the attacker to execute arbitrary code and obtain full control of the system, or cause a reload of the affected device. This vulnerability affects Cisco ASA Software that is running on the following Cisco products: 3000 Series Industrial Security Appliance (ISA), ASA 5500 Series Adaptive Security Appliances, ASA 5500-X Series Next-Generation Firewalls, ASA Services Module for Cisco Catalyst 6500 Series Switches and Cisco 7600 Series Routers, ASA 1000V Cloud Firewall, Adaptive Security Virtual Appliance (ASAv), Firepower 2100 Series Security Appliance, Firepower 4110 Security Appliance, Firepower 9300 ASA Security Module, Firepower Threat Defense Software (FTD). Cisco Bug IDs: CSCvg35618.

### [CVE-2018-0114](https://github.com/zi0Black/POC-CVE-2018-0114)

- A vulnerability in the Cisco node-jose open source library before 0.11.0 could allow an unauthenticated, remote attacker to re-sign tokens using a key that is embedded within the token. The vulnerability is due to node-jose following the JSON Web Signature (JWS) standard for JSON Web Tokens (JWTs). This standard specifies that a JSON Web Key (JWK) representing a public key can be embedded within the header of a JWS. This public key is then trusted for verification. An attacker could exploit this by forging valid JWS objects by removing the original signature, adding a new public key to the header, and then signing the object using the (attacker-owned) private key associated with the public key embedded in that JWS header.

### [CVE-2018-0171](https://embedi.com/blog/cisco-smart-install-remote-code-execution/)

- A vulnerability in the Smart Install feature of Cisco IOS Software and Cisco IOS XE Software could allow an unauthenticated, remote attacker to trigger a reload of an affected device, resulting in a denial of service (DoS) condition, or to execute arbitrary code on an affected device. The vulnerability is due to improper validation of packet data. An attacker could exploit this vulnerability by sending a crafted Smart Install message to an affected device on TCP port 4786. A successful exploit could allow the attacker to cause a buffer overflow on the affected device, which could have the following impacts: Triggering a reload of the device, Allowing the attacker to execute arbitrary code on the device, Causing an indefinite loop on the affected device that triggers a watchdog crash. Cisco Bug IDs: CSCvg76186.

### [CVE-2018-0296](https://milo2012.wordpress.com/2018/06/21/cve-2018-0296-script-to-extract-usernames-from-cisco-asa-devices/)

- A vulnerability in the web interface of the Cisco Adaptive Security Appliance (ASA) could allow an unauthenticated, remote attacker to cause an affected device to reload unexpectedly, resulting in a denial of service (DoS) condition. It is also possible on certain software releases that the ASA will not reload, but an attacker could view sensitive system information without authentication by using directory traversal techniques. The vulnerability is due to lack of proper input validation of the HTTP URL. An attacker could exploit this vulnerability by sending a crafted HTTP request to an affected device. An exploit could allow the attacker to cause a DoS condition or unauthenticated disclosure of information. This vulnerability applies to IPv4 and IPv6 HTTP traffic. This vulnerability affects Cisco ASA Software and Cisco Firepower Threat Defense (FTD) Software that is running on the following Cisco products: 3000 Series Industrial Security Appliance (ISA), ASA 1000V Cloud Firewall, ASA 5500 Series Adaptive Security Appliances, ASA 5500-X Series Next-Generation Firewalls, ASA Services Module for Cisco Catalyst 6500 Series Switches and Cisco 7600 Series Routers, Adaptive Security Virtual Appliance (ASAv), Firepower 2100 Series Security Appliance, Firepower 4100 Series Security Appliance, Firepower 9300 ASA Security Module, FTD Virtual (FTDv). Cisco Bug IDs: CSCvi16029.

### [CVE-2018-0492](CVE-2018-0492.md)

- Johnathan Nightingale beep through 1.3.4, if setuid, has a race condition that allows local privilege escalation.

### [CVE-2018-0497](https://tls.mbed.org/tech-updates/security-advisories/mbedtls-security-advisory-2018-02)

- ARM mbed TLS before 2.12.0, before 2.7.5, and before 2.1.14 allows remote attackers to achieve partial plaintext recovery (for a CBC based ciphersuite) via a timing-based side-channel attack. This vulnerability exists because of an incorrect fix (with a wrong SHA-384 calculation) for CVE-2013-0169.

### [CVE-2018-0498](https://tls.mbed.org/tech-updates/security-advisories/mbedtls-security-advisory-2018-02)

- ARM mbed TLS before 2.12.0, before 2.7.5, and before 2.1.14 allows local users to achieve partial plaintext recovery (for a CBC based ciphersuite) via a cache-based side-channel attack.

### [CVE-2018-0743](https://github.com/saaramar/execve_exploit)

- Windows Subsystem for Linux in Windows 10 version 1703, Windows 10 version 1709, and Windows Server, version 1709 allows an elevation of privilege vulnerability due to the way objects are handled in memory, aka "Windows Subsystem for Linux Elevation of Privilege Vulnerability".

### [CVE-2018-0744](https://www.exploit-db.com/exploits/43446/)

- The Windows kernel in Windows 8.1 and RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703 and 1709, Windows Server 2016 and Windows Server, version 1709 allows an elevation of privilege vulnerability due to the way objects are handled in memory, aka "Windows Elevation of Privilege Vulnerability".

### [CVE-2018-0752](https://www.exploit-db.com/exploits/43516/)

- The Windows Kernel API in Windows 8.1 and RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703 and 1709, Windows Server 2016 and Windows Server, version 1709 allows an elevation of privilege vulnerability due to the way the Kernel API enforces permissions, aka "Windows Elevation of Privilege Vulnerability". This CVE ID is unique from CVE-2018-0751.

### [CVE-2018-0758](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0758.md)

- Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0762, CVE-2018-0768, CVE-2018-0769, CVE-2018-0770, CVE-2018-0772, CVE-2018-0773, CVE-2018-0774, CVE-2018-0775, CVE-2018-0776, CVE-2018-0777, CVE-2018-0778, and CVE-2018-0781.

### [CVE-2018-0763](https://twitter.com/j00sean/status/982216053508882433)

- Microsoft Edge in Microsoft Windows 10 1703 and 1709 allows information disclosure, due to how Edge handles objects in memory, aka "Microsoft Edge Information Disclosure Vulnerability". This CVE ID is unique from CVE-2018-0839.

### [CVE-2018-0767](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0767.md)

- Microsoft Edge in Microsoft Windows 10 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to obtain information to further compromise the user's system, due to how the scripting engine handles objects in memory, aka "Scripting Engine Information Disclosure Vulnerability". This CVE ID is unique from CVE-2018-0780 and CVE-2018-0800.

### [CVE-2018-0769](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0769.md)

- Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0758, CVE-2018-0762, CVE-2018-0768, CVE-2018-0770, CVE-2018-0772, CVE-2018-0773, CVE-2018-0774, CVE-2018-0775, CVE-2018-0776, CVE-2018-0777, CVE-2018-0778, and CVE-2018-0781.

### [CVE-2018-0770](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0770.md)

- Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0758, CVE-2018-0762, CVE-2018-0768, CVE-2018-0769, CVE-2018-0772, CVE-2018-0773, CVE-2018-0774, CVE-2018-0775, CVE-2018-0776, CVE-2018-0777, CVE-2018-0778, and CVE-2018-0781.

### [CVE-2018-0774](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0774.md)

- Microsoft Edge in Windows 10 1709 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0758, CVE-2018-0762, CVE-2018-0768, CVE-2018-0769, CVE-2018-0770, CVE-2018-0772, CVE-2018-0773, CVE-2018-0775, CVE-2018-0776, CVE-2018-0777, CVE-2018-0778, and CVE-2018-0781.

### [CVE-2018-0775](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0775.md)

- Microsoft Edge in Windows 10 1709 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0758, CVE-2018-0762, CVE-2018-0768, CVE-2018-0769, CVE-2018-0770, CVE-2018-0772, CVE-2018-0773, CVE-2018-0774, CVE-2018-0776, CVE-2018-0777, CVE-2018-0778, and CVE-2018-0781.

### [CVE-2018-0776](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0776.md)

- Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0758, CVE-2018-0762, CVE-2018-0768, CVE-2018-0769, CVE-2018-0770, CVE-2018-0772, CVE-2018-0773, CVE-2018-0774, CVE-2018-0775, CVE-2018-0777, CVE-2018-0778, and CVE-2018-0781.

### [CVE-2018-0777](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0777.md)

- Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0758, CVE-2018-0762, CVE-2018-0768, CVE-2018-0769, CVE-2018-0770, CVE-2018-0772, CVE-2018-0773, CVE-2018-0774, CVE-2018-0775, CVE-2018-0776, CVE-2018-0778, and CVE-2018-0781.

### [CVE-2018-0780](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0780.md)

- Microsoft Edge in Microsoft Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to obtain information to further compromise the user's system, due to how the scripting engine handles objects in memory, aka "Scripting Engine Information Disclosure Vulnerability". This CVE ID is unique from CVE-2018-0767 and CVE-2018-0800.

### [CVE-2018-0797](https://www.fortinet.com/blog/threat-research/a-root-cause-analysis-of-cve-2018-0797---rich-text-format-styles.html)

- Microsoft Office 2010, Microsoft Office 2013, and Microsoft Office 2016 allow a remote code execution vulnerability due to the way RTF content is handled, aka "Microsoft Word Memory Corruption Vulnerability".

### [CVE-2018-0802](https://github.com/zldww2011/CVE-2018-0802_POC)

- Equation Editor in Microsoft Office 2007, Microsoft Office 2010, Microsoft Office 2013, and Microsoft Office 2016 allow a remote code execution vulnerability due to the way objects are handled in memory, aka "Microsoft Office Memory Corruption Vulnerability". This CVE is unique from CVE-2018-0797 and CVE-2018-0812.

### [CVE-2018-0824](https://codewhitesec.blogspot.com/2018/06/cve-2018-0624.html)

- A remote code execution vulnerability exists in "Microsoft COM for Windows" when it fails to properly handle serialized objects, aka "Microsoft COM for Windows Remote Code Execution Vulnerability." This affects Windows 7, Windows Server 2012 R2, Windows RT 8.1, Windows Server 2008, Windows Server 2012, Windows 8.1, Windows Server 2016, Windows Server 2008 R2, Windows 10, Windows 10 Servers.

### [CVE-2018-0833](https://krbtgt.pw/smbv3-null-pointer-dereference-vulnerability/)

- The Microsoft Server Message Block 2.0 and 3.0 (SMBv2/SMBv3) client in Windows 8.1 and RT 8.1 and Windows Server 2012 R2 allows a denial of service vulnerability due to how specially crafted requests are handled, aka "SMBv2/SMBv3 Null Dereference Denial of Service Vulnerability".

### [CVE-2018-0834](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0834.md)

- Microsoft Edge and ChakraCore in Microsoft Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows remote code execution, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0835, CVE-2018-0836, CVE-2018-0837, CVE-2018-0838, CVE-2018-0840, CVE-2018-0856, CVE-2018-0857, CVE-2018-0858, CVE-2018-0859, CVE-2018-0860, CVE-2018-0861, and CVE-2018-0866.

### [CVE-2018-0835](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0835.md)

- Microsoft Edge and ChakraCore in Microsoft Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows remote code execution, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0834, CVE-2018-0836, CVE-2018-0837, CVE-2018-0838, CVE-2018-0840, CVE-2018-0856, CVE-2018-0857, CVE-2018-0858, CVE-2018-0859, CVE-2018-0860, CVE-2018-0861, and CVE-2018-0866.

### [CVE-2018-0837](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0837.md)

- Microsoft Edge and ChakraCore in Microsoft Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows remote code execution, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0834, CVE-2018-0835, CVE-2018-0836, CVE-2018-0838, CVE-2018-0840, CVE-2018-0856, CVE-2018-0857, CVE-2018-0858, CVE-2018-0859, CVE-2018-0860, CVE-2018-0861, and CVE-2018-0866.

### [CVE-2018-0838](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0838.md)

- Microsoft Edge and ChakraCore in Microsoft Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows remote code execution, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0834, CVE-2018-0835, CVE-2018-0836, CVE-2018-0837, CVE-2018-0840, CVE-2018-0856, CVE-2018-0857, CVE-2018-0858, CVE-2018-0859, CVE-2018-0860, CVE-2018-0861, and CVE-2018-0866.

### [CVE-2018-0840](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0840.md)

- Internet Explorer in Microsoft Windows 7 SP1, Windows Server 2008 R2 SP1, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, and Internet Explorer and Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows remote code execution, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0834, CVE-2018-0835, CVE-2018-0836, CVE-2018-0837, CVE-2018-0838, CVE-2018-0856, CVE-2018-0857, CVE-2018-0858, CVE-2018-0859, CVE-2018-0860, CVE-2018-0861, and CVE-2018-0866.

### [CVE-2018-0860](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0860.md)

- Microsoft Edge and ChakraCore in Microsoft Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows remote code execution, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0834, CVE-2018-0835, CVE-2018-0836, CVE-2018-0837, CVE-2018-0838, CVE-2018-0840, CVE-2018-0856, CVE-2018-0857, CVE-2018-0858, CVE-2018-0859, CVE-2018-0861, and CVE-2018-0866.

### [CVE-2018-0871](https://www.netsparker.com/blog/web-security/stealing-local-files-with-simple-html-file/)

- An information disclosure vulnerability exists when Edge improperly marks files, aka "Microsoft Edge Information Disclosure Vulnerability." This affects Microsoft Edge. This CVE ID is unique from CVE-2018-8234.

### [CVE-2018-0878](https://krbtgt.pw/windows-remote-assistance-xxe-vulnerability/)

- Windows Remote Assistance in Microsoft Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1 and RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703, and 1709, Windows Server 2016 and Windows Server, version 1709 allows an information disclosure vulnerability due to how XML External Entities (XXE) are processed, aka "Windows Remote Assistance Information Disclosure Vulnerability".

### [CVE-2018-0886](CVE-2018-0886.md)

- The Credential Security Support Provider protocol (CredSSP) in Microsoft Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1 and RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703, and 1709 Windows Server 2016 and Windows Server, version 1709 allows a remote code execution vulnerability due to how CredSSP validates request during the authentication process, aka "CredSSP Remote Code Execution Vulnerability".

### [CVE-2018-0891](https://github.com/tunz/js-vuln-db/blob/master/jscript/CVE-2018-0891.md)

- ChakraCore, and Internet Explorer in Microsoft Windows 7 SP1, Windows Server 2008 and R2 SP1, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, and Internet Explorer and Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allow information disclosure, due to how the scripting engine handles objects in memory, aka "Scripting Engine Information Disclosure Vulnerability". This CVE ID is unique from CVE-2018-0939.

### [CVE-2018-0933](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0933.md)

- ChakraCore and Microsoft Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows remote code execution, due to how the Chakra scripting engine handles objects in memory, aka "Chakra Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0872, CVE-2018-0873, CVE-2018-0874, CVE-2018-0930, CVE-2018-0931, CVE-2018-0934, CVE-2018-0936, and CVE-2018-0937.

### [CVE-2018-0934](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0934.md)

- ChakraCore and Microsoft Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows remote code execution, due to how the Chakra scripting engine handles objects in memory, aka "Chakra Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0872, CVE-2018-0873, CVE-2018-0874, CVE-2018-0930, CVE-2018-0931, CVE-2018-0933, CVE-2018-0936, and CVE-2018-0937.

### [CVE-2018-0935](https://github.com/tunz/js-vuln-db/blob/master/jscript/CVE-2018-0935.md)

- Internet Explorer in Microsoft Windows 7 SP1, Windows Server 2008 and R2 SP1, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows remote code execution, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0876, CVE-2018-0889, CVE-2018-0893, and CVE-2018-0925.

### [CVE-2018-0953](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0953.md)

- A remote code execution vulnerability exists in the way that the scripting engine handles objects in memory in Microsoft Edge, aka "Scripting Engine Memory Corruption Vulnerability." This affects Microsoft Edge, ChakraCore. This CVE ID is unique from CVE-2018-0945, CVE-2018-0946, CVE-2018-0951, CVE-2018-0954, CVE-2018-0955, CVE-2018-1022, CVE-2018-8114, CVE-2018-8122, CVE-2018-8128, CVE-2018-8137, CVE-2018-8139.

### [CVE-2018-0980](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0980.md)

- A remote code execution vulnerability exists in the way that the Chakra scripting engine handles objects in memory in Microsoft Edge, aka "Chakra Scripting Engine Memory Corruption Vulnerability." This affects Microsoft Edge, ChakraCore. This CVE ID is unique from CVE-2018-0979, CVE-2018-0990, CVE-2018-0993, CVE-2018-0994, CVE-2018-0995, CVE-2018-1019.

### [CVE-2018-1036](https://sec-consult.com/en/blog/2018/06/pentesters-windows-ntfs-tricks-collection/)

- An elevation of privilege vulnerability exists when NTFS improperly checks access, aka "NTFS Elevation of Privilege Vulnerability." This affects Windows 7, Windows Server 2012 R2, Windows RT 8.1, Windows Server 2008, Windows Server 2012, Windows 8.1, Windows Server 2016, Windows Server 2008 R2, Windows 10, Windows 10 Servers.

### [CVE-2018-1037](https://bugs.chromium.org/p/project-zero/issues/detail?id=1500)

- An information disclosure vulnerability exists when Visual Studio improperly discloses limited contents of uninitialized memory while compiling program database (PDB) files, aka "Microsoft Visual Studio Information Disclosure Vulnerability." This affects Microsoft Visual Studio.

### [CVE-2018-1038](https://blog.frizk.net/2018/03/total-meltdown.html)

- The Windows kernel in Windows 7 SP1 and Windows Server 2008 R2 SP1 allows an elevation of privilege vulnerability due to the way it handles objects in memory, aka "Windows Kernel Elevation of Privilege Vulnerability."

### [CVE-2018-1040](https://www.fortinet.com/blog/threat-research/microsoft-windows-remote-kernel-crash-vulnerability.html)

- A denial of service vulnerability exists in the way that the Windows Code Integrity Module performs hashing, aka "Windows Code Integrity Module Denial of Service Vulnerability." This affects Windows 7, Windows Server 2012 R2, Windows RT 8.1, Windows Server 2008, Windows Server 2012, Windows 8.1, Windows Server 2016, Windows Server 2008 R2, Windows 10, Windows 10 Servers.

### [CVE-2018-1111](https://dynoroot.ninja/)

- DHCP packages in Red Hat Enterprise Linux 6 and 7, Fedora 28, and earlier are vulnerable to a command injection flaw in the NetworkManager integration script included in the DHCP client. A malicious DHCP server, or an attacker on the local network able to spoof DHCP responses, could use this flaw to execute arbitrary commands with root privileges on systems using NetworkManager and configured to obtain network configuration using the DHCP protocol.

### [CVE-2018-1149](https://www.tenable.com/blog/tenable-research-advisory-peekaboo-critical-vulnerability-in-nuuo-network-video-recorder)

- cgi_system in NUUO's NVRMini2 3.8.0 and below allows remote attackers to execute arbitrary code via crafted HTTP requests.

### [CVE-2018-1150](https://www.tenable.com/blog/tenable-research-advisory-peekaboo-critical-vulnerability-in-nuuo-network-video-recorder)

- NUUO's NVRMini2 3.8.0 and below contains a backdoor that would allow an unauthenticated remote attacker to take over user accounts if the file /tmp/moses exists.

### [CVE-2018-1207](https://github.com/KraudSecurity/Exploits/tree/master/CVE-2018-1207)

- Dell EMC iDRAC7/iDRAC8, versions prior to 2.52.52.52, contain CGI injection vulnerability which could be used to execute remote code. A remote unauthenticated attacker may potentially be able to use CGI variables to execute remote code.

### [CVE-2018-1270](https://github.com/CaledoniaProject/CVE-2018-1270)

- Spring Framework, versions 5.0 prior to 5.0.5 and versions 4.3 prior to 4.3.15 and older unsupported versions, allow applications to expose STOMP over WebSocket endpoints with a simple, in-memory STOMP broker through the spring-messaging module. A malicious user (or attacker) can craft a message to the broker that can lead to a remote code execution attack.

### [CVE-2018-1273](https://gist.github.com/matthiaskaiser/bfb274222c009b3570ab26436dc8799e)

- Spring Data Commons, versions prior to 1.13 to 1.13.10, 2.0 to 2.0.5, and older unsupported versions, contain a property binder vulnerability caused by improper neutralization of special elements. An unauthenticated remote malicious user (or attacker) can supply specially crafted request parameters against Spring Data REST backed HTTP resources or using Spring Data's projection-based request payload binding hat can lead to a remote code execution attack.

### [CVE-2018-1275](https://github.com/CaledoniaProject/CVE-2018-1270)

- Spring Framework, versions 5.0 prior to 5.0.5 and versions 4.3 prior to 4.3.16 and older unsupported versions, allow applications to expose STOMP over WebSocket endpoints with a simple, in-memory STOMP broker through the spring-messaging module. A malicious user (or attacker) can craft a message to the broker that can lead to a remote code execution attack. This CVE addresses the partial fix for CVE-2018-1270 in the 4.3.x branch of the Spring Framework.

### [CVE-2018-1335](https://rhinosecuritylabs.com/application-security/exploiting-cve-2018-1335-apache-tika/)

- From Apache Tika versions 1.7 to 1.17, clients could send carefully crafted headers to tika-server that could be used to inject commands into the command line of the server running tika-server. This vulnerability only affects those running tika-server on a server that is open to untrusted clients. The mitigation is to upgrade to Tika 1.18.

### [CVE-2018-1435](https://improsec.com/blog/ibm-advisory-7)

- IBM Notes 8.5 and 9.0 is vulnerable to a DLL hijacking attack. A remote attacker could trick a user to double click a malicious executable in an attacker-controlled directory, which could result in code execution. IBM X-Force ID: 139563.

### [CVE-2018-2628](http://xxlegend.com/2018/04/18/CVE-2018-2628%20%E7%AE%80%E5%8D%95%E5%A4%8D%E7%8E%B0%E5%92%8C%E5%88%86%E6%9E%90/)

- Vulnerability in the Oracle WebLogic Server component of Oracle Fusion Middleware (subcomponent: WLS Core Components). Supported versions that are affected are 10.3.6.0, 12.1.3.0, 12.2.1.2 and 12.2.1.3. Easily exploitable vulnerability allows unauthenticated attacker with network access via T3 to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.0 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).

### [CVE-2018-2694](https://twitter.com/_niklasb/status/953602210088341505)

- Vulnerability in the Oracle VM VirtualBox component of Oracle Virtualization (subcomponent: Core). Supported versions that are affected are Prior to 5.1.32 and Prior to 5.2.6. Easily exploitable vulnerability allows low privileged attacker with logon to the infrastructure where Oracle VM VirtualBox executes to compromise Oracle VM VirtualBox. While the vulnerability is in Oracle VM VirtualBox, attacks may significantly impact additional products. Successful attacks of this vulnerability can result in takeover of Oracle VM VirtualBox. CVSS 3.0 Base Score 8.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H).

### [CVE-2018-2698](https://blogs.securiteam.com/index.php/archives/3649)

- Vulnerability in the Oracle VM VirtualBox component of Oracle Virtualization (subcomponent: Core). Supported versions that are affected are Prior to 5.1.32 and Prior to 5.2.6. Easily exploitable vulnerability allows low privileged attacker with logon to the infrastructure where Oracle VM VirtualBox executes to compromise Oracle VM VirtualBox. While the vulnerability is in Oracle VM VirtualBox, attacks may significantly impact additional products. Successful attacks of this vulnerability can result in takeover of Oracle VM VirtualBox. CVSS 3.0 Base Score 8.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H).

### [CVE-2018-2844](https://www.voidsecurity.in/2018/08/from-compiler-optimization-to-code.html)

- Vulnerability in the Oracle VM VirtualBox component of Oracle Virtualization (subcomponent: Core). Supported versions that are affected are Prior to 5.1.36 and Prior to 5.2.10. Easily exploitable vulnerability allows low privileged attacker with logon to the infrastructure where Oracle VM VirtualBox executes to compromise Oracle VM VirtualBox. While the vulnerability is in Oracle VM VirtualBox, attacks may significantly impact additional products. Successful attacks of this vulnerability can result in takeover of Oracle VM VirtualBox. CVSS 3.0 Base Score 8.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H).

### [CVE-2018-2860](https://github.com/niklasb/sploits/tree/master/virtualbox/hgcm-oob)

- Vulnerability in the Oracle VM VirtualBox component of Oracle Virtualization (subcomponent: Core). Supported versions that are affected are Prior to 5.1.36 and Prior to 5.2.10. Easily exploitable vulnerability allows high privileged attacker with logon to the infrastructure where Oracle VM VirtualBox executes to compromise Oracle VM VirtualBox. While the vulnerability is in Oracle VM VirtualBox, attacks may significantly impact additional products. Successful attacks of this vulnerability can result in takeover of Oracle VM VirtualBox. CVSS 3.0 Base Score 8.2 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:L/AC:L/PR:H/UI:N/S:C/C:H/I:H/A:H).

### [CVE-2018-2893](https://github.com/pyn3rd/CVE-2018-2893)

- Vulnerability in the Oracle WebLogic Server component of Oracle Fusion Middleware (subcomponent: WLS Core Components). Supported versions that are affected are 10.3.6.0, 12.1.3.0, 12.2.1.2 and 12.2.1.3. Easily exploitable vulnerability allows unauthenticated attacker with network access via T3 to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.0 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).

### [CVE-2018-2894](https://github.com/LandGrey/CVE-2018-2894/)

- Vulnerability in the Oracle WebLogic Server component of Oracle Fusion Middleware (subcomponent: WLS - Web Services). Supported versions that are affected are 10.3.6.0, 12.1.3.0, 12.2.1.2 and 12.2.1.3. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.0 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).

### [CVE-2018-3055](https://github.com/niklasb/3dpwn/tree/master/CVE-2018-3055%2B3085)

- Vulnerability in the Oracle VM VirtualBox component of Oracle Virtualization (subcomponent: Core). The supported version that is affected is Prior to 5.2.16. Easily exploitable vulnerability allows unauthenticated attacker with logon to the infrastructure where Oracle VM VirtualBox executes to compromise Oracle VM VirtualBox. Successful attacks require human interaction from a person other than the attacker and while the vulnerability is in Oracle VM VirtualBox, attacks may significantly impact additional products. Successful attacks of this vulnerability can result in unauthorized ability to cause a hang or frequently repeatable crash (complete DOS) of Oracle VM VirtualBox and unauthorized read access to a subset of Oracle VM VirtualBox accessible data. CVSS 3.0 Base Score 7.1 (Confidentiality and Availability impacts). CVSS Vector: (CVSS:3.0/AV:L/AC:L/PR:N/UI:R/S:C/C:L/I:N/A:H).

### [CVE-2018-3085](https://github.com/niklasb/3dpwn/tree/master/CVE-2018-3055%2B3085)

- Vulnerability in the Oracle VM VirtualBox component of Oracle Virtualization (subcomponent: Core). The supported version that is affected is Prior to 5.2.16. Easily exploitable vulnerability allows unauthenticated attacker with logon to the infrastructure where Oracle VM VirtualBox executes to compromise Oracle VM VirtualBox. Successful attacks require human interaction from a person other than the attacker and while the vulnerability is in Oracle VM VirtualBox, attacks may significantly impact additional products. Successful attacks of this vulnerability can result in unauthorized creation, deletion or modification access to critical data or all Oracle VM VirtualBox accessible data as well as unauthorized read access to a subset of Oracle VM VirtualBox accessible data and unauthorized ability to cause a hang or frequently repeatable crash (complete DOS) of Oracle VM VirtualBox. CVSS 3.0 Base Score 8.5 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:L/AC:L/PR:N/UI:R/S:C/C:L/I:H/A:H).

### [CVE-2018-3191](https://github.com/voidfyoo/CVE-2018-3191/)

- Vulnerability in the Oracle WebLogic Server component of Oracle Fusion Middleware (subcomponent: WLS Core Components). Supported versions that are affected are 10.3.6.0, 12.1.3.0 and 12.2.1.3. Easily exploitable vulnerability allows unauthenticated attacker with network access via T3 to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.0 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).

### [CVE-2018-3245](https://github.com/pyn3rd/CVE-2018-3245)

- Vulnerability in the Oracle WebLogic Server component of Oracle Fusion Middleware (subcomponent: WLS Core Components). Supported versions that are affected are 10.3.6.0, 12.1.3.0 and 12.2.1.3. Easily exploitable vulnerability allows unauthenticated attacker with network access via T3 to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.0 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).

### [CVE-2018-3253](https://www.trustedsec.com/2018/10/w32-coozie-discovering-oracle-cve-2018-3253/)

- Vulnerability in the Oracle Virtual Directory component of Oracle Fusion Middleware (subcomponent: Virtual Directory Manager). Supported versions that are affected are 11.1.1.7.0 and 11.1.1.9.0. Difficult to exploit vulnerability allows low privileged attacker with network access via HTTP to compromise Oracle Virtual Directory. Successful attacks of this vulnerability can result in unauthorized update, insert or delete access to some of Oracle Virtual Directory accessible data as well as unauthorized read access to a subset of Oracle Virtual Directory accessible data and unauthorized ability to cause a partial denial of service (partial DOS) of Oracle Virtual Directory. CVSS 3.0 Base Score 8.5 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:H).

### [CVE-2018-3615](https://foreshadowattack.eu/foreshadow.pdf)

- Systems with microprocessors utilizing speculative execution and Intel software guard extensions (Intel SGX) may allow unauthorized disclosure of information residing in the L1 data cache from an enclave to an attacker with local user access via a side-channel analysis.

### [CVE-2018-3693](https://arxiv.org/pdf/1807.03757.pdf)

- Systems with microprocessors utilizing speculative execution and branch prediction may allow unauthorized disclosure of information to an attacker with local user access via a speculative buffer overflow and side-channel analysis.

### [CVE-2018-3760](https://github.com/rails/sprockets/commit/c09131cf5b2c479263939c8582e22b98ed616c5f)

- There is an information leak vulnerability in Sprockets. Versions Affected: 4.0.0.beta7 and lower, 3.7.1 and lower, 2.12.4 and lower. Specially crafted requests can be used to access files that exists on the filesystem that is outside an application's root directory, when the Sprockets server is used in production. All users running an affected release should either upgrade or use one of the work arounds immediately.

### [CVE-2018-3784](https://hackerone.com/reports/350418)

- A code injection in cryo 0.0.6 allows an attacker to arbitrarily execute code due to insecure implementation of deserialization.

### [CVE-2018-3893](https://www.talosintelligence.com/reports/TALOS-2018-0570/)

- An exploitable buffer overflow vulnerability exists in the /cameras/XXXX/clips handler of video-core's HTTP server of Samsung SmartThings Hub STH-ETH-250 - Firmware version 0.20.17. The video-core process incorrectly extracts fields from a user-controlled JSON payload, leading to a buffer overflow on the stack. An attacker can send an HTTP request to trigger this vulnerability.

### [CVE-2018-3894](https://www.talosintelligence.com/reports/TALOS-2018-0570/)

- An exploitable buffer overflow vulnerability exists in the /cameras/XXXX/clips handler of video-core's HTTP server of Samsung SmartThings Hub STH-ETH-250-Firmware version 0.20.17. The strncpy call overflows the destination buffer, which has a size of 52 bytes. An attacker can send an arbitrarily long "startTime" value in order to exploit this vulnerability.

### [CVE-2018-3895](https://www.talosintelligence.com/reports/TALOS-2018-0570/)

- An exploitable buffer overflow vulnerability exists in the /cameras/XXXX/clips handler of video-core's HTTP server of Samsung SmartThings Hub STH-ETH-250 Firmware version 0.20.17. The strncpy call overflows the destination buffer, which has a size of 52 bytes. An attacker can send an arbitrarily long 'endTime' value in order to exploit this vulnerability. An attacker can send an HTTP request to trigger this vulnerability.

### [CVE-2018-3896](https://www.talosintelligence.com/reports/TALOS-2018-0570/)

- An exploitable buffer overflow vulnerabilities exist in the /cameras/XXXX/clips handler of video-core's HTTP server of Samsung SmartThings Hub with Firmware version 0.20.17. The video-core process incorrectly extracts fields from a user-controlled JSON payload, leading to a buffer overflow on the stack. The strncpy call overflows the destination buffer, which has a size of 52 bytes. An attacker can send an arbitrarily long "correlationId" value in order to exploit this vulnerability.

### [CVE-2018-3897](https://www.talosintelligence.com/reports/TALOS-2018-0570/)

- An exploitable buffer overflow vulnerabilities exist in the /cameras/XXXX/clips handler of video-core's HTTP server of Samsung SmartThings Hub with Firmware version 0.20.17. The video-core process incorrectly extracts fields from a user-controlled JSON payload, leading to a buffer overflow on the stack. The strncpy call overflows the destination buffer, which has a size of 52 bytes. An attacker can send an arbitrarily long "callbackUrl" value in order to exploit this vulnerability.

### [CVE-2018-3903](https://www.talosintelligence.com/reports/TALOS-2018-0574/)

- On Samsung SmartThings Hub STH-ETH-250 devices with firmware version 0.20.17, the video-core process incorrectly extracts fields from a user-controlled JSON payload, leading to a buffer overflow on the stack. An attacker can send an HTTP request to trigger this vulnerability. The memcpy call overflows the destination buffer, which has a size of 512 bytes. An attacker can send an arbitrarily long "url" value in order to overwrite the saved-PC with 0x42424242.

### [CVE-2018-3904](https://www.talosintelligence.com/reports/TALOS-2018-0574/)

- An exploitable buffer overflow vulnerability exists in the camera 'update' feature of video-core's HTTP server of Samsung SmartThings Hub STH-ETH-250 - Firmware version 0.20.17. The video-core process incorrectly extracts fields from a user-controlled JSON payload, leading to a buffer overflow on the stack. An attacker can send an HTTP request to trigger this vulnerability.

### [CVE-2018-3905](https://www.talosintelligence.com/reports/TALOS-2018-0575/)

- An exploitable buffer overflow vulnerability exists in the camera "create" feature of video-core's HTTP server of Samsung SmartThings Hub STH-ETH-250 devices with firmware version 0.20.17. The video-core process incorrectly extracts the "state" field from a user-controlled JSON payload, leading to a buffer overflow on the stack. An attacker can send an HTTP request to trigger this vulnerability.

### [CVE-2018-3952](https://www.talosintelligence.com/reports/TALOS-2018-0622)

- An exploitable code execution vulnerability exists in the connect functionality of NordVPN 6.14.28.0. A specially crafted configuration file can cause a privilege escalation, resulting in the execution of arbitrary commands with system privileges.

### [CVE-2018-3971](https://blog.talosintelligence.com/2018/11/TALOS-2018-0636.html)

- An exploitable arbitrary write vulnerability exists in the 0x2222CC IOCTL handler functionality of Sophos HitmanPro.Alert 3.7.6.744. A specially crafted IRP request can cause the driver to write data under controlled by an attacker address, resulting in memory corruption. An attacker can send IRP request to trigger this vulnerability.

### [CVE-2018-4087](https://blog.zimperium.com/cve-2018-4087-poc-escaping-sandbox-misleading-bluetoothd/)

- An issue was discovered in certain Apple products. iOS before 11.2.5 is affected. tvOS before 11.2.5 is affected. watchOS before 4.2.2 is affected. The issue involves the "Core Bluetooth" component. It allows attackers to execute arbitrary code in a privileged context or cause a denial of service (memory corruption) via a crafted app.

### [CVE-2018-4010](https://www.talosintelligence.com/reports/TALOS-2018-0679)

- An exploitable code execution vulnerability exists in the connect functionality of ProtonVPN VPN client 1.5.1. A specially crafted configuration file can cause a privilege escalation, resulting in the ability to execute arbitrary commands with the system's privileges.

### [CVE-2018-4121](https://github.com/mwrlabs/CVE-2018-4121)

- An issue was discovered in certain Apple products. iOS before 11.3 is affected. Safari before 11.1 is affected. iCloud before 7.4 on Windows is affected. iTunes before 12.7.4 on Windows is affected. tvOS before 11.3 is affected. watchOS before 4.3 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2018-4148](https://comsecuris.com/blog/posts/theres_life_in_the_old_dog_yet_tearing_new_holes_into_inteliphone_cellular_modems/)

- An issue was discovered in certain Apple products. iOS before 11.3 is affected. The issue involves the "Telephony" component. A buffer overflow allows remote attackers to execute arbitrary code.

### [CVE-2018-4150](https://pastebin.com/raw/XTfhN2Cj)

- An issue was discovered in certain Apple products. iOS before 11.3 is affected. macOS before 10.13.4 is affected. tvOS before 11.3 is affected. watchOS before 4.3 is affected. The issue involves the "Kernel" component. It allows attackers to execute arbitrary code in a privileged context or cause a denial of service (memory corruption) via a crafted app.

### [CVE-2018-4192](https://github.com/wzw19890321/Exploits/tree/master/CVE-2018-4192)

- An issue was discovered in certain Apple products. iOS before 11.4 is affected. Safari before 11.1.1 is affected. iCloud before 7.5 on Windows is affected. iTunes before 12.7.5 on Windows is affected. tvOS before 11.4 is affected. watchOS before 4.3.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code via a crafted web site that leverages a race condition.

### [CVE-2018-4204](https://github.com/Metnew/uxss-db/tree/master/webkit/CVE-2018-4204)

- An issue was discovered in certain Apple products. iOS before 11.4 is affected. iOS before 11.3.1 is affected. Safari before 11.1 is affected. iCloud before 7.5 on Windows is affected. iTunes before 12.7.5 on Windows is affected. tvOS before 11.4 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2018-4233](https://github.com/saelo/cve-2018-4233)

- An issue was discovered in certain Apple products. iOS before 11.4 is affected. Safari before 11.1.1 is affected. iCloud before 7.5 on Windows is affected. iTunes before 12.7.5 on Windows is affected. tvOS before 11.4 is affected. watchOS before 4.3.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2018-4262](https://github.com/wzw19890321/Exploits/tree/master/CVE-2018-4262)

- In Safari before 11.1.2, iTunes before 12.8 for Windows, iOS before 11.4.1, tvOS before 11.4.1, iCloud for Windows before 7.6, multiple memory corruption issues were addressed with improved memory handling.

### [CVE-2018-4307](https://www.rafaybaloch.com/2018/09/apple-safari-microsoft-edge-browser.html)

- A logic issue was addressed with improved state management. This issue affected versions prior to iOS 12, Safari 12.

### [CVE-2018-4330](https://github.com/omerporze/toothfairy)

- In iOS before 11.4, a memory corruption issue exists and was addressed with improved memory handling.

### [CVE-2018-4338](https://www.zerodayinitiative.com/blog/2018/10/24/cve-2018-4338-triggering-an-information-disclosure-on-macos-through-a-broadcom-airport-kext)

- A validation issue was addressed with improved input sanitization. This issue affected versions prior to macOS Mojave 10.14.

### [CVE-2018-4407](https://lgtm.com/blog/apple_xnu_icmp_error_CVE-2018-4407)

- A memory corruption issue was addressed with improved validation. This issue affected versions prior to iOS 12, macOS Mojave 10.14, tvOS 12, watchOS 5.

### [CVE-2018-4415](https://blogs.securiteam.com/index.php/archives/3796)

- A memory corruption issue was addressed with improved memory handling. This issue affected versions prior to macOS Mojave 10.14.1.

### [CVE-2018-4878](CVE-2018-4878.md)

- A use-after-free vulnerability was discovered in Adobe Flash Player before 28.0.0.161. This vulnerability occurs due to a dangling pointer in the Primetime SDK related to the handling of listener objects. A successful attack can lead to arbitrary code execution. This was exploited in the wild in January and February 2018.

### [CVE-2018-4990](https://cloudblogs.microsoft.com/microsoftsecure/2018/07/02/taking-apart-a-double-zero-day-sample-discovered-in-joint-hunt-with-eset/)

- Adobe Acrobat and Reader versions 2018.011.20038 and earlier, 2017.011.30079 and earlier, and 2015.006.30417 and earlier have a Double Free vulnerability. Successful exploitation could lead to arbitrary code execution in the context of the current user.

### [CVE-2018-4993](https://research.checkpoint.com/ntlm-credentials-theft-via-pdf-files/)

- Adobe Acrobat and Reader versions 2018.011.20038 and earlier, 2017.011.30079 and earlier, and 2015.006.30417 and earlier have an NTLM SSO hash theft vulnerability. Successful exploitation could lead to information disclosure.

### [CVE-2018-5002](http://blogs.360.cn/blog/cve-2018-5002-en/)

- Adobe Flash Player versions 29.0.0.171 and earlier have a Stack-based buffer overflow vulnerability. Successful exploitation could lead to arbitrary code execution in the context of the current user.

### [CVE-2018-5146](http://blogs.360.cn/blog/how-to-kill-a-firefox-en/)

- An out of bounds memory write while processing Vorbis audio data was reported through the Pwn2Own contest. This vulnerability affects Firefox < 59.0.1, Firefox ESR < 52.7.2, and Thunderbird < 52.7.

### [CVE-2018-5175](https://mksben.l0.cm/2018/05/cve-2018-5175-firefox-csp-strict-dynamic-bypass.html)

- A mechanism to bypass Content Security Policy (CSP) protections on sites that have a "script-src" policy of "'strict-dynamic'". If a target website contains an HTML injection flaw an attacker could inject a reference to a copy of the "require.js" library that is part of Firefox's Developer Tools, and then use a known technique using that library to bypass the CSP restrictions on executing injected scripts. This vulnerability affects Firefox < 60.

### [CVE-2018-5181](https://pastebin.com/raw/nbQJnfee)

- If a URL using the "file:" protocol is dragged and dropped onto an open tab that is running in a different child process the tab will open a local file corresponding to the dropped URL, contrary to policy. One way to make the target tab open more reliably in a separate process is to open it with the "noopener" keyword. This vulnerability affects Firefox < 60.

### [CVE-2018-5189](https://www.fidusinfosec.com/jungo-windriver-code-execution-cve-2018-5189)

- Race condition in Jungo Windriver 12.5.1 allows local users to cause a denial of service (buffer overflow) or gain system privileges by flipping pool buffer size, aka a "double fetch" vulnerability.

### [CVE-2018-5318](https://paper.seebug.org/504/)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2018-5390](https://git.kernel.org/pub/scm/linux/kernel/git/davem/net.git/commit/?id=1a4f14bab1868b443f0dd3c55b689a478f82e72e)

- Linux kernel versions 4.9+ can be forced to make very expensive calls to tcp_collapse_ofo_queue() and tcp_prune_ofo_queue() for every incoming packet which can lead to a denial of service.

### [CVE-2018-5553](https://blog.rapid7.com/2018/06/12/r7-2018-15-cve-2018-5553-crestron-dge-100-console-command-injection-fixed/)

- The Crestron Console service running on DGE-100, DM-DGE-200-C, and TS-1542-C devices with default configuration and running firmware versions 1.3384.00049.001 and lower are vulnerable to command injection that can be used to gain root-level access.

### [CVE-2018-5711](http://blog.orange.tw/2018/01/php-cve-2018-5711-hanging-websites-by.html)

- gd_gif_in.c in the GD Graphics Library (aka libgd), as used in PHP before 5.6.33, 7.0.x before 7.0.27, 7.1.x before 7.1.13, and 7.2.x before 7.2.1, has an integer signedness error that leads to an infinite loop via a crafted GIF file, as demonstrated by a call to the imagecreatefromgif or imagecreatefromstring PHP function. This is related to GetCode_ and gdImageCreateFromGifCtx.

### [CVE-2018-5924](https://research.checkpoint.com/sending-fax-back-to-the-dark-ages/)

- A security vulnerability has been identified with certain HP Inkjet printers. A maliciously crafted file sent to an affected device can cause a stack buffer overflow, which could allow remote code execution.

### [CVE-2018-5925](https://research.checkpoint.com/sending-fax-back-to-the-dark-ages/)

- A security vulnerability has been identified with certain HP Inkjet printers. A maliciously crafted file sent to an affected device can cause a static buffer overflow, which could allow remote code execution.

### [CVE-2018-5996](https://landave.io/2018/01/7-zip-multiple-memory-corruptions-via-rar-and-zip/)

- Insufficient exception handling in the method NCompress::NRar3::CDecoder::Code of 7-Zip before 18.00 and p7zip can lead to multiple memory corruptions within the PPMd code, allows remote attackers to cause a denial of service (segmentation fault) or execute arbitrary code via a crafted RAR archive.

### [CVE-2018-6034](https://bugs.chromium.org/p/chromium/issues/detail?id=784183)

- Insufficient data validation in WebGL in Google Chrome prior to 64.0.3282.119 allowed a remote attacker to perform an out of bounds memory read via a crafted HTML page.

### [CVE-2018-6055](https://bugs.chromium.org/p/project-zero/issues/detail?id=1450)

- Insufficient policy enforcement in Catalog Service in Google Chrome prior to 64.0.3282.119 allowed a remote attacker to potentially run arbitrary code outside sandbox via a crafted HTML page.

### [CVE-2018-6056](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2018-6056.md)

- Type confusion could lead to a heap out-of-bounds write in V8 in Google Chrome prior to 64.0.3282.168 allowing a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page.

### [CVE-2018-6061](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2018-6061.md)

- A race in the handling of SharedArrayBuffers in WebAssembly in Google Chrome prior to 65.0.3325.146 allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page.

### [CVE-2018-6064](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2018-6064.md)

- Type Confusion in the implementation of __defineGetter__ in V8 in Google Chrome prior to 65.0.3325.146 allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page.

### [CVE-2018-6065](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2018-6065.md)

- Integer overflow in computing the required allocation size when instantiating a new javascript object in V8 in Google Chrome prior to 65.0.3325.146 allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page.

### [CVE-2018-6072](https://bugs.chromium.org/p/chromium/issues/detail?id=791048)

- An integer overflow leading to use after free in PDFium in Google Chrome prior to 65.0.3325.146 allowed a remote attacker to potentially exploit heap corruption via a crafted PDF file.

### [CVE-2018-6106](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2018-6106.md)

- An asynchronous generator may return an incorrect state in V8 in Google Chrome prior to 66.0.3359.117 allowing a remote attacker to potentially exploit object corruption via a crafted HTML page.

### [CVE-2018-6128](https://bugs.chromium.org/p/chromium/issues/detail?id=841105)

- Incorrect URL parsing in WebKit in Google Chrome on iOS prior to 67.0.3396.62 allowed a remote attacker to perform domain spoofing via a crafted HTML page.

### [CVE-2018-6177](https://bugs.chromium.org/p/chromium/issues/detail?id=826187)

- Information leak in media engine in Google Chrome prior to 68.0.3440.75 allowed a remote attacker to leak cross-origin data via a crafted HTML page.

### [CVE-2018-6184](https://github.com/zeit/next.js/commit/bba744d3faa2e91bc3a3c934e8563553c430b2a2)

- ZEIT Next.js 4 before 4.2.3 has Directory Traversal under the /_next request namespace.

### [CVE-2018-6317](https://medium.com/secjuice/claymore-dual-gpu-miner-10-5-format-strings-vulnerability-916ab3d2db30)

- The remote management interface in Claymore Dual Miner 10.5 and earlier is vulnerable to an unauthenticated format string vulnerability, allowing remote attackers to read memory or cause a denial of service.

### [CVE-2018-6376](https://www.notsosecure.com/analyzing-cve-2018-6376/)

- In Joomla! before 3.8.4, the lack of type casting of a variable in a SQL statement leads to a SQL injection vulnerability in the Hathor postinstall message.

### [CVE-2018-6389](https://baraktawily.blogspot.tw/2018/02/how-to-dos-29-of-world-wide-websites.html)

- In WordPress through 4.9.2, unauthenticated attackers can cause a denial of service (resource consumption) by using the large list of registered .js files (from wp-includes/script-loader.php) to construct a series of requests to load every file many times.

### [CVE-2018-6460](http://www.paulosyibelo.com/2018/02/hotspot-shield-cve-2018-6460-sensitive.html)

- Hotspot Shield runs a webserver with a static IP address 127.0.0.1 and port 895. The web server uses JSONP and hosts sensitive information including configuration. User controlled input is not sufficiently filtered: an unauthenticated attacker can send a POST request to /status.js with the parameter func=$_APPLOG.Rfunc and extract sensitive information about the machine, including whether the user is connected to a VPN, to which VPN he/she is connected, and what is their real IP address.

### [CVE-2018-6789](https://medium.com/@straightblast426/my-poc-walk-through-for-cve-2018-6789-2e402e4ff588)

- An issue was discovered in the base64d function in the SMTP listener in Exim before 4.90.1. By sending a handcrafted message, a buffer overflow may happen. This can be used to execute code remotely.

### [CVE-2018-6794](https://github.com/kirillwow/ids_bypass)

- Suricata before 4.1 is prone to an HTTP detection bypass vulnerability in detect.c and stream-tcp.c. If a malicious server breaks a normal TCP flow and sends data before the 3-way handshake is complete, then the data sent by the malicious server will be accepted by web clients such as a web browser or Linux CLI utilities, but ignored by Suricata IDS signatures. This mostly affects IDS signatures for the HTTP protocol and TCP stream content; signatures for TCP packets will inspect such network traffic as usual.

### [CVE-2018-6851](https://labs.nettitude.com/blog/cve-2018-6851-to-cve-2018-6857-sophos-privilege-escalation-vulnerabilities/)

- Sophos SafeGuard Enterprise before 8.00.5, SafeGuard Easy before 7.00.3, and SafeGuard LAN Crypt before 3.95.2 are vulnerable to Local Privilege Escalation via IOCTL 0x80206040. By crafting an input buffer we can control the execution path to the point where the constant DWORD 0 will be written to a user-controlled address. We can take advantage of this condition to zero-out the pointer to the security descriptor in the object header of a privileged process or modify the security descriptor itself and run code in the context of a process running as SYSTEM.

### [CVE-2018-6852](https://labs.nettitude.com/blog/cve-2018-6851-to-cve-2018-6857-sophos-privilege-escalation-vulnerabilities/)

- Sophos SafeGuard Enterprise before 8.00.5, SafeGuard Easy before 7.00.3, and SafeGuard LAN Crypt before 3.95.2 are vulnerable to Local Privilege Escalation via IOCTL 0x80202298. By crafting an input buffer we can control the execution path to the point where the nt!memset function is called to zero out contents of a user-controlled address. We can take advantage of this condition to zero-out the pointer to the security descriptor in the object header of a privileged process or modify the security descriptor itself and run code in the context of a process running as SYSTEM.

### [CVE-2018-6853](https://labs.nettitude.com/blog/cve-2018-6851-to-cve-2018-6857-sophos-privilege-escalation-vulnerabilities/)

- Sophos SafeGuard Enterprise before 8.00.5, SafeGuard Easy before 7.00.3, and SafeGuard LAN Crypt before 3.95.2 are vulnerable to Local Privilege Escalation via IOCTL 0x80206024. By crafting an input buffer we can control the execution path to the point where a global variable will be written to a user controlled address. We can take advantage of this condition to zero-out the pointer to the security descriptor in the object header of a privileged process or modify the security descriptor itself and run code in the context of a process running as SYSTEM.

### [CVE-2018-6854](https://labs.nettitude.com/blog/cve-2018-6851-to-cve-2018-6857-sophos-privilege-escalation-vulnerabilities/)

- Sophos SafeGuard Enterprise before 8.00.5, SafeGuard Easy before 7.00.3, and SafeGuard LAN Crypt before 3.95.2 are vulnerable to Local Privilege Escalation via multiple IOCTLs, e.g., 0x8810200B, 0x8810200F, 0x8810201B, 0x8810201F, 0x8810202B, 0x8810202F, 0x8810203F, 0x8810204B, 0x88102003, 0x88102007, 0x88102013, 0x88102017, 0x88102027, 0x88102033, 0x88102037, 0x88102043, and 0x88102047. When some conditions in the user-controlled input buffer are not met, the driver writes an error code (0x2000001A) to a user-controlled address. Also, note that all the aforementioned IOCTLs use transfer type METHOD_NEITHER, which means that the I/O manager does not validate any of the supplied pointers and buffer sizes. So, even though the driver checks for input/output buffer sizes, it doesn't validate if the pointers to those buffers are actually valid. So, we can supply a pointer for the output buffer to a kernel address space address, and the error code will be written there. We can take advantage of this condition to modify the SEP_TOKEN_PRIVILEGES structure of the Token object belonging to the exploit process and grant SE_DEBUG_NAME privilege. This allows the exploit process to interact with higher privileged processes running as SYSTEM and execute code in their security context.

### [CVE-2018-6855](https://labs.nettitude.com/blog/cve-2018-6851-to-cve-2018-6857-sophos-privilege-escalation-vulnerabilities/)

- Sophos SafeGuard Enterprise before 8.00.5, SafeGuard Easy before 7.00.3, and SafeGuard LAN Crypt before 3.95.2 are vulnerable to Local Privilege Escalation via IOCTL 0x80202014. By crafting an input buffer we can control the execution path to the point where the constant 0xFFFFFFF will be written to a user-controlled address. We can take advantage of this condition to modify the SEP_TOKEN_PRIVILEGES structure of the Token object belonging to the exploit process and grant SE_DEBUG_NAME privilege. This allows the exploit process to interact with higher privileged processes running as SYSTEM and execute code in their security context.

### [CVE-2018-6856](https://labs.nettitude.com/blog/cve-2018-6851-to-cve-2018-6857-sophos-privilege-escalation-vulnerabilities/)

- Sophos SafeGuard Enterprise before 8.00.5, SafeGuard Easy before 7.00.3, and SafeGuard LAN Crypt before 3.95.2 are vulnerable to Local Privilege Escalation via IOCTL 0x8020601C. By crafting an input buffer we can control the execution path to the point where a global variable will be written to a user controlled address. We can take advantage of this condition to zero-out the pointer to the security descriptor in the object header of a privileged process or modify the security descriptor itself and run code in the context of a process running as SYSTEM.

### [CVE-2018-6857](https://labs.nettitude.com/blog/cve-2018-6851-to-cve-2018-6857-sophos-privilege-escalation-vulnerabilities/)

- Sophos SafeGuard Enterprise before 8.00.5, SafeGuard Easy before 7.00.3, and SafeGuard LAN Crypt before 3.95.2 are vulnerable to Local Privilege Escalation via IOCTL 0x802022E0. By crafting an input buffer we can control the execution path to the point where the constant 0x12 will be written to a user-controlled address. We can take advantage of this condition to modify the SEP_TOKEN_PRIVILEGES structure of the Token object belonging to the exploit process and grant SE_DEBUG_NAME privilege. This allows the exploit process to interact with higher privileged processes running as SYSTEM and execute code in their security context.

### [CVE-2018-6871](https://github.com/jollheef/libreoffice-remote-arbitrary-file-disclosure)

- LibreOffice through 6.0.1 allows remote attackers to read arbitrary files via =WEBSERVICE calls in a document, which use the COM.MICROSOFT.WEBSERVICE function.

### [CVE-2018-6954](https://github.com/systemd/systemd/issues/7986)

- systemd-tmpfiles in systemd through 237 mishandles symlinks present in non-terminal path components, which allows local users to obtain ownership of arbitrary files via vectors involving creation of a directory and a file under that directory, and later replacing that directory with a symlink. This occurs even if the fs.protected_symlinks sysctl is turned on.

### [CVE-2018-7182](https://dumpco.re/blog/cve-2018-7182)

- The ctl_getitem method in ntpd in ntp-4.2.8p6 before 4.2.8p11 allows remote attackers to cause a denial of service (out-of-bounds read) via a crafted mode 6 packet with a ntpd instance from 4.2.8p6 through 4.2.8p10.

### [CVE-2018-7260](https://github.com/phpmyadmin/phpmyadmin/commit/d2886a3)

- Cross-site scripting (XSS) vulnerability in db_central_columns.php in phpMyAdmin before 4.7.8 allows remote authenticated users to inject arbitrary web script or HTML via a crafted URL.

### [CVE-2018-7273](https://remoteawesomethoughts.blogspot.tw/2018/03/cve-2018-7273-poc.html)

- In the Linux kernel through 4.15.4, the floppy driver reveals the addresses of kernel functions and global variables using printk calls within the function show_floppy in drivers/block/floppy.c. An attacker can read this information from dmesg and use the addresses to find the locations of kernel code and data and bypass kernel security protections such as KASLR.

### [CVE-2018-7600](CVE-2018-7600.md)

- Drupal before 7.58, 8.x before 8.3.9, 8.4.x before 8.4.6, and 8.5.x before 8.5.1 allows remote attackers to execute arbitrary code because of an issue affecting multiple subsystems with default or common module configurations.

### [CVE-2018-7602](https://www.exploit-db.com/exploits/44542/)

- A remote code execution vulnerability exists within multiple subsystems of Drupal 7.x and 8.x. This potentially allows attackers to exploit multiple attack vectors on a Drupal site, which could result in the site being compromised. This vulnerability is related to Drupal core - Highly critical - Remote Code Execution - SA-CORE-2018-002. Both SA-CORE-2018-002 and this vulnerability are being exploited in the wild.

### [CVE-2018-7738](https://blog.grimm-co.com/post/malicious-command-execution-via-bash-completion-cve-2018-7738/)

- In util-linux before 2.32-rc1, bash-completion/umount allows local users to gain privileges by embedding shell commands in a mountpoint name, which is mishandled during a umount command (within Bash) by a different user, as demonstrated by logging in as root and entering umount followed by a tab character for autocompletion.

### [CVE-2018-8021](https://github.com/r3dxpl0it/Apache-Superset-Remote-Code-Execution-PoC-CVE-2018-8021)

- Versions of Superset prior to 0.23 used an unsafe load method from the pickle library to deserialize data leading to possible remote code execution. Note Superset 0.23 was released prior to any Superset release under the Apache Software Foundation.

### [CVE-2018-8120](https://github.com/bigric3/cve-2018-8120)

- An elevation of privilege vulnerability exists in Windows when the Win32k component fails to properly handle objects in memory, aka "Win32k Elevation of Privilege Vulnerability." This affects Windows Server 2008, Windows 7, Windows Server 2008 R2. This CVE ID is unique from CVE-2018-8124, CVE-2018-8164, CVE-2018-8166.

### [CVE-2018-8140](https://securingtomorrow.mcafee.com/mcafee-labs/want-to-break-into-a-locked-windows-10-device-ask-cortana-cve-2018-8140/)

- An Elevation of Privilege vulnerability exists when Cortana retrieves data from user input services without consideration for status, aka "Cortana Elevation of Privilege Vulnerability." This affects Windows 10 Servers, Windows 10.

### [CVE-2018-8174](CVE-2018-8174.md)

- A remote code execution vulnerability exists in the way that the VBScript engine handles objects in memory, aka "Windows VBScript Engine Remote Code Execution Vulnerability." This affects Windows 7, Windows Server 2012 R2, Windows RT 8.1, Windows Server 2008, Windows Server 2012, Windows 8.1, Windows Server 2016, Windows Server 2008 R2, Windows 10, Windows 10 Servers.

### [CVE-2018-8212](https://posts.specterops.io/cve-2018-8212-device-guard-clm-bypass-using-msft-scriptresource-b6cc2318e885)

- A security feature bypass vulnerability exists in Device Guard that could allow an attacker to inject malicious code into a Windows PowerShell session, aka "Device Guard Code Integrity Policy Security Feature Bypass Vulnerability." This affects Windows Server 2016, Windows 10, Windows 10 Servers. This CVE ID is unique from CVE-2018-8201, CVE-2018-8211, CVE-2018-8215, CVE-2018-8216, CVE-2018-8217, CVE-2018-8221.

### [CVE-2018-8235](https://jakearchibald.com/2018/i-discovered-a-browser-bug/)

- A security feature bypass vulnerability exists when Microsoft Edge improperly handles requests of different origins, aka "Microsoft Edge Security Feature Bypass Vulnerability." This affects Microsoft Edge.

### [CVE-2018-8284](https://www.nccgroup.trust/uk/our-research/technical-advisory-bypassing-workflows-protection-mechanisms-remote-code-execution-on-sharepoint/)

- A remote code execution vulnerability exists when the Microsoft .NET Framework fails to validate input properly, aka ".NET Framework Remote Code Injection Vulnerability." This affects Microsoft .NET Framework 2.0, Microsoft .NET Framework 3.0, Microsoft .NET Framework 4.6.2/4.7/4.7.1/4.7.2, Microsoft .NET Framework 4.5.2, Microsoft .NET Framework 4.6, Microsoft .NET Framework 4.7/4.7.1/4.7.2, Microsoft .NET Framework 4.7.1/4.7.2, Microsoft .NET Framework 3.5, Microsoft .NET Framework 3.5.1, Microsoft .NET Framework 4.6/4.6.1/4.6.2, Microsoft .NET Framework 4.6/4.6.1/4.6.2/4.7/4.7.1/4.7.1/4.7.2, Microsoft .NET Framework 4.7.2.

### [CVE-2018-8367](https://blogs.projectmoon.pw/2018/09/15/Edge-Inline-Segment-Use-After-Free/)

- A remote code execution vulnerability exists in the way that the Chakra scripting engine handles objects in memory in Microsoft Edge, aka "Chakra Scripting Engine Memory Corruption Vulnerability." This affects Microsoft Edge, ChakraCore. This CVE ID is unique from CVE-2018-8465, CVE-2018-8466, CVE-2018-8467.

### [CVE-2018-8373](https://blog.trendmicro.com/trendlabs-security-intelligence/new-cve-2018-8373-exploit-spotted-in-the-wild/)

- A remote code execution vulnerability exists in the way that the scripting engine handles objects in memory in Internet Explorer, aka "Scripting Engine Memory Corruption Vulnerability." This affects Internet Explorer 9, Internet Explorer 11, Internet Explorer 10. This CVE ID is unique from CVE-2018-8353, CVE-2018-8355, CVE-2018-8359, CVE-2018-8371, CVE-2018-8372, CVE-2018-8385, CVE-2018-8389, CVE-2018-8390.

### [CVE-2018-8383](https://www.rafaybaloch.com/2018/09/apple-safari-microsoft-edge-browser.html)

- A spoofing vulnerability exists when Microsoft Edge does not properly parse HTTP content, aka "Microsoft Edge Spoofing Vulnerability." This affects Microsoft Edge. This CVE ID is unique from CVE-2018-8388.

### [CVE-2018-8414](https://posts.specterops.io/cve-2018-8414-a-case-study-in-responsible-disclosure-ff74c39615ba)

- A remote code execution vulnerability exists when the Windows Shell does not properly validate file paths, aka "Windows Shell Remote Code Execution Vulnerability." This affects Windows 10 Servers, Windows 10.

### [CVE-2018-8420](https://github.com/Theropord/CVE-2018-8420)

- A remote code execution vulnerability exists when the Microsoft XML Core Services MSXML parser processes user input, aka "MS XML Remote Code Execution Vulnerability." This affects Windows 7, Windows Server 2012 R2, Windows RT 8.1, Windows Server 2008, Windows Server 2012, Windows 8.1, Windows Server 2016, Windows Server 2008 R2, Windows 10, Windows 10 Servers.

### [CVE-2018-8421](https://www.nccgroup.trust/uk/our-research/technical-advisory-bypassing-microsoft-xoml-workflows-protection-mechanisms-using-deserialisation-of-untrusted-data/)

- A remote code execution vulnerability exists when Microsoft .NET Framework processes untrusted input, aka ".NET Framework Remote Code Execution Vulnerability." This affects Microsoft .NET Framework 4.6, Microsoft .NET Framework 3.5, Microsoft .NET Framework 4.7/4.7.1/4.7.2, Microsoft .NET Framework 3.0, Microsoft .NET Framework 3.5.1, Microsoft .NET Framework 4.6.2/4.7/4.7.1/4.7.2, Microsoft .NET Framework 4.5.2, Microsoft .NET Framework 4.6/4.6.1/4.6.2/4.7/4.7.1/4.7.1/4.7.2, Microsoft .NET Framework 4.7.1/4.7.2, Microsoft .NET Framework 4.7.2, Microsoft .NET Framework 2.0.

### [CVE-2018-8440](https://github.com/rapid7/metasploit-framework/pull/10643)

- An elevation of privilege vulnerability exists when Windows improperly handles calls to Advanced Local Procedure Call (ALPC), aka "Windows ALPC Elevation of Privilege Vulnerability." This affects Windows 7, Windows Server 2012 R2, Windows RT 8.1, Windows Server 2008, Windows Server 2012, Windows 8.1, Windows Server 2016, Windows Server 2008 R2, Windows 10, Windows 10 Servers.

### [CVE-2018-8495](https://leucosite.com/Microsoft-Edge-RCE/)

- A remote code execution vulnerability exists when Windows Shell improperly handles URIs, aka "Windows Shell Remote Code Execution Vulnerability." This affects Windows Server 2016, Windows 10, Windows 10 Servers.

### [CVE-2018-8532](http://hyp3rlinx.altervista.org/advisories/MICROSOFT-SQL-SERVER-MGMT-STUDIO-XMLA-FILETYPE-XML-INJECTION-CVE-2018-8532.txt)

- An information disclosure vulnerability exists in Microsoft SQL Server Management Studio (SSMS) when parsing a malicious XMLA file containing a reference to an external entity, aka "SQL Server Management Studio Information Disclosure Vulnerability." This affects SQL Server Management Studio 17.9, SQL Server Management Studio 18.0. This CVE ID is unique from CVE-2018-8527, CVE-2018-8533.

### [CVE-2018-8589](https://securelist.com/a-new-exploit-for-zero-day-vulnerability-cve-2018-8589/88845/)

- An elevation of privilege vulnerability exists when Windows improperly handles calls to Win32k.sys, aka "Windows Win32k Elevation of Privilege Vulnerability." This affects Windows Server 2008, Windows 7, Windows Server 2008 R2.

### [CVE-2018-8611](https://securelist.com/zero-day-in-windows-kernel-transaction-manager-cve-2018-8611/89253/)

- An elevation of privilege vulnerability exists when the Windows kernel fails to properly handle objects in memory, aka "Windows Kernel Elevation of Privilege Vulnerability." This affects Windows 7, Windows Server 2012 R2, Windows RT 8.1, Windows Server 2008, Windows Server 2019, Windows Server 2012, Windows 8.1, Windows Server 2016, Windows Server 2008 R2, Windows 10, Windows 10 Servers.

### [CVE-2018-8639](https://github.com/ze0r/CVE-2018-8639-exp/)

- An elevation of privilege vulnerability exists in Windows when the Win32k component fails to properly handle objects in memory, aka "Win32k Elevation of Privilege Vulnerability." This affects Windows 7, Windows Server 2012 R2, Windows RT 8.1, Windows Server 2008, Windows Server 2019, Windows Server 2012, Windows 8.1, Windows Server 2016, Windows Server 2008 R2, Windows 10, Windows 10 Servers. This CVE ID is unique from CVE-2018-8641.

### [CVE-2018-8719](https://www.exploit-db.com/exploits/44371/)

- An issue was discovered in the WP Security Audit Log plugin 3.1.1 for WordPress. Access to wp-content/uploads/wp-security-audit-log/* files is not restricted. For example, these files are indexed by Google and allows for attackers to possibly find sensitive information.

### [CVE-2018-8733](http://blog.redactedsec.net/exploits/2018/04/26/nagios.html)

- Authentication bypass vulnerability in the core config manager in Nagios XI 5.2.x through 5.4.x before 5.4.13 allows an unauthenticated attacker to make configuration changes and leverage an authenticated SQL injection vulnerability.

### [CVE-2018-8734](http://blog.redactedsec.net/exploits/2018/04/26/nagios.html)

- SQL injection vulnerability in the core config manager in Nagios XI 5.2.x through 5.4.x before 5.4.13 allows an attacker to execute arbitrary SQL commands via the selInfoKey1 parameter.

### [CVE-2018-8735](http://blog.redactedsec.net/exploits/2018/04/26/nagios.html)

- Remote command execution (RCE) vulnerability in Nagios XI 5.2.x through 5.4.x before 5.4.13 allows an attacker to execute arbitrary commands on the target system, aka OS command injection.

### [CVE-2018-8736](http://blog.redactedsec.net/exploits/2018/04/26/nagios.html)

- A privilege escalation vulnerability in Nagios XI 5.2.x through 5.4.x before 5.4.13 allows an attacker to leverage an RCE vulnerability escalating to root.

### [CVE-2018-8778](https://blog.sqreen.io/buffer-under-read-ruby/)

- In Ruby before 2.2.10, 2.3.x before 2.3.7, 2.4.x before 2.4.4, 2.5.x before 2.5.1, and 2.6.0-preview1, an attacker controlling the unpacking format (similar to format string vulnerabilities) can trigger a buffer under-read in the String#unpack method, resulting in a massive and controlled information disclosure.

### [CVE-2018-8819](https://www.coalfire.com/The-Coalfire-Blog/June-2018/How-I-Found-CVE-2018-8819-Out-of-Band-(OOB)-XXE)

- An XXE issue was discovered in Automated Logic Corporation (ALC) WebCTRL Versions 6.0, 6.1 and 6.5. An unauthenticated attacker could enter malicious input to WebCTRL and a weakly configured XML parser will allow the application to disclose full file contents from the underlying web server OS via the "X-Wap-Profile" HTTP header.

### [CVE-2018-8897](https://www.triplefault.io/2018/05/spurious-db-exceptions-with-pop-ss.html)

- A statement in the System Programming Guide of the Intel 64 and IA-32 Architectures Software Developer's Manual (SDM) was mishandled in the development of some or all operating-system kernels, resulting in unexpected behavior for #DB exceptions that are deferred by MOV SS or POP SS, as demonstrated by (for example) privilege escalation in Windows, macOS, some Xen configurations, or FreeBSD, or a Linux kernel crash. The MOV to SS and POP SS instructions inhibit interrupts (including NMIs), data breakpoints, and single step trap exceptions until the instruction boundary following the next instruction (SDM Vol. 3A; section 6.8.3). (The inhibited data breakpoints are those on memory accessed by the MOV to SS or POP to SS instruction itself.) Note that debug exceptions are not inhibited by the interrupt enable (EFLAGS.IF) system flag (SDM Vol. 3A; section 2.3). If the instruction following the MOV to SS or POP to SS instruction is an instruction like SYSCALL, SYSENTER, INT 3, etc. that transfers control to the operating system at CPL < 3, the debug exception is delivered after the transfer to CPL < 3 is complete. OS kernels may not expect this order of events and may therefore experience unexpected behavior when it occurs.

### [CVE-2018-8955](https://labs.nettitude.com/blog/cve-2018-8955-bitdefender-gravityzone-arbitrary-code-execution/)

- The installer for BitDefender GravityZone relies on an encoded string in a filename to determine the URL for installation metadata, which allows remote attackers to execute arbitrary code by changing the filename while leaving the file's digital signature unchanged.

### [CVE-2018-9206](http://www.vapidlabs.com/advisory.php?v=204)

- Unauthenticated arbitrary file upload vulnerability in Blueimp jQuery-File-Upload <= v9.22.0.

### [CVE-2018-9341](https://github.com/V-E-O/PoC/tree/master/CVE-2018-9341)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2018-9359](https://blog.quarkslab.com/a-story-about-three-bluetooth-vulnerabilities-in-android.html)

- In process_l2cap_cmd of l2c_main.cc, there is a possible out of bounds read due to a missing bounds check. This could lead to remote information disclosure with no additional execution privileges needed. User interaction is not needed for exploitation. Product: Android Versions: Android-6.0 Android-6.0.1 Android-7.0 Android-7.1.1 Android-7.1.2 Android-8.0 Android-8.1 Android ID: A-74196706.

### [CVE-2018-9360](https://blog.quarkslab.com/a-story-about-three-bluetooth-vulnerabilities-in-android.html)

- In process_l2cap_cmd of l2c_main.cc, there is a possible out of bounds read due to a missing bounds check. This could lead to remote information disclosure with no additional execution privileges needed. User interaction is not needed for exploitation. Product: Android Versions: Android-6.0 Android-6.0.1 Android-7.0 Android-7.1.1 Android-7.1.2 Android-8.0 Android-8.1 Android ID: A-74201143.

### [CVE-2018-9361](https://blog.quarkslab.com/a-story-about-three-bluetooth-vulnerabilities-in-android.html)

- In process_l2cap_cmd of l2c_main.cc, there is a possible out of bounds read due to a missing bounds check. This could lead to remote information disclosure with no additional execution privileges needed. User interaction is not needed for exploitation. Product: Android Versions: Android-6.0 Android-6.0.1 Android-7.0 Android-7.1.1 Android-7.1.2 Android-8.0 Android-8.1 Android ID: A-74202041.

### [CVE-2018-9411](https://blog.zimperium.com/cve-2018-9411-new-critical-vulnerability-multiple-high-privileged-android-services/)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2018-9445](https://0day.city/cve-2018-9445.html)

- In readMetadata of Utils.cpp, there is a possible path traversal bug due to a confused deputy. This could lead to local escalation of privilege when mounting a USB device with no additional execution privileges needed. User interaction is not needed for exploitation. Product: Android Versions: Android-6.0 Android-6.0.1 Android-7.0 Android-7.1.1 Android-7.1.2 Android-8.0 Android-8.1 Android ID: A-80436257.

### [CVE-2018-9995](https://github.com/ezelf/CVE-2018-9995_dvr_credentials)

- TBK DVR4104 and DVR4216 devices allow remote attackers to bypass authentication via a "Cookie: uid=admin" header, as demonstrated by a device.rsp?opt=user&cmd=list request that provides credentials within JSON data in a response.

### [CVE-2018-10115](https://landave.io/2018/05/7-zip-from-uninitialized-memory-to-remote-code-execution/)

- Incorrect initialization logic of RAR decoder objects in 7-Zip 18.03 and before can lead to usage of uninitialized memory, allowing remote attackers to cause a denial of service (segmentation fault) or execute arbitrary code via a crafted RAR archive.

### [CVE-2018-10172](https://sourceforge.net/p/sevenzip/discussion/45797/thread/e730c709/?limit=25&page=1#b240)

- 7-Zip through 18.01 on Windows implements the "Large memory pages" option by calling the LsaAddAccountRights function to add the SeLockMemoryPrivilege privilege to the user's account, which makes it easier for attackers to bypass intended access restrictions by using this privilege in the context of a sandboxed process.

### [CVE-2018-10468](https://medium.com/coinmonks/uselessethereumtoken-uet-erc20-token-allows-attackers-to-steal-all-victims-balances-543d42ac808e)

- The transferFrom function of a smart contract implementation for Useless Ethereum Token (UET), an Ethereum ERC20 token, allows attackers to steal assets (e.g., transfer all victims' balances into their account) because certain computations involving _value are incorrect, as exploited in the wild starting in December 2017, aka the "transferFlaw" issue.

### [CVE-2018-10561](https://www.vpnmentor.com/blog/critical-vulnerability-gpon-router/)

- An issue was discovered on Dasan GPON home routers. It is possible to bypass authentication simply by appending "?images" to any URL of the device that requires authentication, as demonstrated by the /menu.html?images/ or /GponForm/diag_FORM?images/ URI. One can then manage the device.

### [CVE-2018-10562](https://www.vpnmentor.com/blog/critical-vulnerability-gpon-router/)

- An issue was discovered on Dasan GPON home routers. Command Injection can occur via the dest_host parameter in a diag_action=ping request to a GponForm/diag_Form URI. Because the router saves ping results in /tmp and transmits them to the user when the user revisits /diag.html, it's quite simple to execute commands and retrieve their output.

### [CVE-2018-10641](https://advancedpersistentsecurity.net/cve-2018-10641/)

- D-Link DIR-601 A1 1.02NA devices do not require the old password for a password change, which occurs in cleartext.

### [CVE-2018-10666](https://medium.com/@jonghyk.song/aurora-idex-membership-idxm-erc20-token-allows-attackers-to-acquire-contract-ownership-1ff426cee7c6)

- The Owned smart contract implementation for Aurora IDEX Membership (IDXM), an Ethereum ERC20 token, allows attackers to acquire contract ownership because the setOwner function is declared as public. A new owner can subsequently modify variables.

### [CVE-2018-10676](http://misteralfa-hack.blogspot.tw/2018/05/0day-dvr-multivendor.html)

- CeNova, Night OWL, Novo, Pulnix, QSee, Securus, and TBK Vision DVR devices allow remote attackers to download a file and obtain sensitive credential information via a direct request for the download.rsp URI.

### [CVE-2018-10895](https://github.com/qutebrowser/qutebrowser/issues/4060)

- qutebrowser before version 1.4.1 is vulnerable to a cross-site request forgery flaw that allows websites to access 'qute://*' URLs. A malicious website could exploit this to load a 'qute://settings/set' URL, which then sets 'editor.command' to a bash script, resulting in arbitrary code execution.

### [CVE-2018-10933](CVE-2018-10933.md)

- A vulnerability was found in libssh's server-side state machine before versions 0.7.6 and 0.8.4. A malicious client could create channels without first performing authentication, resulting in unauthorized access.

### [CVE-2018-10944](https://medium.com/coinmonks/attackers-can-steal-all-of-ether-in-roc-rasputin-online-coin-token-smart-contract-ae928b4a935a)

- The request_dividend function of a smart contract implementation for ROC (aka Rasputin Online Coin), an Ethereum ERC20 token, allows attackers to steal all of the contract's Ether.

### [CVE-2018-10956](https://labs.nettitude.com/blog/cve-2018-10956-unauthenticated-privileged-directory-traversal-in-ipconfigure-orchid-core-vms/)

- IPConfigure Orchid Core VMS 2.0.5 allows Directory Traversal.

### [CVE-2018-10994](http://seclists.org/fulldisclosure/2018/May/39)

- js/views/message_view.js in Open Whisper Signal (aka Signal-Desktop) before 1.10.1 allows XSS via a URL.

### [CVE-2018-11101](http://seclists.org/fulldisclosure/2018/May/46)

- Open Whisper Signal (aka Signal-Desktop) through 1.10.1 allows XSS via a resource location specified in an attribute of a SCRIPT, IFRAME, or IMG element, leading to JavaScript execution after a reply, a different vulnerability than CVE-2018-10994. The attacker needs to send HTML code directly as a message, and then reply to that message to trigger this vulnerability. The Signal-Desktop software fails to sanitize specific HTML elements that can be used to inject HTML code into remote chat windows when replying to an HTML message. Specifically the IMG and IFRAME elements can be used to include remote or local resources. For example, the use of an IFRAME element enables full code execution, allowing an attacker to download/upload files, information, etc. The SCRIPT element was also found to be injectable. On the Windows operating system, the CSP fails to prevent remote inclusion of resources via the SMB protocol. In this case, remote execution of JavaScript can be achieved by referencing the script on an SMB share within an IFRAME element, for example: <IFRAME src=\\DESKTOP-XXXXX\Temp\test.html> and then replying to it. The included JavaScript code is then executed automatically, without any interaction needed from the user. The vulnerability can be triggered in the Signal-Desktop client by sending a specially crafted message and then replying to it with any text or content in the reply (it doesn't matter).

### [CVE-2018-11235](https://github.com/Rogdham/CVE-2018-11235)

- In Git before 2.13.7, 2.14.x before 2.14.4, 2.15.x before 2.15.2, 2.16.x before 2.16.4, and 2.17.x before 2.17.1, remote code execution can occur. With a crafted .gitmodules file, a malicious project can execute an arbitrary script on a machine that runs "git clone --recurse-submodules" because submodule "names" are obtained from this file, and then appended to $GIT_DIR/modules, leading to directory traversal with "../" in a name. Finally, post-checkout hooks from a submodule are executed, bypassing the intended design in which hooks are not obtained from a remote server.

### [CVE-2018-11411](https://medium.com/coinmonks/dimoncoin-fud-erc20-token-allows-attackers-to-steal-all-victims-balances-cve-2018-11411-ba9a320604f9)

- The transferFrom function of a smart contract implementation for DimonCoin (FUD), an Ethereum ERC20 token, allows attackers to steal assets (e.g., transfer all victims' balances into their account) because certain computations involving _value are incorrect.

### [CVE-2018-11689](http://seclists.org/fulldisclosure/2018/Jun/40)

- Smart Viewer in Samsung Web Viewer for Samsung DVR is vulnerable to cross-site scripting, caused by improper validation of user-supplied input. A remote attacker could exploit this vulnerability via a crafted URL to execute script in a victim's Web browser within the security context of the hosting Web site, once the URL is clicked. An attacker could use this vulnerability to steal the victim's cookie-based authentication credentials.

### [CVE-2018-11759](https://github.com/Jul10l1r4/Identificador-CVE-2018-11759)

- The Apache Web Server (httpd) specific code that normalised the requested path before matching it to the URI-worker map in Apache Tomcat JK (mod_jk) Connector 1.2.0 to 1.2.44 did not handle some edge cases correctly. If only a sub-set of the URLs supported by Tomcat were exposed via httpd, then it was possible for a specially constructed request to expose application functionality through the reverse proxy that was not intended for clients accessing the application via the reverse proxy. It was also possible in some configurations for a specially constructed request to bypass the access controls configured in httpd. While there is some overlap between this issue and CVE-2018-1323, they are not identical.

### [CVE-2018-11776](CVE-2018-11776.md)

- Apache Struts versions 2.3 to 2.3.34 and 2.5 to 2.5.16 suffer from possible Remote Code Execution when using results with no namespace and in same time, its upper action(s) have no or wildcard namespace. Same possibility when using url tag which doesn't have value and action set and in same time, its upper action(s) have no or wildcard namespace.

### [CVE-2018-11784](http://www.zhutougg.com/2018/10/08/cve-2018-11784-tomcat-urltiao-zhuan-lou-dong/)

- When the default servlet in Apache Tomcat versions 9.0.0.M1 to 9.0.11, 8.5.0 to 8.5.33 and 7.0.23 to 7.0.90 returned a redirect to a directory (e.g. redirecting to '/foo/' when the user requested '/foo') a specially crafted URL could be used to cause the redirect to be generated to any URI of the attackers choice.

### [CVE-2018-11788](https://github.com/brianwrf/CVE-2018-11788/)

- Apache Karaf provides a features deployer, which allows users to "hot deploy" a features XML by dropping the file directly in the deploy folder. The features XML is parsed by XMLInputFactory class. Apache Karaf XMLInputFactory class doesn't contain any mitigation codes against XXE. This is a potential security risk as an user can inject external XML entities in Apache Karaf version prior to 4.1.7 or 4.2.2. It has been fixed in Apache Karaf 4.1.7 and 4.2.2 releases.

### [CVE-2018-11882](https://ti.360.net/blog/articles/cve-2017-11882-exploit-kit-sample/)

- Incorrect bound check can lead to potential buffer overwrite in WLAN controller in Snapdragon Mobile in version SD 835, SD 845, SD 850, SDA660.

### [CVE-2018-12015](http://knqyf263.hatenablog.com/entry/2018/06/27/181037)

- In Perl through 5.26.2, the Archive::Tar module allows remote attackers to bypass a directory-traversal protection mechanism, and overwrite arbitrary files, via an archive file containing a symlink and a regular file with the same name.

### [CVE-2018-12020](https://neopg.io/blog/gpg-signature-spoof)

- mainproc.c in GnuPG before 2.2.8 mishandles the original filename during decryption and verification actions, which allows remote attackers to spoof the output that GnuPG sends on file descriptor 2 to other programs that use the "--status-fd 2" option. For example, the OpenPGP data might represent an original filename that contains line feed characters in conjunction with GOODSIG or VALIDSIG status codes.

### [CVE-2018-12034](https://bnbdr.github.io/posts/swisscheese/)

- In YARA 3.7.1 and prior, parsing a specially crafted compiled rule file can cause an out of bounds read vulnerability in yr_execute_code in libyara/exec.c.

### [CVE-2018-12035](https://bnbdr.github.io/posts/swisscheese/)

- In YARA 3.7.1 and prior, parsing a specially crafted compiled rule file can cause an out of bounds write vulnerability in yr_execute_code in libyara/exec.c.

### [CVE-2018-12056](https://medium.com/coinmonks/to-be-a-winner-of-ethereum-gambling-game-all-for-one-by-breaking-prng-1ab011163d40)

- The maxRandom function of a smart contract implementation for All For One, an Ethereum gambling game, generates a random value with publicly readable variables because the _seed value can be retrieved with a getStorageAt call. Therefore, it allows attackers to always win and get rewards.

### [CVE-2018-12386](https://github.com/niklasb/sploits/blob/master/firefox/rce-register-misalloc.js)

- A vulnerability in register allocation in JavaScript can lead to type confusion, allowing for an arbitrary read and write. This leads to remote code execution inside the sandboxed content process when triggered. This vulnerability affects Firefox ESR < 60.2.2 and Firefox < 62.0.3.

### [CVE-2018-12387](https://github.com/niklasb/sploits/blob/master/firefox/stack-off-by-8.js)

- A vulnerability where the JavaScript JIT compiler inlines Array.prototype.push with multiple arguments that results in the stack pointer being off by 8 bytes after a bailout. This leaks a memory address to the calling function which can be used as part of an exploit inside the sandboxed content process. This vulnerability affects Firefox ESR < 60.2.2 and Firefox < 62.0.3.

### [CVE-2018-12454](https://medium.com/coinmonks/attack-on-pseudo-random-number-generator-prng-used-in-1000-guess-an-ethereum-lottery-game-7b76655f953d)

- The _addguess function of a simplelottery smart contract implementation for 1000 Guess, an Ethereum gambling game, generates a random value with publicly readable variables such as the current block information and a private variable (which can be read with a getStorageAt call). Therefore, it allows attackers to always win and get rewards.

### [CVE-2018-12885](https://medium.com/coinmonks/get-legendary-items-by-breaking-pnrg-of-mycyptochamp-an-ethereum-online-game-cve-2018-12855-6e6beb41b8df)

- The randMod() function of the smart contract implementation for MyCryptoChamp, an Ethereum game, generates a random value with publicly readable variables such as the current block information and a private variable, (which can be read with a getStorageAt call). Therefore, attackers can get powerful champs/items and get rewards.

### [CVE-2018-13149](https://medium.com/@peckshield/the-traderifle-vulnerability-identified-in-huobi-otc-service-cve-2018-13149-4882c8ccf94e)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2018-13452](https://cxsecurity.com/issue/WLB-2018070249)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2018-14327](https://osandamalith.com/2018/09/17/ee-4gee-mini-local-privilege-escalation-vulnerability-cve-2018-14327/)

- The installer for the Alcatel OSPREY3_MINI Modem component on EE EE40VB 4G mobile broadband modems with firmware before EE40_00_02.00_45 sets weak permissions (Everyone:Full Control) for the "Web Connecton\EE40" and "Web Connecton\EE40\BackgroundService" directories, which allows local users to gain privileges, as demonstrated by inserting a Trojan horse ServiceManager.exe file into the "Web Connecton\EE40\BackgroundService" directory.

### [CVE-2018-14634](https://www.qualys.com/2018/09/25/cve-2018-14634/mutagen-astronomy-integer-overflow-linux-create_elf_tables-cve-2018-14634.txt)

- An integer overflow flaw was found in the Linux kernel's create_elf_tables() function. An unprivileged local user with access to SUID (or otherwise privileged) binary could use this flaw to escalate their privileges on the system. Kernel versions 2.6.x, 3.10.x and 4.14.x are believed to be vulnerable.

### [CVE-2018-14665](https://twitter.com/hackerfantastic/status/1055517801224396800)

- A flaw was found in xorg-x11-server before 1.20.3. An incorrect permission check for -modulepath and -logfile options when starting Xorg. X server allows unprivileged users with the ability to log in to the system via physical console to escalate their privileges and run arbitrary code under root privileges.

### [CVE-2018-14667](https://www.slideshare.net/joaomatosff/a-little-bit-about-code-injection-in-webapplication-frameworks-cve201814667-h2hc-2018)

- The RichFaces Framework 3.X through 3.3.4 is vulnerable to Expression Language (EL) injection via the UserResource resource. A remote, unauthenticated attacker could exploit this to execute arbitrary code using a chain of java serialized objects via org.ajax4jsf.resource.UserResource$UriData.

### [CVE-2018-14686](https://github.com/TonyKentClark/MyCodeAudit/blob/master/xycms%20%20v1.7)

- system/edit_book.php in XYCMS 1.7 has stored XSS via a crafted add_do.php request, related to add_book.php.

### [CVE-2018-14715](https://medium.com/coinmonks/attack-on-pseudo-random-number-generator-prng-used-in-cryptogs-an-ethereum-cve-2018-14715-f63a51ac2eb9)

- The endCoinFlip function and throwSlammer function of the smart contract implementations for Cryptogs, an Ethereum game, generate random numbers with an old block's hash. Therefore, attackers can predict the random number and always win the game.

### [CVE-2018-14847](https://n0p.me/winbox-bug-dissection/)

- Winbox for MikroTik RouterOS through 6.42 allows remote attackers to bypass authentication and read arbitrary files by modifying a request to change one byte related to a Session ID.

### [CVE-2018-15473](https://github.com/Rhynorater/CVE-2018-15473-Exploit)

- OpenSSH through 7.7 is prone to a user enumeration vulnerability due to not delaying bailout for an invalid authenticating user until after the packet containing the request has been fully parsed, related to auth2-gss.c, auth2-hostbased.c, and auth2-pubkey.c.

### [CVE-2018-15685](https://github.com/matt-/CVE-2018-15685)

- GitHub Electron 1.7.15, 1.8.7, 2.0.7, and 3.0.0-beta.6, in certain scenarios involving IFRAME elements and "nativeWindowOpen: true" or "sandbox: true" options, is affected by a WebPreferences vulnerability that can be leveraged to perform remote code execution.

### [CVE-2018-15705](https://www.tenable.com/security/research/tra-2018-35)

- WADashboard API in Advantech WebAccess 8.3.1 and 8.3.2 allows remote authenticated attackers to write or overwrite any file on the filesystem due to a directory traversal vulnerability in the writeFile API. An attacker can use this vulnerability to remotely execute arbitrary code.

### [CVE-2018-15706](https://www.tenable.com/security/research/tra-2018-35)

- WADashboard API in Advantech WebAccess 8.3.1 and 8.3.2 allows remote authenticated attackers to read any file on the filesystem due to a directory traversal vulnerability in the readFile API.

### [CVE-2018-15707](https://www.tenable.com/security/research/tra-2018-35)

- Advantech WebAccess 8.3.1 and 8.3.2 are vulnerable to cross-site scripting in the Bwmainleft.asp page. An attacker could leverage this vulnerability to disclose credentials amongst other things.

### [CVE-2018-15715](https://medium.com/tenable-techblog/remotely-exploiting-zoom-meetings-5a811342ba1d)

- Zoom clients on Windows (before version 4.1.34814.1119), Mac OS (before version 4.1.34801.1116), and Linux (2.4.129780.0915 and below) are vulnerable to unauthorized message processing. A remote unauthenticated attacker can spoof UDP messages from a meeting attendee or Zoom server in order to invoke functionality in the target client. This allows the attacker to remove attendees from meetings, spoof messages from users, or hijack shared screens.

### [CVE-2018-15869](https://github.com/hashicorp/packer/issues/6584)

- An Amazon Web Services (AWS) developer who does not specify the --owners flag when describing images via AWS CLI, and therefore not properly validating source software per AWS recommended security best practices, may unintentionally load an undesired and potentially malicious Amazon Machine Image (AMI) from the uncurated public community AMI catalog.

### [CVE-2018-15961](https://github.com/vah13/CVE-2018-15961)

- Adobe ColdFusion versions July 12 release (2018.0.0.310739), Update 6 and earlier, and Update 14 and earlier have an unrestricted file upload vulnerability. Successful exploitation could lead to arbitrary code execution.

### [CVE-2018-15982](https://github.com/smgorelik/Windows-RCE-exploits/blob/master/Documents/Office%2BFlash/CVE-2018-15982_%23PoC%23.zip)

- Flash Player versions 31.0.0.153 and earlier, and 31.0.0.108 and earlier have a use after free vulnerability. Successful exploitation could lead to arbitrary code execution.

### [CVE-2018-16323](https://medium.com/@ilja.bv/yet-another-memory-leak-in-imagemagick-or-how-to-exploit-cve-2018-16323-a60f048a1e12)

- ReadXBMImage in coders/xbm.c in ImageMagick before 7.0.8-9 leaves data uninitialized when processing an XBM file that has a negative pixel value. If the affected code is used as a library loaded into a process that includes sensitive information, that information sometimes can be leaked via the image data.

### [CVE-2018-16384](https://github.com/SpiderLabs/owasp-modsecurity-crs/issues/1167)

- A SQL injection bypass (aka PL1 bypass) exists in OWASP ModSecurity Core Rule Set (owasp-modsecurity-crs) through v3.1.0-rc3 via {\`a\`b} where a is a special function name (such as "if") and b is the SQL statement to be executed.

### [CVE-2018-16509](https://medium.com/@NumbShiva/imagemagic-rce-f364a9f50a14)

- An issue was discovered in Artifex Ghostscript before 9.24. Incorrect "restoration of privilege" checking during handling of /invalidaccess exceptions could be used by attackers able to supply crafted PostScript to execute code using the "pipe" instruction.

### [CVE-2018-16946](https://github.com/EgeBalci/LG-Smart-IP-Device-Backup-Download)

- LG LNB*, LND*, LNU*, and LNV* smart network camera devices have broken access control. Attackers are able to download /updownload/t.report (aka Log & Report) files and download backup files (via download.php) without authenticating. These backup files contain user credentials and configuration information for the camera device. An attacker is able to discover the backup filename via reading the system logs or report data, or just by brute-forcing the backup filename pattern. It may be possible to authenticate to the admin account with the admin password.

### [CVE-2018-17082](https://bugs.php.net/bug.php?id=76582)

- The Apache2 component in PHP before 5.6.38, 7.0.x before 7.0.32, 7.1.x before 7.1.22, and 7.2.x before 7.2.10 allows XSS via the body of a "Transfer-Encoding: chunked" request, because the bucket brigade is mishandled in the php_handler function in sapi/apache2handler/sapi_apache2.c.

### [CVE-2018-17144](https://bitcoincore.org/en/2018/09/20/notice/)

- Bitcoin Core 0.14.x before 0.14.3, 0.15.x before 0.15.2, and 0.16.x before 0.16.3 and Bitcoin Knots 0.14.x through 0.16.x before 0.16.3 allow a remote denial of service (application crash) exploitable by miners via duplicate input. An attacker can make bitcoind or Bitcoin-Qt crash.

### [CVE-2018-17182](https://www.exploit-db.com/exploits/45497/)

- An issue was discovered in the Linux kernel through 4.18.8. The vmacache_flush_all function in mm/vmacache.c mishandles sequence number overflows. An attacker can trigger a use-after-free (and possibly gain privileges) via certain thread creation, map, unmap, invalidation, and dereference operations.

### [CVE-2018-17780](https://www.inputzero.io/2018/09/bug-bounty-telegram-cve-2018-17780.html)

- Telegram Desktop (aka tdesktop) 1.3.14, and Telegram 3.3.0.0 WP8.1 on Windows, leaks end-user public and private IP addresses during a call because of an unsafe default behavior in which P2P connections are accepted from clients outside of the My Contacts list.

### [CVE-2018-19276](https://github.com/mpgn/CVE-2018-19276/)

- OpenMRS before 2.24.0 is affected by an Insecure Object Deserialization vulnerability that allows an unauthenticated user to execute arbitrary commands on the targeted system via crafted XML data in a request body.

### [CVE-2018-19788](https://gitlab.freedesktop.org/polkit/polkit/issues/74)

- A flaw was found in PolicyKit (aka polkit) 0.115 that allows a user with a uid greater than INT_MAX to successfully execute any systemctl command.

### [CVE-2018-20250](https://isc.sans.edu/forums/diary/rar+Files+and+ACE+Exploit+CVE201820250/24864/)

- In WinRAR versions prior to and including 5.61, There is path traversal vulnerability when crafting the filename field of the ACE format (in UNACEV2.dll). When the filename field is manipulated with specific patterns, the destination (extraction) folder is ignored, thus treating the filename as an absolute path.

### [CVE-2018-20714](https://blog.ripstech.com/2018/wordpress-design-flaw-leads-to-woocommerce-rce/)

- The logging system of the Automattic WooCommerce plugin before 3.4.6 for WordPress is vulnerable to a File Deletion vulnerability. This allows deletion of woocommerce.php, which leads to certain privilege checks not being in place, and therefore a shop manager can escalate privileges to admin.

### [CVE-2018-1000006](https://xianzhi.aliyun.com/forum/topic/1994?from=timeline&isappinstalled=0)

- GitHub Electron versions 1.8.2-beta.3 and earlier, 1.7.10 and earlier, 1.6.15 and earlier has a vulnerability in the protocol handler, specifically Electron apps running on Windows 10, 7 or 2008 that register custom protocol handlers can be tricked in arbitrary command execution if the user clicks on a specially crafted URL. This has been fixed in versions 1.8.2-beta.4, 1.7.11, and 1.6.16.

### [CVE-2018-1000094](https://github.com/strukt93/exploits/blob/master/CVE-2018-1000094.py)

- CMS Made Simple version 2.2.5 contains a Remote Code Execution vulnerability in File Manager that can result in Allows an authenticated admin that has access to the file manager to execute code on the server. This attack appear to be exploitable via File upload -> copy to any extension.

### [CVE-2018-1000129](https://blog.gdssecurity.com/labs/2018/4/18/jolokia-vulnerabilities-rce-xss.html)

- An XSS vulnerability exists in the Jolokia agent version 1.3.7 in the HTTP servlet that allows an attacker to execute malicious javascript in the victim's browser.

### [CVE-2018-1000130](https://blog.gdssecurity.com/labs/2018/4/18/jolokia-vulnerabilities-rce-xss.html)

- A JNDI Injection vulnerability exists in Jolokia agent version 1.3.7 in the proxy mode that allows a remote attacker to run arbitrary Java code on the server.

### [CVE-2018-1000136](https://www.trustwave.com/Resources/SpiderLabs-Blog/CVE-2018-1000136---Electron-nodeIntegration-Bypass/)

- Electron version 1.7 up to 1.7.12; 1.8 up to 1.8.3 and 2.0.0 up to 2.0.0-beta.3 contains an improper handling of values vulnerability in Webviews that can result in remote code execution. This attack appear to be exploitable via an app which allows execution of 3rd party code AND disallows node integration AND has not specified if webview is enabled/disabled. This vulnerability appears to have been fixed in 1.7.13, 1.8.4, 2.0.0-beta.4.

### [CVE-2018-1002105](https://github.com/evict/poc_CVE-2018-1002105)

- In all Kubernetes versions prior to v1.10.11, v1.11.5, and v1.12.3, incorrect handling of error responses to proxied upgrade requests in the kube-apiserver allowed specially crafted requests to establish a connection through the Kubernetes API server to backend servers, then send arbitrary requests over the same connection directly to the backend, authenticated with the Kubernetes API server's TLS credentials used to establish the backend connection.

### [CVE-2019-0193](https://github.com/jas502n/CVE-2019-0193)

- In Apache Solr, the DataImportHandler, an optional but popular module to pull in data from databases and other sources, has a feature in which the whole DIH configuration can come from a request's "dataConfig" parameter. The debug mode of the DIH admin screen uses this to allow convenient debugging / development of a DIH config. Since a DIH config can contain scripts, this parameter is a security risk. Starting with version 8.2.0 of Solr, use of this parameter requires setting the Java System property "enable.dih.dataConfigParam" to true.

### [CVE-2019-0211](https://cfreal.github.io/carpe-diem-cve-2019-0211-apache-local-root.html)

- In Apache HTTP Server 2.4 releases 2.4.17 to 2.4.38, with MPM event, worker or prefork, code executing in less-privileged child processes or threads (including scripts executed by an in-process scripting interpreter) could execute arbitrary code with the privileges of the parent process (usually root) by manipulating the scoreboard. Non-Unix systems are not affected.

### [CVE-2019-0232](https://blog.trendmicro.com/trendlabs-security-intelligence/uncovering-cve-2019-0232-a-remote-code-execution-vulnerability-in-apache-tomcat/)

- When running on Windows with enableCmdLineArguments enabled, the CGI Servlet in Apache Tomcat 9.0.0.M1 to 9.0.17, 8.5.0 to 8.5.39 and 7.0.0 to 7.0.93 is vulnerable to Remote Code Execution due to a bug in the way the JRE passes command line arguments to Windows. The CGI Servlet is disabled by default. The CGI option enableCmdLineArguments is disable by default in Tomcat 9.0.x (and will be disabled by default in all versions in response to this vulnerability). For a detailed explanation of the JRE behaviour, see Markus Wulftange's blog (https://codewhitesec.blogspot.com/2016/02/java-and-command-line-injections-in-windows.html) and this archived MSDN blog (https://web.archive.org/web/20161228144344/https://blogs.msdn.microsoft.com/twistylittlepassagesallalike/2011/04/23/everyone-quotes-command-line-arguments-the-wrong-way/).

### [CVE-2019-0539](https://perception-point.io/resources/research/cve-2019-0539-exploitation/)

- A remote code execution vulnerability exists in the way that the Chakra scripting engine handles objects in memory in Microsoft Edge, aka "Chakra Scripting Engine Memory Corruption Vulnerability." This affects Microsoft Edge, ChakraCore. This CVE ID is unique from CVE-2019-0567, CVE-2019-0568.

### [CVE-2019-0604](https://github.com/linhlhq/CVE-2019-0604)

- A remote code execution vulnerability exists in Microsoft SharePoint when the software fails to check the source markup of an application package, aka 'Microsoft SharePoint Remote Code Execution Vulnerability'. This CVE ID is unique from CVE-2019-0594.

### [CVE-2019-0708](https://github.com/zerosum0x0/CVE-2019-0708)

- A remote code execution vulnerability exists in Remote Desktop Services formerly known as Terminal Services when an unauthenticated attacker connects to the target system using RDP and sends specially crafted requests, aka 'Remote Desktop Services Remote Code Execution Vulnerability'.

### [CVE-2019-0797](https://securelist.com/cve-2019-0797-zero-day-vulnerability/89885/)

- An elevation of privilege vulnerability exists in Windows when the Win32k component fails to properly handle objects in memory, aka 'Win32k Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2019-0808.

### [CVE-2019-0808](http://blogs.360.cn/post/RootCause_CVE-2019-0808_EN.html)

- An elevation of privilege vulnerability exists in Windows when the Win32k component fails to properly handle objects in memory, aka 'Win32k Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2019-0797.

### [CVE-2019-0841](https://rastamouse.me/2019/04/weaponizing-cve-2019-0841-with-laps/)

- An elevation of privilege vulnerability exists when Windows AppX Deployment Service (AppXSVC) improperly handles hard links, aka 'Windows Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2019-0730, CVE-2019-0731, CVE-2019-0796, CVE-2019-0805, CVE-2019-0836.

### [CVE-2019-1306](https://www.thezdi.com/blog/2019/10/23/cve-2019-1306-are-you-my-index)

- A remote code execution vulnerability exists when Azure DevOps Server (ADO) and Team Foundation Server (TFS) fail to validate input properly, aka 'Azure DevOps and Team Foundation Server Remote Code Execution Vulnerability'.

### [CVE-2019-1388](https://github.com/jas502n/CVE-2019-1388)

- An elevation of privilege vulnerability exists in the Windows Certificate Dialog when it does not properly enforce user privileges, aka 'Windows Certificate Dialog Elevation of Privilege Vulnerability'.

### [CVE-2019-1414](https://iwantmore.pizza/posts/cve-2019-1414.html)

- An elevation of privilege vulnerability exists in Visual Studio Code when it exposes a debug listener to users of a local computer, aka 'Visual Studio Code Elevation of Privilege Vulnerability'.

### [CVE-2019-1458](https://github.com/piotrflorczyk/cve-2019-1458_POC)

- An elevation of privilege vulnerability exists in Windows when the Win32k component fails to properly handle objects in memory, aka 'Win32k Elevation of Privilege Vulnerability'.

### [CVE-2019-2588](https://www.exploit-db.com/exploits/46728)

- Vulnerability in the BI Publisher (formerly XML Publisher) component of Oracle Fusion Middleware (subcomponent: BI Publisher Security). Supported versions that are affected are 11.1.1.9.0, 12.2.1.3.0 and 12.2.1.4.0. Easily exploitable vulnerability allows high privileged attacker with network access via HTTP to compromise BI Publisher (formerly XML Publisher). Successful attacks of this vulnerability can result in unauthorized access to critical data or complete access to all BI Publisher (formerly XML Publisher) accessible data. CVSS 3.0 Base Score 4.9 (Confidentiality impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:N/A:N).

### [CVE-2019-2618](https://github.com/jas502n/cve-2019-2618/blob/master/cve-2019-2618.py)

- Vulnerability in the Oracle WebLogic Server component of Oracle Fusion Middleware (subcomponent: WLS Core Components). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0 and 12.2.1.3.0. Easily exploitable vulnerability allows high privileged attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in unauthorized access to critical data or complete access to all Oracle WebLogic Server accessible data as well as unauthorized update, insert or delete access to some of Oracle WebLogic Server accessible data. CVSS 3.0 Base Score 5.5 (Confidentiality and Integrity impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:L/A:N).

### [CVE-2019-2725](https://paper.seebug.org/910/)

- Vulnerability in the Oracle WebLogic Server component of Oracle Fusion Middleware (subcomponent: Web Services). Supported versions that are affected are 10.3.6.0.0 and 12.1.3.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.0 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).

### [CVE-2019-2888](https://github.com/jas502n/CVE-2019-2888)

- Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: EJB Container). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0 and 12.2.1.3.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in unauthorized read access to a subset of Oracle WebLogic Server accessible data. CVSS 3.0 Base Score 5.3 (Confidentiality impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:L/I:N/A:N).

### [CVE-2019-2890](https://www.anquanke.com/post/id/190154)

- Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Web Services). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0 and 12.2.1.3.0. Easily exploitable vulnerability allows high privileged attacker with network access via T3 to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.0 Base Score 7.2 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H).

### [CVE-2020-3187](https://twitter.com/aboul3la/status/1286809567989575685)

- A vulnerability in the web services interface of Cisco Adaptive Security Appliance (ASA) Software and Cisco Firepower Threat Defense (FTD) Software could allow an unauthenticated, remote attacker to conduct directory traversal attacks and obtain read and delete access to sensitive files on a targeted system. The vulnerability is due to a lack of proper input validation of the HTTP URL. An attacker could exploit this vulnerability by sending a crafted HTTP request containing directory traversal character sequences. An exploit could allow the attacker to view or delete arbitrary files on the targeted system. When the device is reloaded after exploitation of this vulnerability, any files that were deleted are restored. The attacker can only view and delete files within the web services file system. This file system is enabled when the affected device is configured with either WebVPN or AnyConnect features. This vulnerability can not be used to obtain access to ASA or FTD system files or underlying operating system (OS) files. Reloading the affected device will restore all files within the web services file system.

### [CVE-2019-3394](https://github.com/jas502n/CVE-2019-3394)

- There was a local file disclosure vulnerability in Confluence Server and Confluence Data Center via page exporting. An attacker with permission to editing a page is able to exploit this issue to read arbitrary file on the server under \<install-directory>/confluence/WEB-INF directory, which may contain configuration files used for integrating with other services, which could potentially leak credentials or other sensitive information such as LDAP credentials. The LDAP credential will be potentially leaked only if the Confluence server is configured to use LDAP as user repository. All versions of Confluence Server from 6.1.0 before 6.6.16 (the fixed version for 6.6.x), from 6.7.0 before 6.13.7 (the fixed version for 6.13.x), and from 6.14.0 before 6.15.8 (the fixed version for 6.15.x) are affected by this vulnerability.

### [CVE-2019-3396](https://github.com/jas502n/CVE-2019-3396)

- The Widget Connector macro in Atlassian Confluence Server before version 6.6.12 (the fixed version for 6.6.x), from version 6.7.0 before 6.12.3 (the fixed version for 6.12.x), from version 6.13.0 before 6.13.3 (the fixed version for 6.13.x), and from version 6.14.0 before 6.14.2 (the fixed version for 6.14.x), allows remote attackers to achieve path traversal and remote code execution on a Confluence Server or Data Center instance via server-side template injection.

### [CVE-2019-3560](https://lgtm.com/blog/facebook_fizz_CVE-2019-3560)

- An improperly performed length calculation on a buffer in PlaintextRecordLayer could lead to an infinite loop and denial-of-service based on user input. This issue affected versions of fizz prior to v2019.03.04.00.

### [CVE-2019-3921](https://github.com/tenable/poc/blob/master/gpon/nokia_a-l_i-240w-q/gpon_poc_cve-2019-3921.py)

- The Alcatel Lucent I-240W-Q GPON ONT using firmware version 3FE54567BOZJ19 is vulnerable to a stack buffer overflow via crafted HTTP POST request sent by a remote, authenticated attacker to /GponForm/usb_Form?script/. An attacker can leverage this vulnerability to potentially execute arbitrary code.

### [CVE-2019-5241](https://www.microsoft.com/security/blog/2019/03/25/from-alert-to-driver-vulnerability-microsoft-defender-atp-investigation-unearths-privilege-escalation-flaw/)

- There is a privilege escalation vulnerability in Huawei PCManager versions earlier than PCManager 9.0.1.50. The attacker can tricking a user to install and run a malicious application to exploit this vulnerability. Successful exploitation may cause the attacker to obtain a higher privilege.

### [CVE-2019-5418](https://gist.github.com/mala/bdcf8681615d9b5ba7814f48dcea8d60)

- There is a File Content Disclosure vulnerability in Action View (Rails) <5.2.2.1, <5.1.6.2, <5.0.7.2, <4.2.11.1 where specially crafted accept headers can cause contents of arbitrary files on the target system's filesystem to be exposed.

### [CVE-2019-5624](https://blog.doyensec.com/2019/04/24/rubyzip-bug.html)

- Rapid7 Metasploit Framework suffers from an instance of CWE-22, Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal') in the Zip import function of Metasploit. Exploiting this vulnerability can allow an attacker to execute arbitrary code in Metasploit at the privilege level of the user running Metasploit. This issue affects: Rapid7 Metasploit Framework version 4.14.0 and prior versions.

### [CVE-2019-5736](https://github.com/feexd/pocs/blob/master/CVE-2019-5736/exploit.c)

- runc through 1.0-rc6, as used in Docker before 18.09.2 and other products, allows attackers to overwrite the host runc binary (and consequently obtain host root access) by leveraging the ability to execute a command as root within one of these types of containers: (1) a new container with an attacker-controlled image, or (2) an existing container, to which the attacker previously had write access, that can be attached with docker exec. This occurs because of file-descriptor mishandling, related to /proc/self/exe.

### [CVE-2019-5790](https://bugs.chromium.org/p/chromium/issues/detail?id=914736)

- An integer overflow leading to an incorrect capacity of a buffer in JavaScript in Google Chrome prior to 73.0.3683.75 allowed a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page.

### [CVE-2019-6251](https://gitlab.gnome.org/GNOME/epiphany/issues/532)

- WebKitGTK and WPE WebKit prior to version 2.24.1 are vulnerable to address bar spoofing upon certain JavaScript redirections. An attacker could cause malicious web content to be displayed as if for a trusted URI. This is similar to the CVE-2018-8383 issue in Microsoft Edge.

### [CVE-2019-7192](https://github.com/cycraft-corp/cve-2019-7192-check)

- This improper access control vulnerability allows remote attackers to gain unauthorized access to the system. To fix these vulnerabilities, QNAP recommend updating Photo Station to their latest versions.

### [CVE-2019-7193](https://github.com/cycraft-corp/cve-2019-7192-check)

- This improper input validation vulnerability allows remote attackers to inject arbitrary code to the system. To fix the vulnerability, QNAP recommend updating QTS to their latest versions.

### [CVE-2019-7194](https://github.com/cycraft-corp/cve-2019-7192-check)

- This external control of file name or path vulnerability allows remote attackers to access or modify system files. To fix the vulnerability, QNAP recommend updating Photo Station to their latest versions.

### [CVE-2019-7195](https://github.com/cycraft-corp/cve-2019-7192-check)

- This external control of file name or path vulnerability allows remote attackers to access or modify system files. To fix the vulnerability, QNAP recommend updating Photo Station to their latest versions.

### [CVE-2019-7238](https://github.com/jas502n/CVE-2019-7238)

- Sonatype Nexus Repository Manager before 3.15.0 has Incorrect Access Control.

### [CVE-2019-7286](https://blog.zecops.com/vulnerabilities/analysis-and-reproduction-of-cve-2019-7286/)

- A memory corruption issue was addressed with improved input validation. This issue is fixed in iOS 12.1.4, macOS Mojave 10.14.3 Supplemental Update. An application may be able to gain elevated privileges.

### [CVE-2019-7609](https://github.com/jas502n/kibana-RCE)

- Kibana versions before 5.6.15 and 6.6.1 contain an arbitrary code execution flaw in the Timelion visualizer. An attacker with access to the Timelion application could send a request that will attempt to execute javascript code. This could possibly lead to an attacker executing arbitrary commands with permissions of the Kibana process on the host system.

### [CVE-2019-8451](https://github.com/jas502n/CVE-2019-8451)

- The /plugins/servlet/gadgets/makeRequest resource in Jira before version 8.4.0 allows remote attackers to access the content of internal network resources via a Server Side Request Forgery (SSRF) vulnerability due to a logic bug in the JiraWhitelist class.

### [CVE-2019-8518](http://dwfault-blog.imwork.net:30916/2019/04/27/CVE-2019-8518%20FTL%20LICM%20GetByVal%20hoisted%20OOB/)

- Multiple memory corruption issues were addressed with improved memory handling. This issue is fixed in iOS 12.2, tvOS 12.2, watchOS 5.2, Safari 12.1, iTunes 12.9.4 for Windows, iCloud for Windows 7.11. Processing maliciously crafted web content may lead to arbitrary code execution.

### [CVE-2019-8565](https://github.com/ChiChou/sploits/tree/master/CVE-2019-8565)

- A race condition was addressed with additional validation. This issue is fixed in iOS 12.2, macOS Mojave 10.14.4. A malicious application may be able to gain root privileges.

### [CVE-2019-9213](https://bugs.chromium.org/p/project-zero/issues/detail?id=1792)

- In the Linux kernel before 4.20.14, expand_downwards in mm/mmap.c lacks a check for the mmap minimum address, which makes it easier for attackers to exploit kernel NULL pointer dereferences on non-SMAP platforms. This is related to a capability check for the wrong task.

### [CVE-2019-10038](https://www.inputzero.io/2019/04/evernote-cve-2019-10038.html)

- Evernote 7.9 on macOS allows attackers to execute arbitrary programs by embedding a reference to a local executable file such as the /Applications/Calculator.app/Contents/MacOS/Calculator file.

### [CVE-2019-10392](https://github.com/jas502n/CVE-2019-10392)

- Jenkins Git Client Plugin 2.8.4 and earlier did not properly restrict values passed as URL argument to an invocation of 'git ls-remote', resulting in OS command injection.

### [CVE-2019-11043](https://github.com/jas502n/CVE-2019-11043)

- In PHP versions 7.1.x below 7.1.33, 7.2.x below 7.2.24 and 7.3.x below 7.3.11 in certain configurations of FPM setup it is possible to cause FPM module to write past allocated buffers into the space reserved for FCGI protocol data, thus opening the possibility of remote code execution.

### [CVE-2019-11354](https://zeropwn.github.io/2019-05-22-fun-with-uri-handlers/)

- The client in Electronic Arts (EA) Origin 10.5.36 on Windows allows template injection in the title parameter of the Origin2 URI handler. This can be used to escape the underlying AngularJS sandbox and achieve remote code execution via an origin2://game/launch URL for QtApplication QDesktopServices communication.

### [CVE-2019-11358](https://snyk.io/blog/after-three-years-of-silence-a-new-jquery-prototype-pollution-vulnerability-emerges-once-again/)

- jQuery before 3.4.0, as used in Drupal, Backdrop CMS, and other products, mishandles jQuery.extend(true, {}, ...) because of Object.prototype pollution. If an unsanitized source object contained an enumerable __proto__ property, it could extend the native Object.prototype.

### [CVE-2019-11510](https://github.com/jas502n/CVE-2019-11510-1)

- In Pulse Secure Pulse Connect Secure (PCS) 8.2 before 8.2R12.1, 8.3 before 8.3R7.1, and 9.0 before 9.0R3.4, an unauthenticated remote attacker can send a specially crafted URI to perform an arbitrary file reading vulnerability.

### [CVE-2019-11580](https://github.com/jas502n/CVE-2019-11580)

- Atlassian Crowd and Crowd Data Center had the pdkinstall development plugin incorrectly enabled in release builds. Attackers who can send unauthenticated or authenticated requests to a Crowd or Crowd Data Center instance can exploit this vulnerability to install arbitrary plugins, which permits remote code execution on systems running a vulnerable version of Crowd or Crowd Data Center. All versions of Crowd from version 2.1.0 before 3.0.5 (the fixed version for 3.0.x), from version 3.1.0 before 3.1.6 (the fixed version for 3.1.x), from version 3.2.0 before 3.2.8 (the fixed version for 3.2.x), from version 3.3.0 before 3.3.5 (the fixed version for 3.3.x), and from version 3.4.0 before 3.4.4 (the fixed version for 3.4.x) are affected by this vulnerability.

### [CVE-2019-11581](https://github.com/jas502n/CVE-2019-11581)

- There was a server-side template injection vulnerability in Jira Server and Data Center, in the ContactAdministrators and the SendBulkMail actions. An attacker is able to remotely execute code on systems that run a vulnerable version of Jira Server or Data Center. All versions of Jira Server and Data Center from 4.4.0 before 7.6.14, from 7.7.0 before 7.13.5, from 8.0.0 before 8.0.3, from 8.1.0 before 8.1.2, and from 8.2.0 before 8.2.3 are affected by this vulnerability.

### [CVE-2019-12384](https://github.com/jas502n/CVE-2019-12384)

- FasterXML jackson-databind 2.x before 2.9.9.1 might allow attackers to have a variety of impacts by leveraging failure to block the logback-core class from polymorphic deserialization. Depending on the classpath content, remote code execution may be possible.

### [CVE-2019-12409](https://github.com/jas502n/CVE-2019-12409)

- The 8.1.1 and 8.2.0 releases of Apache Solr contain an insecure setting for the ENABLE_REMOTE_JMX_OPTS configuration option in the default solr.in.sh configuration file shipping with Solr. If you use the default solr.in.sh file from the affected releases, then JMX monitoring will be enabled and exposed on RMI_PORT (default=18983), without any authentication. If this port is opened for inbound traffic in your firewall, then anyone with network access to your Solr nodes will be able to access JMX, which may in turn allow them to upload malicious code for execution on the Solr server.

### [CVE-2019-12415](https://blog.gypsyengineer.com/en/security/cve-2019-12415-xml-processing-vulnerability-in-apache-poi.html)

- In Apache POI up to 4.1.0, when using the tool XSSFExportToXml to convert user-provided Microsoft Excel documents, a specially crafted document can allow an attacker to read files from the local filesystem or from internal network resources via XML External Entity (XXE) Processing.

### [CVE-2019-12526](https://www.anquanke.com/post/id/190579)

- An issue was discovered in Squid before 4.9. URN response handling in Squid suffers from a heap-based buffer overflow. When receiving data from a remote server in response to an URN request, Squid fails to ensure that the response can fit within the buffer. This leads to attacker controlled data overflowing in the heap.

### [CVE-2019-12527](https://www.thezdi.com/blog/2019/8/22/cve-2019-12527-code-execution-on-squid-proxy-through-a-heap-buffer-overflow)

- An issue was discovered in Squid 4.0.23 through 4.7. When checking Basic Authentication with HttpHeader::getAuth, Squid uses a global buffer to store the decoded data. Squid does not check that the decoded length isn't greater than the buffer, leading to a heap-based buffer overflow with user controlled data.

### [CVE-2019-13272](https://github.com/jas502n/CVE-2019-13272)

- In the Linux kernel before 5.1.17, ptrace_link in kernel/ptrace.c mishandles the recording of the credentials of a process that wants to create a ptrace relationship, which allows local users to obtain root access by leveraging certain scenarios with a parent-child process relationship, where a parent drops privileges and calls execve (potentially allowing control by an attacker). One contributing factor is an object lifetime issue (which can also cause a panic). Another contributing factor is incorrect marking of a ptrace relationship as privileged, which is exploitable through (for example) Polkit's pkexec helper with PTRACE_TRACEME. NOTE: SELinux deny_ptrace might be a usable workaround in some environments.

### [CVE-2019-13720](https://securelist.com/chrome-0-day-exploit-cve-2019-13720-used-in-operation-wizardopium/94866/)

- Use after free in WebAudio in Google Chrome prior to 78.0.3904.87 allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page.

### [CVE-2019-14234](https://github.com/vulhub/vulhub/tree/master/django/CVE-2019-14234)

- An issue was discovered in Django 1.11.x before 1.11.23, 2.1.x before 2.1.11, and 2.2.x before 2.2.4. Due to an error in shallow key transformation, key and index lookups for django.contrib.postgres.fields.JSONField, and key lookups for django.contrib.postgres.fields.HStoreField, were subject to SQL injection. This could, for example, be exploited via crafted use of "OR 1=1" in a key or index name to return all records, using a suitably crafted dictionary, with dictionary expansion, as the **kwargs passed to the QuerySet.filter() function.

### [CVE-2019-14994](https://github.com/bugbounty-site/exploits/tree/master/CVE-2019-14994)

- The Customer Context Filter in Atlassian Jira Service Desk Server and Jira Service Desk Data Center before version 3.9.16, from version 3.10.0 before version 3.16.8, from version 4.0.0 before version 4.1.3, from version 4.2.0 before version 4.2.5, from version 4.3.0 before version 4.3.4, and version 4.4.0 allows remote attackers with portal access to view arbitrary issues in Jira Service Desk projects via a path traversal vulnerability. Note that when the 'Anyone can email the service desk or raise a request in the portal' setting is enabled, an attacker can grant themselves portal access, allowing them to exploit the vulnerability.

### [CVE-2019-15107](https://github.com/jas502n/CVE-2019-15107)

- An issue was discovered in Webmin <=1.920. The parameter old in password_change.cgi contains a command injection vulnerability.

### [CVE-2019-15126](https://www.welivesecurity.com/2020/02/26/krook-serious-vulnerability-affected-encryption-billion-wifi-devices/)

- An issue was discovered on Broadcom Wi-Fi client devices. Specifically timed and handcrafted traffic can cause internal errors (related to state transitions) in a WLAN device that lead to improper layer 2 Wi-Fi encryption with a consequent possibility of information disclosure over the air for a discrete set of traffic, a different vulnerability than CVE-2019-9500, CVE-2019-9501, CVE-2019-9502, and CVE-2019-9503.

### [CVE-2019-15642](https://github.com/jas502n/CVE-2019-15642)

- rpc.cgi in Webmin through 1.920 allows authenticated Remote Code Execution via a crafted object name because unserialise_variable makes an eval call. NOTE: the Webmin_Servers_Index documentation states "RPC can be used to run any command or modify any file on a server, which is why access to it must not be granted to un-trusted Webmin users."

### [CVE-2019-16278](https://github.com/jas502n/CVE-2019-16278)

- Directory Traversal in the function http_verify in nostromo nhttpd through 1.9.6 allows an attacker to achieve remote code execution via a crafted HTTP request.

### [CVE-2019-16384](https://labs.nettitude.com/blog/cve-2019-16384-85-cyblesoft-thinfinity-virtualui-path-traversal-http-header-injection/)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2019-16385](https://labs.nettitude.com/blog/cve-2019-16384-85-cyblesoft-thinfinity-virtualui-path-traversal-http-header-injection/)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2019-16759](https://github.com/jas502n/CVE-2019-16759)

- vBulletin 5.x through 5.5.4 allows remote command execution via the widgetConfig[code] parameter in an ajax/render/widget_php routestring request.

### [CVE-2019-17564](https://mp.weixin.qq.com/s/reQaUVCa6RNG9tG_IZ_UjA)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2019-18683](http://blog.ptsecurity.com/2020/03/cve-2019-18683-exploiting-linux-kernel.html)

- An issue was discovered in drivers/media/platform/vivid in the Linux kernel through 5.3.8. It is exploitable for privilege escalation on some Linux distributions where local users have /dev/video0 access, but only if the driver happens to be loaded. There are multiple race conditions during streaming stopping in this driver (part of the V4L2 subsystem). These issues are caused by wrong mutex locking in vivid_stop_generating_vid_cap(), vivid_stop_generating_vid_out(), sdr_cap_stop_streaming(), and the corresponding kthreads. At least one of these race conditions leads to a use-after-free.

### [CVE-2019-18935](https://know.bishopfox.com/research/cve-2019-18935-remote-code-execution-in-telerik-ui)

- Progress Telerik UI for ASP.NET AJAX through 2019.3.1023 contains a .NET deserialization vulnerability in the RadAsyncUpload function. This is exploitable when the encryption keys are known due to the presence of CVE-2017-11317 or CVE-2017-11357, or other means. Exploitation can result in remote code execution. (As of 2020.1.114, a default setting prevents the exploit. In 2019.3.1023, but not earlier versions, a non-default setting can prevent exploitation.)

### [CVE-2019-19781](https://github.com/jas502n/CVE-2019-19781)

- An issue was discovered in Citrix Application Delivery Controller (ADC) and Gateway 10.5, 11.1, 12.0, 12.1, and 13.0. They allow Directory Traversal.

### [CVE-2019-20197](https://code610.blogspot.com/2019/12/postauth-rce-in-latest-nagiosxi.html)

- In Nagios XI 5.6.9, an authenticated user is able to execute arbitrary OS commands via shell metacharacters in the id parameter to schedulereport.php, in the context of the web-server user account.

### [CVE-2020-0601](https://github.com/ioncodes/Curveball)

- A spoofing vulnerability exists in the way Windows CryptoAPI (Crypt32.dll) validates Elliptic Curve Cryptography (ECC) certificates.An attacker could exploit the vulnerability by using a spoofed code-signing certificate to sign a malicious executable, making it appear the file was from a trusted, legitimate source, aka 'Windows CryptoAPI Spoofing Vulnerability'.

### [CVE-2020-0609](https://github.com/ollypwn/BlueGate)

- A remote code execution vulnerability exists in Windows Remote Desktop Gateway (RD Gateway) when an unauthenticated attacker connects to the target system using RDP and sends specially crafted requests, aka 'Windows Remote Desktop Gateway (RD Gateway) Remote Code Execution Vulnerability'. This CVE ID is unique from CVE-2020-0610.

### [CVE-2020-0610](https://github.com/ollypwn/BlueGate)

- A remote code execution vulnerability exists in Windows Remote Desktop Gateway (RD Gateway) when an unauthenticated attacker connects to the target system using RDP and sends specially crafted requests, aka 'Windows Remote Desktop Gateway (RD Gateway) Remote Code Execution Vulnerability'. This CVE ID is unique from CVE-2020-0609.

### [CVE-2020-0646](https://www.mdsec.co.uk/2020/01/code-injection-in-workflows-leading-to-sharepoint-rce-cve-2020-0646/)

- A remote code execution vulnerability exists when the Microsoft .NET Framework fails to validate input properly, aka '.NET Framework Remote Code Execution Injection Vulnerability'.

### [CVE-2020-0668](https://itm4n.github.io/cve-2020-0668-windows-service-tracing-eop/)

- An elevation of privilege vulnerability exists in the way that the Windows Kernel handles objects in memory, aka 'Windows Kernel Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2020-0669, CVE-2020-0670, CVE-2020-0671, CVE-2020-0672.

### [CVE-2020-0683](https://padovah4ck.github.io/CVE-2020-0683/)

- An elevation of privilege vulnerability exists in the Windows Installer when MSI packages process symbolic links, aka 'Windows Installer Elevation of Privilege Vulnerability'. This CVE ID is unique from CVE-2020-0686.

### [CVE-2020-0688](https://www.thezdi.com/blog/2020/2/24/cve-2020-0688-remote-code-execution-on-microsoft-exchange-server-through-fixed-cryptographic-keys)

- A remote code execution vulnerability exists in Microsoft Exchange software when the software fails to properly handle objects in memory, aka 'Microsoft Exchange Memory Corruption Vulnerability'.

### [CVE-2020-0787](https://itm4n.github.io/cve-2020-0787-windows-bits-eop/)

- An elevation of privilege vulnerability exists when the Windows Background Intelligent Transfer Service (BITS) improperly handles symbolic links, aka 'Windows Background Intelligent Transfer Service Elevation of Privilege Vulnerability'.

### [CVE-2020-0796](https://github.com/ZecOps/CVE-2020-0796-RCE-POC/)

- A remote code execution vulnerability exists in the way that the Microsoft Server Message Block 3.1.1 (SMBv3) protocol handles certain requests, aka 'Windows SMBv3 Client/Server Remote Code Execution Vulnerability'.

### [CVE-2020-0863](https://itm4n.github.io/cve-2020-0863-windows-diagtrack-info-disclo/)

- An information vulnerability exists when Windows Connected User Experiences and Telemetry Service improperly discloses file information, aka 'Connected User Experiences and Telemetry Service Information Disclosure Vulnerability'.

### [CVE-2020-0932](https://www.thezdi.com/blog/2020/4/28/cve-2020-0932-remote-code-execution-on-microsoft-sharepoint-using-typeconverters)

- A remote code execution vulnerability exists in Microsoft SharePoint when the software fails to check the source markup of an application package, aka 'Microsoft SharePoint Remote Code Execution Vulnerability'. This CVE ID is unique from CVE-2020-0920, CVE-2020-0929, CVE-2020-0931, CVE-2020-0971, CVE-2020-0974.

### [CVE-2020-0984](https://theevilbit.github.io/posts/secure_coding_privilegedhelpertools_part3/)

- An elevation of privilege vulnerability exists when the Microsoft AutoUpdate (MAU) application for Mac improperly validates updates before executing them, aka 'Microsoft (MAU) Office Elevation of Privilege Vulnerability'.

### [CVE-2020-1181](https://www.zerodayinitiative.com/blog/2020/6/16/cve-2020-1181-sharepoint-remote-code-execution-through-web-parts)

- A remote code execution vulnerability exists in Microsoft SharePoint Server when it fails to properly identify and filter unsafe ASP.Net web controls, aka 'Microsoft SharePoint Server Remote Code Execution Vulnerability'.

### [CVE-2020-1206](https://github.com/ZecOps/CVE-2020-1206-POC)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2020-1938](https://www.chaitin.cn/en/ghostcat)

- When using the Apache JServ Protocol (AJP), care must be taken when trusting incoming connections to Apache Tomcat. Tomcat treats AJP connections as having higher trust than, for example, a similar HTTP connection. If such connections are available to an attacker, they can be exploited in ways that may be surprising. In Apache Tomcat 9.0.0.M1 to 9.0.0.30, 8.5.0 to 8.5.50 and 7.0.0 to 7.0.99, Tomcat shipped with an AJP Connector enabled by default that listened on all configured IP addresses. It was expected (and recommended in the security guide) that this Connector would be disabled if not required. This vulnerability report identified a mechanism that allowed: - returning arbitrary files from anywhere in the web application - processing any file in the web application as a JSP Further, if the web application allowed file upload and stored those files within the web application (or the attacker was able to control the content of the web application by some other means) then this, along with the ability to process a file as a JSP, made remote code execution possible. It is important to note that mitigation is only required if an AJP port is accessible to untrusted users. Users wishing to take a defence-in-depth approach and block the vector that permits returning arbitrary files and execution as JSP may upgrade to Apache Tomcat 9.0.31, 8.5.51 or 7.0.100 or later. A number of changes were made to the default AJP Connector configuration in 9.0.31 to harden the default configuration. It is likely that users upgrading to 9.0.31, 8.5.51 or 7.0.100 or later will need to make small changes to their configurations.

### [CVE-2020-2096](https://twitter.com/j3ssiejjj/status/1217638755906883584)

- Jenkins Gitlab Hook Plugin 1.4.2 and earlier does not escape project names in the build_now endpoint, resulting in a reflected XSS vulnerability.

### [CVE-2020-2551](https://github.com/hktalent/CVE-2020-2551/blob/master/CVE-2020-2551.py)

- Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: WLS Core Components). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.3.0 and 12.2.1.4.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via IIOP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.0 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).

### [CVE-2020-2555](https://www.thezdi.com/blog/2020/3/5/cve-2020-2555-rce-through-a-deserialization-bug-in-oracles-weblogic-server)

- Vulnerability in the Oracle Coherence product of Oracle Fusion Middleware (component: Caching,CacheStore,Invocation). Supported versions that are affected are 3.7.1.17, 12.1.3.0.0, 12.2.1.3.0 and 12.2.1.4.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via T3 to compromise Oracle Coherence. Successful attacks of this vulnerability can result in takeover of Oracle Coherence. CVSS 3.0 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).

### [CVE-2020-28948](https://github.com/pear/Archive_Tar/issues/33)

- Archive_Tar through 1.4.10 allows an unserialization attack because phar: is blocked but PHAR: is not blocked.

### [CVE-2020-28949](https://github.com/pear/Archive_Tar/issues/33)

- Archive_Tar through 1.4.10 has :// filename sanitization only to address phar attacks, and thus any other stream-wrapper attack (such as file:// to overwrite files) can still succeed.

### [CVE-2020-3452](https://twitter.com/aboul3la/status/1286012324722155525)

- A vulnerability in the web services interface of Cisco Adaptive Security Appliance (ASA) Software and Cisco Firepower Threat Defense (FTD) Software could allow an unauthenticated, remote attacker to conduct directory traversal attacks and read sensitive files on a targeted system. The vulnerability is due to a lack of proper input validation of URLs in HTTP requests processed by an affected device. An attacker could exploit this vulnerability by sending a crafted HTTP request containing directory traversal character sequences to an affected device. A successful exploit could allow the attacker to view arbitrary files within the web services file system on the targeted device. The web services file system is enabled when the affected device is configured with either WebVPN or AnyConnect features. This vulnerability cannot be used to obtain access to ASA or FTD system files or underlying operating system (OS) files.

### [CVE-2020-3882](https://research.nccgroup.com/2020/05/28/exploring-macos-calendar-alerts-part-2-exfiltrating-data-cve-2020-3882/)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2020-3950](https://github.com/mirchr/security-research/blob/master/vulnerabilities/CVE-2020-3950.sh)

- VMware Fusion (11.x before 11.5.2), VMware Remote Console for Mac (11.x and prior before 11.0.1) and Horizon Client for Mac (5.x and prior before 5.4.0) contain a privilege escalation vulnerability due to improper use of setuid binaries. Successful exploitation of this issue may allow attackers with normal user privileges to escalate their privileges to root on the system where Fusion, VMRC or Horizon Client is installed.

### [CVE-2020-3956](https://github.com/aaronsvk/CVE-2020-3956/)

- VMware Cloud Director 10.0.x before 10.0.0.2, 9.7.0.x before 9.7.0.5, 9.5.0.x before 9.5.0.6, and 9.1.0.x before 9.1.0.4 do not properly handle input leading to a code injection vulnerability. An authenticated actor may be able to send malicious traffic to VMware Cloud Director which may lead to arbitrary remote code execution. This vulnerability can be exploited through the HTML5- and Flex-based UIs, the API Explorer interface and API access.

### [CVE-2020-5398](https://github.com/motikan2010/CVE-2020-5398)

- In Spring Framework, versions 5.2.x prior to 5.2.3, versions 5.1.x prior to 5.1.13, and versions 5.0.x prior to 5.0.16, an application is vulnerable to a reflected file download (RFD) attack when it sets a "Content-Disposition" header in the response where the filename attribute is derived from user supplied input.

### [CVE-2020-5902](https://gist.github.com/cihanmehmet/07d2f9dac55f278839b054b8eb7d4cc5)

- In BIG-IP versions 15.0.0-15.1.0.3, 14.1.0-14.1.2.5, 13.1.0-13.1.3.3, 12.1.0-12.1.5.1, and 11.6.1-11.6.5.1, the Traffic Management User Interface (TMUI), also referred to as the Configuration utility, has a Remote Code Execution (RCE) vulnerability in undisclosed pages.

### [CVE-2020-6418](https://github.com/ray-cp/browser_pwn/tree/master/cve-2020-6418)

- Type confusion in V8 in Google Chrome prior to 80.0.3987.122 allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page.

### [CVE-2020-7961](https://codewhitesec.blogspot.com/2020/03/liferay-portal-json-vulns.html)

- Deserialization of Untrusted Data in Liferay Portal prior to 7.2.1 CE GA2 allows remote attackers to execute arbitrary code via JSON web services (JSONWS).

### [CVE-2020-8840](https://github.com/jas502n/CVE-2020-8840)

- FasterXML jackson-databind 2.0.0 through 2.9.10.2 lacks certain xbean-reflect/JNDI blocking, as demonstrated by org.apache.xbean.propertyeditor.JndiConverter.

### [CVE-2020-9471](https://gitlab.com/eLeN3Re/cve-2020-9471)

- Umbraco Cloud 8.5.3 allows an authenticated file upload (and consequently Remote Code Execution) via the Install Packages functionality.

### [CVE-2020-9472](https://gitlab.com/eLeN3Re/cve-2020-9472)

- Umbraco CMS 8.5.3 allows an authenticated file upload (and consequently Remote Code Execution) via the Install Package functionality.

### [CVE-2020-9484](https://www.redtimmy.com/java-hacking/apache-tomcat-rce-by-deserialization-cve-2020-9484-write-up-and-exploit/)

- When using Apache Tomcat versions 10.0.0-M1 to 10.0.0-M4, 9.0.0.M1 to 9.0.34, 8.5.0 to 8.5.54 and 7.0.0 to 7.0.103 if a) an attacker is able to control the contents and name of a file on the server; and b) the server is configured to use the PersistenceManager with a FileStore; and c) the PersistenceManager is configured with sessionAttributeValueClassNameFilter="null" (the default unless a SecurityManager is used) or a sufficiently lax filter to allow the attacker provided object to be deserialized; and d) the attacker knows the relative file path from the storage location used by FileStore to the file the attacker has control over; then, using a specifically crafted request, the attacker will be able to trigger remote code execution via deserialization of the file under their control. Note that all of conditions a) to d) must be true for the attack to succeed.

### [CVE-2020-9546](https://www.anquanke.com/post/id/200010)

- FasterXML jackson-databind 2.x before 2.9.10.4 mishandles the interaction between serialization gadgets and typing, related to org.apache.hadoop.shaded.com.zaxxer.hikari.HikariConfig (aka shaded hikari-config).

### [CVE-2020-9547](https://www.anquanke.com/post/id/200010)

- FasterXML jackson-databind 2.x before 2.9.10.4 mishandles the interaction between serialization gadgets and typing, related to com.ibatis.sqlmap.engine.transaction.jta.JtaTransactionConfig (aka ibatis-sqlmap).

### [CVE-2020-9548](https://www.anquanke.com/post/id/200010)

- FasterXML jackson-databind 2.x before 2.9.10.4 mishandles the interaction between serialization gadgets and typing, related to br.com.anteros.dbcp.AnterosDBCPConfig (aka anteros-core).

### [CVE-2020-10673](https://github.com/0nise/CVE-2020-10673)

- FasterXML jackson-databind 2.x before 2.9.10.4 mishandles the interaction between serialization gadgets and typing, related to com.caucho.config.types.ResourceRef (aka caucho-quercus).

### [CVE-2020-11108](https://github.com/frichetten/CVE-2020-11108-PoC)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2020-11932](https://github.com/ProjectorBUg/CVE-2020-11932)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

## Code of Conduct

Please note that this project is released with a [Contributor Code of Conduct](code-of-conduct.md). By participating in this project you agree to abide by its terms.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [@qazbnm456](https://qazbnm456.github.io/) has waived all copyright and related or neighboring rights to this work.
