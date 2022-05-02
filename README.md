# letsdefend_ransom1
A brief walkthrough of the ransomware alert on Letsdefend.io

Ransomware Alert

This alert appears to be ransomware related caused by some form of Malware.

![img](https://github.com/dannyinVT/letsdefend_ransom1/blob/main/Picture1.png)

Upon closer inspection, we can see that the source address is from 172.16.17.88 MarkPRD.

File name – ab.exe
Hash - 0b486fe0503524cfe4726a4022fa6a68
The provided file was uploaded to Virustotal and the following was shown:

![img](https://github.com/dannyinVT/letsdefend_ransom1/blob/main/Picture2.png)

 
This file is obviously malicious and was also cleaned on my local machine as Sophos has labeled it as malware and automatically cleaned up.

The IP address according to the logs that the device was communicating with is - 81.169.145.105
This was shown to be a malicious address.

![img](https://github.com/dannyinVT/letsdefend_ransom1/blob/main/Picture3.png)
 

This alert was marked as a true positive and the device was isolated from the network.
