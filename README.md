# PowerSC
Example files for testing PowerSC functionality.

These files will be used in the PowerSC Lab session (#1615) running at the IBM TechXchange Conference 2024 in Las Vegas, Nevada, USA in October 2024.

## Block listing examples
This includes some example files and a hashfile that includes the MD5 hash values for each of those example files. The hashfile can then be uploaded in the PowerSC GUI and applied as a Block list for each of the 3 Operating System types.

In each managed / monitored LPAR one or more of the example files can be downloaded ad then scanned against to show the effects of idetifying a blocked file.

- blockfile.test (text file)
- blockfile.json (JSON file)
- blockfile.sh (shell script)

## Anti-malware example
This includes an imitation virus file, based on a definition set by the [European Institute for Computer Antivirus Research (EICAR)](https://www.eicar.org/download-anti-malware-testfile/) to enable the testing of anti-malware and anti-malware products. This file itself is not dangerous, and does not pose a risk to systems. However, it will be identified as malware by appropriate tools, including the ClamAV tools monitored by PowerSC.

To use this test file, it must be downloaded, and then edited to remove the initial pair of slash marks ("//").

- virus.file (modified malware test file)
