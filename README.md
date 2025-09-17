# RubberDuckyLinuxAttack
Rubber Ducky attack against a linux system using privilege escalation and defense evasion techniques within the MITRE attack framework.


## The Attack
Attack which leverages ill configured docker privileges to gain root access to a linux system, the intended outcome for the attack is to have a proxy running on the system which can then be used to intercept incoming and outgoing web traffic from the user including email addresses and passwords from HTTPS protected websites and forms.

## MITRE Attack Vectors
The attack vectors which were used and where they fall on the MITRE attack framework.

Initial Access: Hardware Additions T1200
Privilege Escalation: Escape to Host T1611
Create Account: Local Account T1136
Impair Command Logging History T1562.003
Hidden Users T1564.002
Indicator Removal T1070
Encrypted Channel: Assymetric Cryptography T1573.002
Adversary in the Middle T1557
