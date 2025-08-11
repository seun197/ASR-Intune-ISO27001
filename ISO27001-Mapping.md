# ISO 27001 Control Mapping for ASR Policy

| ASR Rule                                                                 | ISO 27001:2022 Control Reference           | Description |
|---------------------------------------------------------------------------|---------------------------------------------|-------------|
| Block executable content from email and webmail                          | A.8.7.1 Protection against malware          | Prevents execution of malicious files delivered via email/webmail |
| Block Office communication apps from creating child processes            | A.8.7.1 Protection against malware          | Stops exploitation via Teams/Skype |
| Block persistence through WMI event subscription                         | A.8.16.1 Management of technical vulnerabilities | Eliminates a known persistence method |
| Block Adobe Reader from creating child processes                         | A.8.7.1 Protection against malware          | Prevents PDF-based malware |
| Block execution of potentially obfuscated scripts                        | A.8.7.1 Protection against malware          | Stops ransomware and script-based attacks |
| Block Office apps from creating executable content                       | A.12.6.2 Restrictions on software installation | Stops Office macro → .exe malware |

