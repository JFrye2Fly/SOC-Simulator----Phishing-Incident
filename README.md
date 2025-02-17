d# SOC-Simulator--Phishing-Incident

## Introduction

In this project I investigate the results of a phishing incident by using VirusTotal, Splunk and log analysis, and Open-Source Intelligence to detect malicioous activities versus false positives. 


## Overall Summary of Phishing SOC Simulation 
![Overall Summary of SOC Simulation ](https://github.com/user-attachments/assets/1cdbb41a-9fab-4f32-bd1d-ecc3ccffbed5)


## Identifying False/True Positives and escalating or discarding them 
![Identifying False/True Positives and escalating or discarding them ](https://github.com/user-attachments/assets/3de79132-d35b-4a8d-8e8c-07cae5074991) 

## Two security Vendors marked this domain as suspicious. -- VirusTotal
![Email Sender Domain is Malicious -- VirusTotal](https://github.com/user-attachments/assets/b032f3cb-1b51-4352-a6e5-a378fe3c60e8) 


## Wow... A network drive was mapped to a shared folder on a remote server...Then the Network Drive was deleted... SUPER SUSPICIOUS

**Remote server: **FILESRV-01 <br> 
**Folder on Remote server the Network drive was coped to: **\SSF-FinancialRecords

![NETWORK DRIVE DELETED](https://github.com/user-attachments/assets/ea23c7d3-aa43-42e7-9575-0471d19de74e) 


## ROBOCOPY.EXE  -- This malicious binary appears to copy important files such as "InvestorPresentation2023.pptx" and "ClientPortfolioSummary.xlsx" to a folder named: "C:\Users\michael.ascot\downloads\exfiltration"

Interesting points: 

###Folder Name: Exfiltration <br>
The working directory of the process is :Z


![EXFILTRATION ATEMPT](https://github.com/user-attachments/assets/232d95c9-7c8f-42dd-bc32-7c624a6470ed) 



Tools used: 
- Splunk 
- Sysmon (Windows System Monitor)
- Virus Total
- Open-Source Intelligence 



## Conclusion


![Results](https://github.com/user-attachments/assets/85051f89-7c2d-4348-a6e1-27720cf8c330) 

