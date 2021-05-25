---
name: CIDer
position: maintenance
avatar: cider_image.png
url: https://github.com/dbwilburn/cider
started: 2021
---

<img width="300" src="{{site.baseurl}}/images/software/{{page.avatar}}" data-action="zoom">

_A statistical framework for interpreting CID and HCD fragmentation_

### Download
[https://github.com/dbwilburn/cider](https://github.com/dbwilburn/cider)

### Description

CIDer is a simple Python3 compatible script that will "CID correct" spectrum libraries acquired by HCD in DLIB format. The conversion is based on a series of linear weights that were learned across multiple NCE settings (6 values spanning 20 to 35) with interpolations for all intermediate values. Details of the training and inferred features can be found in the [associated manuscript](https://pubs.acs.org/doi/abs/10.1021/acs.jproteome.0c00964) at JPR.
