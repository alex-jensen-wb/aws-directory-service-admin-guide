# Review Your AWS Managed Microsoft AD Directory Logs<a name="ms_ad_directory_logs"></a>

Security logs from AWS Managed Microsoft AD domain controller instances are archived for a year\. You can also configure your AWS Managed Microsoft AD directory to forward domain controller logs to Amazon CloudWatch Logs in near real time\. For more information, see [Enable Log Forwarding](ms_ad_enable_log_forwarding.md)\.

AWS logs the following events for compliance\. 


****  

| Monitoring category | Policy setting | Audit state | 
| --- | --- | --- | 
| Account Logon | Audit Credential Validation  | Success, Failure | 
| Account Management | Audit Computer Account Management  | Success, Failure | 
|  | Audit Other Account Management Events | Success, Failure | 
|  | Audit Security Group Management | Success, Failure | 
|  | Audit User Account Management | Success, Failure | 
| Detailed Tracking | Audit Process Creation | Success | 
| DS Access | Audit Directory Service Access | Success, Failure | 
|  | Audit Directory Service Changes | Success, Failure | 
| Logon/Logoff | Audit Account Lockout Success | Success, Failure | 
|  | Audit Logoff | Success | 
|  | Audit Logon | Success, Failure | 
|  | Audit Special Logon | Success | 
| Object Access | Audit Removable Storage | Success, Failure | 
|  | Audit Central Access Policy Staging | Success, Failure | 
| Policy Change | Audit Policy Change | Success, Failure | 
|  | Audit Authentication Policy Change | Success | 
|  | Audit Authorization Policy Change | Success, Failure | 
| Privilege Use | Audit Sensitive Privilege Use | Success, Failure | 
| System | Audit IPsec Driver | Success, Failure | 
|  | Audit Other System Events | Success, Failure | 
|  | Audit Security State Change | Success, Failure | 
|  | Audit Security System Extension | Success, Failure | 
|  | Audit System Integrity | Success, Failure | 