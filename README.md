# CVE_Assessments_01_2020


(CVE-2017-8759 Update)


The DVR Examiner version 2.8.3 relies on a .NET Framework version 4.6.2 that is vulnerable to remote code execution 
through an application (CVE-2017-8759).

The software has a compressed (23.7z) executable file (NDP462-KB3151800-x86-x64-AllOS-ENU.exe) that points to an untrusted 
source:

hxxps://download.microsoft.com/download/F/9/4/F942F07D-F26F-4F30-B4E3-EBD54FABA377/NDP462-KB3151800-x86-x64-AllOS-ENU.exe

hxxp://tsmovr.swehockey.se/install/dotnet4.exe

For which the correct addressed would be:

https://support.microsoft.com/en-us/help/3151800/the-net-framework-4-6-2-offline-installer-for-windows

The .NET has also security vulnerabilities regarding how to handle web requests.


File source (download):
http://dmeforensics.com/getlatest 



The software has a long list of GUID in use, that may allow a privilege escalation. For example:
724EF170-A42D-4FEF-9F26-B60E846FBA4F


Additional References:
http://dmeforensics.com/dvr-examiner/
https://www.manageengine.com/products/desktop-central/software-installation/silent_install_Microsoft-.NET-Framework-4.6.2.html
https://www.hybrid-analysis.com/sample/28886593e3b32f018241a4c0b745e564526dbb3295cb2635944e3a393f4278d4/58e12e49aac2edd93a38d961
https://www.virustotal.com/gui/file/28886593e3b32f018241a4c0b745e564526dbb3295cb2635944e3a393f4278d4/detection
https://www.dell.com/support/home/ca/en/cabsdt1/drivers/driversdetails?driverid=t7d7y
https://nvd.nist.gov/vuln/detail/CVE-2017-8759
https://www.virustotal.com/gui/file/c5562354bf52949488b967ff889fe6bbc8545fc79f759f62bdb6626c1363adb9/details
https://gist.github.com/davehull/50c09b5160dfceb5bb13

