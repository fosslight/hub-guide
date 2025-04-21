---
sort: 2 
published: true
title: 2.Identification 
---


# Identification 
<div class="note">
배포하는 Project에 대하여 Open Source Software 분석 결과를 작성하고, OSPO의 리뷰를 받습니다.
</div>

{% include list.liquid all=true %}

## 일반 Project의 Identification Process
{: .left-bar-title }
- **3rd Party, DEP 탭, SRC, BIN 탭 작성 → BOM 탭**에서 **Request** 버튼을 클릭하여 리뷰 요청  
        - [**3rd Party**](https://fosslight.org/hub-guide/tutorial/1_project/2_Identification/1_3rd_Party_Tab.html): 해당 Project에 포함된 3rd Party를 load합니다.  
        - [**DEP**](https://fosslight.org/hub-guide/tutorial/1_project/2_Identification/2_DEP_Tab.html): Dependency 분석 결과를 작성합니다.  
        - [**SRC**](https://fosslight.org/hub-guide/tutorial/1_project/2_Identification/3_SRC_Tab.html): Source code 분석 결과를 작성합니다.  
        - [**BIN**](https://fosslight.org/hub-guide/tutorial/1_project/2_Identification/4_BIN_Tab.html): Binary 분석 결과를 작성합니다.  
        - [**BOM**](https://fosslight.org/hub-guide/tutorial/1_project/2_Identification/5_BOM_Tab.html): 다른 탭에 작성된 OSS List를 취합하고 Warning message를 검토한 후 리뷰 요청을 합니다.  

## (LGE Only) Platform-generated Project의 Identification Process
{: .left-bar-title }
- BIN(Android), BIN(Yocto) Tab : 각 탭 작성 → Request 버튼을 클릭하여 리뷰 요청합니다.  
        - BIN(Android) : [Android binary 분석](https://fosslight.org/fosslight-guide/scanner/6_android.html) 결과를 작성합니다.  
        - BIN(Yocto) : [Yocto 분석](https://fosslight.org/fosslight-guide/scanner/5_yocto.html) 결과를 작성합니다.  