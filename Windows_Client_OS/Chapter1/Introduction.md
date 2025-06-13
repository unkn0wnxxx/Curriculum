# Introduction for WIndows 10 Editions

### Differences between Home, Pro, Enterprise and Education Editions

- Home doesn't have BitLocker, Remote Desktop hosting and Group Policy functions
- Pro adds BitLocker, Remote Desktop, Hyper-V, Group Policy and Windows Update for Business.
- Enterprise includes all Pro features plus advanced security AppLocker, Credential Guard and management tools, LTS, DirectAccess
- Education is like Enterprise but for schools, with some Cortana restrictions and no LTSD by default.
- Enterprise and Education require volume licensing, while Home and Pro are sold individually.


BitLocker = encrypts drive --> if stolen with key to unlock it 
LTSC = Long-Term Servicing Channel --> For systems that need long-term stability e.G Medical Devices, ATMs, Industrial Machines
--> No feature updates, only security patches

### System Requirements and Compatibility

- Secure Boot & TPM 2.0, should be installed for good security.

Secure Boot allows you to boot the computer only with windows installed files, so potential malware cannot be executed.


Trusted Platform Module is an hardware based chip which offers various security functionalities 

as like --> Allowing generation of assymetric keys
 	--> Secure passwords & encryption keys (e.G BitLocker Key)

###### UEFI vs Legacy BIOS: Key Differences

- UEFI allows navigation with the mouse and keyboard, while Legacy Bios only allows navigation via 
- Legacy BIOS also lacks important security functionalities --> like Secure Boot
- UEFI offers graphical interfaces GUI's and Legacy BIOS only offers text based interfaces.



