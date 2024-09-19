Windows Defender for endpoints

# Windows


**Windows** 10 et 11 sont pris en charge par defender. 

Defender ne prend pas en charge les quelques 110 machines réparties entre Windows Server 2003 et Windows Server 2008. 

# Linux

Prend en charge Linux via une installation par le gestionnaire du système, à l'exception de CentOS qui ne peut pas passer par là. 

Pour une *Distributions de serveur Linux et versions x64 (AMD64/EM64T) et x86_64 prise en charge :*

Tout est bon pour **Red Hat Enterprise**, mais il faudra demander au client la version précise de CentOS : Defender s'occupe de 6.7 et ultérieur et 7.2 et ultérieur. Defender n'a **pas** de compatibilité pour CentOS.

Il faudra demander au client la version précise de leur **Almalinux** 8.x et 9.x ; Defender est compatible avec 8.4 et ultérieur ainsi que 9.2 et ultérieur.

Les version **Oracle Linux** 5 & 6 ne sont pas compatibles avec Defender, et il faudra demander au client les version pour Oracle 7.x ; Defender n'est compatible qu'avec 7.2 et ultérieur.

Tout est ok pour les version d'**Ubuntu** 

Defender prend en charge **Debian** des version 9 à 12 ; Le client a quelques machines 6 et 8. 


# MacOS

Defender prend en charge les 3 dernières version majeures : 12 à 14. Tout est ok. 


# Android


Defender prend en charge les version 8.0 et ultérieures de Android. Hardis n'a pas fourni ces informations.
Il faut aussi que l'application Intune soit installée sur les appareils.


# IOS

Defender prend en charge les appareils IOS dont les versions sont 15.0 et ultérieur. 
Il possède aussi l'application Intune.







| **Operating System**                                                                                                                      | Windows 10 & 11                                                                      | Windows Server 2012 R2,<br>2016,<br>2019 & 2022,<br>1803+                                | macOS                                                                                    | Linux                                                                                    |
| ----------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| **Prevention**                                                                                                                            |                                                                                      |                                                                                          |                                                                                          |                                                                                          |
| [Attack Surface Reduction](https://learn.microsoft.com/en-us/defender-endpoint/attack-surface-reduction)                                  | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![No](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-no.svg)        | ![No](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-no.svg)        |
| Device Control                                                                                                                            | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![No](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-no.svg)        | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![No](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-no.svg)        |
| [Firewall](https://learn.microsoft.com/en-us/defender-endpoint/host-firewall-reporting)                                                   | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![No](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-no.svg)        | ![No](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-no.svg)        |
| [Network Protection](https://learn.microsoft.com/en-us/defender-endpoint/network-protection)                                              | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) [2] |
| [Next-generation protection](https://learn.microsoft.com/en-us/defender-endpoint/next-generation-protection)                              | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     |
| [Tamper Protection](https://learn.microsoft.com/en-us/defender-endpoint/prevent-changes-to-security-settings-with-tamper-protection)      | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![No](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-no.svg)        |
| [Web Protection](https://learn.microsoft.com/en-us/defender-endpoint/web-protection-overview)                                             | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     |
|                                                                                                                                           |                                                                                      |                                                                                          |                                                                                          |                                                                                          |
| **Detection**                                                                                                                             |                                                                                      |                                                                                          |                                                                                          |                                                                                          |
| [Advanced Hunting](https://learn.microsoft.com/en-us/defender-xdr/advanced-hunting-overview)                                              | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     |
| [Custom file indicators](https://learn.microsoft.com/en-us/defender-endpoint/indicator-file)                                              | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     |
| [Custom network indicators](https://learn.microsoft.com/en-us/defender-endpoint/indicator-ip-domain)                                      | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) [2] |
| [EDR Block](https://learn.microsoft.com/en-us/defender-endpoint/edr-in-block-mode)                                                        | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![No](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-no.svg)        | ![No](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-no.svg)        |
| [Passive Mode](https://learn.microsoft.com/en-us/defender-endpoint/microsoft-defender-antivirus-compatibility)                            | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     |
| Sense detection sensor                                                                                                                    | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     |
| Endpoint & network device discovery                                                                                                       | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) [5] | ![No](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-no.svg)        | ![No](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-no.svg)        |
| [Vulnerability management](https://learn.microsoft.com/en-us/defender-vulnerability-management/defender-vulnerability-management)         | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     |
|                                                                                                                                           |                                                                                      |                                                                                          |                                                                                          |                                                                                          |
| **Response**                                                                                                                              |                                                                                      |                                                                                          |                                                                                          |                                                                                          |
| [Automated Investigation & Response (AIR)](https://learn.microsoft.com/en-us/defender-endpoint/automated-investigations)                  | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![No](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-no.svg)        | ![No](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-no.svg)        |
| [Device response capabilities: collect investigation package](https://learn.microsoft.com/en-us/defender-endpoint/respond-machine-alerts) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) [3] | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) [3] |
| [Device response capabilities: run antivirus scan](https://learn.microsoft.com/en-us/defender-endpoint/respond-machine-alerts)            | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     |
| [Device isolation](https://learn.microsoft.com/en-us/defender-endpoint/respond-machine-alerts)                                            | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     |
| File response capabilities: collect file, deep analysis, block file, stop, and quarantine processes                                       | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg) | ![Yes.](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-yes.svg)     | ![No](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-no.svg)        | ![No](https://learn.microsoft.com/en-us/defender-endpoint/media/svg/check-no.svg)        |
| [Live Response](https://learn.microsoft.com/en-us/defender-endpoint/live-response)                                                        |                                                                                      |                                                                                          |                                                                                          |                                                                                          |


