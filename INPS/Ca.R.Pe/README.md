# Andrew's `PDQ Deploy Script`

**Hey, there!**
**I’m Andrew and I'm passionate about PDQ inventory and Deploy and I want to share my scripts that I use every day at work.**

# Description
This package includes the deployment of Ca.R.Pe of [INPS](https://it.wikipedia.org/wiki/Istituto_nazionale_della_previdenza_sociale) (Istituto Nazionale della Previdenza Sociale) is Italy's main social security and welfare institution.
- Download the file from the [INPS](https://www.inps.it/it/it/software/dettaglio-software.software.2022.10.611.software-carpe-pc-ca-r-pe---software-per-il-calcolo-della-retribuzione-media-pensionabile-ed-ipotesi-di-rata-pensione.html) site you must rename to ca-70408.exe and save in the inps folder of the PDQ Deploy program repository ( $(Repository)\Inps\ca-70408.exe )
- If you want install the program in Windows 11, download the Cobol RunTime file RTE-NE51.exe and save in the inps folder of the PDQ Deploy program repository ( $(Repository)\Inps\RTE-NE51.exe )

# List of step
1. Install Ca.R.Pe in folder c:\svabi\
2. Install Cobol RunTime in folder c:\rte-ne51 (only if OS is Windows 11)
3. Copy file from folder c:\rte-ne51 to to c:\svabi\files (only if OS is Windows 11)

> :warning: Be aware, products can change over time. I do my best to keep up with the latest changes and releases, but please understand that this won’t always be the case.