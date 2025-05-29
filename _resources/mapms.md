---
name: MAP-MS
position: active
avatar: mapms_image.png
url: https://searlelab.github.io
started: 2025
---

<img width="300" src="{{site.baseurl}}/images/resources/{{page.avatar}}" data-action="zoom">

_Multiple Accumulation Precursor Mass Spectrometry (MAP-MS)_

### Download Method Files
|MAP-MS|Standard|
| -------- | ------- |
|[MAP-MS DDA]({{site.baseurl}}/resources/mapms/Exploris_Aurora_25cm_max4uL_6xpDDA_90min_EndWash_BCS.meth)|[Standard DDA]({{site.baseurl}}/resources/mapms/Exploris_Aurora_25cm_max4uL_NormDDA_90min_EndWash_BCS.meth)|
|[MAP-MS DIA]({{site.baseurl}}/resources/mapms/Exploris_Aurora_25cm_max4uL_6xpDIA_16mzst_90min_EndWash_BCS.meth)|[Standard DIA]({{site.baseurl}}/resources/mapms/Exploris_Aurora_25cm_max4uL_NormDIA_16mzst_90min_EndWash_BCS.meth)|
|[MAP-MS GPF 400-500]({{site.baseurl}}/resources/mapms/Exploris_Aurora_25cm_max4uL_6xpGPFDIA_400to500_4mz_90min_EndWash_BCS.meth)|[Standard GPF 400-500]({{site.baseurl}}/resources/mapms/Exploris_Aurora_25cm_max4uL_GPFDIA_400to500_4mz_90min_EndWash_BCS.meth)|
|[MAP-MS GPF 500-600]({{site.baseurl}}/resources/mapms/Exploris_Aurora_25cm_max4uL_6xpGPFDIA_500to600_4mz_90min_EndWash_BCS.meth)|[Standard GPF 500-600]({{site.baseurl}}/resources/mapms/Exploris_Aurora_25cm_max4uL_GPFDIA_500to600_4mz_90min_EndWash_BCS.meth)|
|[MAP-MS GPF 600-700]({{site.baseurl}}/resources/mapms/Exploris_Aurora_25cm_max4uL_6xpGPFDIA_600to700_4mz_90min_EndWash_BCS.meth)|[Standard GPF 600-700]({{site.baseurl}}/resources/mapms/Exploris_Aurora_25cm_max4uL_GPFDIA_600to700_4mz_90min_EndWash_BCS.meth)|
|[MAP-MS GPF 700-800]({{site.baseurl}}/resources/mapms/Exploris_Aurora_25cm_max4uL_6xpGPFDIA_700to800_4mz_90min_EndWash_BCS.meth)|[Standard GPF 700-800]({{site.baseurl}}/resources/mapms/Exploris_Aurora_25cm_max4uL_GPFDIA_700to800_4mz_90min_EndWash_BCS.meth)|
|[MAP-MS GPF 800-900]({{site.baseurl}}/resources/mapms/Exploris_Aurora_25cm_max4uL_6xpGPFDIA_800to900_4mz_90min_EndWash_BCS.meth)|[Standard GPF 800-900]({{site.baseurl}}/resources/mapms/Exploris_Aurora_25cm_max4uL_GPFDIA_800to900_4mz_90min_EndWash_BCS.meth)|
|[MAP-MS GPF 900-1000]({{site.baseurl}}/resources/mapms/Exploris_Aurora_25cm_max4uL_6xpGPFDIA_900to1000_4mz_90min_EndWash_BCS.meth)|[Standard GPF 900-1000]({{site.baseurl}}/resources/mapms/Exploris_Aurora_25cm_max4uL_GPFDIA_900to1000_4mz_90min_EndWash_BCS.meth)|

### Description

MAP-MS takes advantage of parallelization in a trapping MS. In a hybrid Q-Orbitrap, parallelization still occurs: while one ion batch is measured, a new batch is accumulated. The Orbi's small capacity means MS1s accumulate in 1-2 ms, wasting the rest of the ion beam. 
MAP-MS accumulates pieces of the MS1 mass range in a single spectrum. At first this seems strange, but the benefit is to variably fill each range for a different length of time, allowing the instrument to spend more time on "empty" m/z regions.
This produces Orbitrap MS1s with nearly 2x the number of peaks and over 2x the dynamic range of "standard" MS1s. 

### Citation
Phlairaharn T., Shannon AE, Zeng X, Truong DJ, Schoof EM, Ye Z, Searle BC.
Improving proteomic dynamic range with Multiple Accumulation Precursor Mass Spectrometry (MAP-MS). [bioRxiv](https://doi.org/10.1101/2025.05.14.653938)
