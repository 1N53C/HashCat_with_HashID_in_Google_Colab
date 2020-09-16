# ColabCat With HashID And Rules
Run Hashcat in Google Colab with built-in Hashid and OneRuleToRuleThemAll

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1yil_iLncAjg0waS3dB5C5Q_GjdH6Nfo1?usp=sharing)

## Credits
1. This Repo and the Google Colab is based on the work of Somesh Kar. Somesh was a great inspiration. You can find his repo here: https://github.com/someshkar/colabcat

2. Credits to Daniel Miessler and his SecLists Repo: https://github.com/danielmiessler/SecLists

3. Credits to Stealthsploit for the OneRuleToRuleThemAll: https://github.com/stealthsploit/Optimised-hashcat-Rule

## Prerequisites
1. Go to your Google Drive http://drive.google.com
2. Create a folder named _**hashcat**_.
3. Create a subfolder within named _**hashes**_.
4. Store your hash in the _**hashes**_ subfolder and name it _**hash**_ without file extension.

![File Structure](https://raw.githubusercontent.com/1N53C/ColabCatWithHashIDandRules/master/GoogleDriveHash.png)

## Instructions
1. Simply open https://colab.research.google.com/drive/1yil_iLncAjg0waS3dB5C5Q_GjdH6Nfo1?usp=sharing
2. Make sure the _**Hardware Accelerator**_ is set to GPU. You will find this in _**Runtime -> Change Runtime Type**_.
3. Click on _**Runtime -> Run All**_.
4. In the second cell of the notepad you will be asked for authorization. Simply click on the link and follow the given instructions.
5. The script will clone and install the required parts and ask you for the Hashcat Mode in cell #4, which you will find in the output of cell #3.
6. Happy Cracking!

## Known Issues
1. For some reason the hash mode seems to be not found in the first run. In this case rerun cells #3 and #4.
