---
sort: 4
published: true
---

# Tips: Vulnerability 
Vulnerability 정보 수집, 알림, Score 표시 방법에 대한 내용입니다.
<br><br>  

## Vulnerability 정보 수집  
{: .left-bar-title }  
- Vulnerability 정보는 매일 [NVD Data Feed](https://nvd.nist.gov/vuln/data-feeds) 에서 다운로드되어 FOSSLight Hub에 저장됩니다.
- FOSSLight Hub의 Vulnerability Score는 기본적으로 CVSS v3 Base Score를 기준으로 표기하며, v3 Score가 없는 경우 CVSS v2 Base Score로 대신 표기합니다.  
<br><br><br>  

## Vulnerability 정보 알림  
{: .left-bar-title }  
- 기준 점수 이상인 Vulnerability Score가 최초로 등록되거나, 기준 점수 이상에서 기준 점수 미만으로 변경될 경우 알림 메일이 발송됩니다.
    - Identification이 Confirm된 Project에서 위 조건을 만족하는 OSS가 BOM에 포함된 경우 Project의 Creator, Edit Permission, Reviewer에게 Vulnerability Score 변경 내용이 발송됩니다.  
    - 알림 메일을 더 이상 받고 싶지 않은 경우, [Project Information에서 Security Mail (Vulnerability) 항목을 Disable로 변경](https://fosslight.org/hub-guide-en/tips/4_vul_info/#security-mailvulnerability)할 수 있습니다.  
<br><br><br>  

## Vulnerability Score 표시 방법  
{: .left-bar-title }  
- 사용자가 입력한 OSS Name/Nick name, Version이 동일한 Vulnerability가 존재하는 경우, 해당 OSS의 Max Score를 표시합니다.
    - 사용자가 입력한 OSS Version의 Vulnerability가 존재하는 경우, Vulnerability의 Max Score를 표시합니다.
    - 사용자가 입력한 OSS Version의 Vulnerability가 존재하지 않는 경우에는, 값이 존재하지 않으므로 표시하지 않습니다.
    - 사용자가 OSS Version을 공란으로 입력한 경우, 해당 OSS의 모든 Version 중 Max Score를 표시합니다.
- OSS Name이 '-'인 경우, Vulnerability를 표시하지 않습니다.
<br><br><br>


## Security Mail(Vulnerability)  
{: .left-bar-title }  
Security Mail (Vulnerability) 수신을 Enable / Disable 할 수 있습니다.  


### Security Mail(Vulnerability) 설정
{: .specific-title}
- Project Information >  Security Mail (Vulnerability)를 **Disable**로 설정하면 해당 Project의 Vulnerability 메일이 더 이상 발송되지 않습니다.
- Disable로 설정할 경우 사유가 반드시 입력되어야 합니다.  
![vul_mail_setting](../images/vulnerability/vul_mail_setting.png){: .styled-image} 

### Security Mail(Vulnerability)설정 검색 
{: .specific-title}
 - Project List에서 Security Mail(Vulnerability)의 Setting 값(Enable or Disable)으로 검색할 수 있습니다.  
![vul_mail_search](../images/vulnerability/vul_mail_search.png){: .styled-image} 
