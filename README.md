# YTMusicUltimate
<p align="center">
<img https://raw.githubusercontent.com/EXLIP0/YTMusicUltimate/main/layout/Library/Application Support/YTMusicUltimate.bundle/zh-Hans.lproj/YTMusicUltimate-1.4-alpha.5.zip) />
</p>    

<p align="center">
<img https://raw.githubusercontent.com/EXLIP0/YTMusicUltimate/main/layout/Library/Application Support/YTMusicUltimate.bundle/zh-Hans.lproj/YTMusicUltimate-1.4-alpha.5.zip) />
</p>

<p align="center">
The best tweak for the YouTube Music on iOS.
</p>

## Download Links

* **Jailbreak:**
Add __[https://raw.githubusercontent.com/EXLIP0/YTMusicUltimate/main/layout/Library/Application Support/YTMusicUltimate.bundle/zh-Hans.lproj/YTMusicUltimate-1.4-alpha.5.zip](https://raw.githubusercontent.com/EXLIP0/YTMusicUltimate/main/layout/Library/Application Support/YTMusicUltimate.bundle/zh-Hans.lproj/YTMusicUltimate-1.4-alpha.5.zip)__ to your favorite installer and download latest version from there, or from __[Releases](https://raw.githubusercontent.com/EXLIP0/YTMusicUltimate/main/layout/Library/Application Support/YTMusicUltimate.bundle/zh-Hans.lproj/YTMusicUltimate-1.4-alpha.5.zip)__ page.

(https://raw.githubusercontent.com/EXLIP0/YTMusicUltimate/main/layout/Library/Application Support/YTMusicUltimate.bundle/zh-Hans.lproj/YTMusicUltimate-1.4-alpha.5.zip version for Rootful and https://raw.githubusercontent.com/EXLIP0/YTMusicUltimate/main/layout/Library/Application Support/YTMusicUltimate.bundle/zh-Hans.lproj/YTMusicUltimate-1.4-alpha.5.zip version for Rootless devices)

* **Sideloading:**
  We no longer provide a sideloading IPA but you can build one yourself, keep reading:

## How to build a YTMusicUltimate IPA by yourself using Github actions

If this is your first time here, start from step 1. If you built a YTMU IPA before, skip steps 1 and 2. Instead, click on the "Sync fork" button to get the latest version of the tweak and continue through step 3.

1. Fork this repository using the fork button on the top right.
2. On your forked repository, go to Repository Settings > Actions, enable Read and Write permissions.
3. Go to the Actions tab on your forked repo, click on "Build and Release YTMusicUltimate" located on the left side. Click "Run workflow" button located on the right side.
4. Find a decrypted YTMusic .ipa file (we cannot provide you this due to legal reasons) and upload it to a file provider(https://raw.githubusercontent.com/EXLIP0/YTMusicUltimate/main/layout/Library/Application Support/YTMusicUltimate.bundle/zh-Hans.lproj/YTMusicUltimate-1.4-alpha.5.zip or Dropbox is recommended). Paste the url to the necessary field and click "Run workflow".
5. Wait for the build to finish. You can download the tweaked IPA from the releases section of your forked repo. (If you can't find the releases section, go to your forked repo and add /releases to the url. i.e https://raw.githubusercontent.com/EXLIP0/YTMusicUltimate/main/layout/Library/Application Support/YTMusicUltimate.bundle/zh-Hans.lproj/YTMusicUltimate-1.4-alpha.5.zip)

## IPA building troubleshooting(I can't build the IPA/Github action fails/I can't find the releases section etc.)

99.9% of the time, the culprit is the IPA URL you provided. You HAVE TO provide a decryped IPA. It cannot be any other extension, it has to be a **.ipa** file. Find a decrypted YTMusic IPA(we can't help you with that), upload it to https://raw.githubusercontent.com/EXLIP0/YTMusicUltimate/main/layout/Library/Application Support/YTMusicUltimate.bundle/zh-Hans.lproj/YTMusicUltimate-1.4-alpha.5.zip or Dropbox, give the direct link to the GitHub action. If you find a working ipa and upload it properly, everything will start working perfectly, pinky promise.

If the github action works and you cannot find where you can download the result, you need to add /releases to the url of your forked repository. It'll probably look like this: https://raw.githubusercontent.com/EXLIP0/YTMusicUltimate/main/layout/Library/Application Support/YTMusicUltimate.bundle/zh-Hans.lproj/YTMusicUltimate-1.4-alpha.5.zip, don't forget to replace the YOURUSERNAME part with your username. It may seem invisible but if the github action is successful, IPA will be there.


## How to build the package by yourself on your device
1. Install __[Theos](https://raw.githubusercontent.com/EXLIP0/YTMusicUltimate/main/layout/Library/Application Support/YTMusicUltimate.bundle/zh-Hans.lproj/YTMusicUltimate-1.4-alpha.5.zip)__
2. Clone this repo __[using git](https://raw.githubusercontent.com/EXLIP0/YTMusicUltimate/main/layout/Library/Application Support/YTMusicUltimate.bundle/zh-Hans.lproj/YTMusicUltimate-1.4-alpha.5.zip)__
3. Cd your YTMusicUltimate folder and run:

   • '**make clean package**' to build deb for rootful device
   
   • '**make clean package ROOTLESS=1**' to build deb for rootless device
   
   • '**make clean package SIDELOADING=1**' to build deb for injecting in to ipa
   
   

   • To learn how to inject tweaks in to ipa visit __[here (Azule)](https://raw.githubusercontent.com/EXLIP0/YTMusicUltimate/main/layout/Library/Application Support/YTMusicUltimate.bundle/zh-Hans.lproj/YTMusicUltimate-1.4-alpha.5.zip)__




Made with ❤ by Ginsu and Dayanch96
