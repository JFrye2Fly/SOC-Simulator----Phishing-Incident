# SOC-Simulator--Phishing-Incident

## Introduction

In this project I investigate the results of a phishing incident by using VirusTotal, Splunk and log analysis, and Open-Source Intelligence to detect malicioous activities versus false positives. 


## Overall Summary of Phishing SOC Simulation 
![Overall Summary of SOC Simulation ](https://github.com/user-attachments/assets/1cdbb41a-9fab-4f32-bd1d-ecc3ccffbed5)


## Identifying False/True Positives and escalating or discarding them 
![Identifying False/True Positives and escalating or discarding them ](https://github.com/user-attachments/assets/3de79132-d35b-4a8d-8e8c-07cae5074991) 

## Email Sender Domain is Malicious -- VirusTotal
![Email Sender Domain is Malicious -- VirusTotal](https://github.com/user-attachments/assets/b032f3cb-1b51-4352-a6e5-a378fe3c60e8) 


## Wow... A network drive was mapped to a shared folder on a remote server...Then the Network Drive was deleeted... SUPER SUSPICIOUS

**Remote server: **FILESRV-01 
**Folder on Remote server the Network drive was coped to: **\SSF-FinancialRecords

![NETWORK DRIVE DELETED](https://github.com/user-attachments/assets/ea23c7d3-aa43-42e7-9575-0471d19de74e) 


## ROBOCOPY.EXE  -- This malicious binary appears to copy important files such as "InvestorPresentation2023.pptx" and "ClientPortfolioSummary.xlsx"



![NETWORK DRIVE DELETED](https://github.com/user-attachments/assets/ea23c7d3-aa43-42e7-9575-0471d19de74e) 
) 


Tools used: 
- Splunk 
- Sysmon (Windows System Monitor)
- Virus Total
- Open-Source Intelligence 



## Conclusion

In this project it was found that a bad actor accessed and exfiltrated data from user Michael Ascot's account. 
