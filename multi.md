---
layout: page
title: Multi-Stream
tags: [Forbidden Knowledge]
comments: false
---

<h2>How to Multi-Stream on OBS, courtesy of our comrade <a href="https://neuroriot.net/">Neuroriot</a></h2>

First determine what version of OBS you have installed. This should be in the top left corner of the window. Download the correct plugin for your OBS Version
* <a href="https://github.com/sorayuki/obs-multi-rtmp/releases/">Github obs-multi-rtmp releases page</a>
* <a href="https://github.com/sorayuki/obs-multi-rtmp/releases/download/0.7.3.2/obs-multi-rtmp-0.7.3.0-windows-x64-Installer.exe">OBS 32 Windows exe Download</a>
* <a href="https://github.com/sorayuki/obs-multi-rtmp/releases/download/0.6.0.1-obs31/obs-multi-rtmp-0.6.0.1-windows-x64-Installer.exe">OBS 31 Windows exe Download</a>
* <a href="https://github.com/sorayuki/obs-multi-rtmp/releases/download/0.6.0.1/obs-multi-rtmp-0.6.0.0-windows-x64-Installer.exe">OBS 30 Windows exe Download</a>
* If later you decide to upgrade to a newer version of OBS, you will need to uninstall the old version of the plugin and install the new one - your settings will transfer over

Ensure OBS is not running, then run the exe to install. (or complete another installation method)

After install, open OBS. Then go to Docks -> Multiple output
![OBS Docks Screenshot](https://streetcatlove.github.io/hellostreetcat/assets/img/docks.png){: .mx-auto.d-block :}

This window will open, click on Add new target. Another window will open, Streaming Settings.
![OBS Outputs Screenshot](https://streetcatlove.github.io/hellostreetcat/assets/img/outputs.png){: .mx-auto.d-block :}

For example, let's add a Kick target output. Go to Kick, then your account Settings. There's a tab there, Stream URL and Key, and it has the information we need.
![Kick Screenshot](https://streetcatlove.github.io/hellostreetcat/assets/img/kick.png){: .mx-auto.d-block :}

Copy Stream URL to the URL textbox in the Streaming Settings window. Likewise with Stream Key.
![OBS Settings Screenshot](https://streetcatlove.github.io/hellostreetcat/assets/img/settings.png){: .mx-auto.d-block :}

Go to the tab Output and check both New Socket Loop & Low Latency Mode
![OBS Output Screenshot](https://streetcatlove.github.io/hellostreetcat/assets/img/output.png){: .mx-auto.d-block :}

We reccomend to sync start with OBS & Sync stop with OBS. Do this by checking the boxes, then press OK.

If you didn't check Sync start with OBS, then after you've started streaming go to the Multiple output window and press Start.

You're done, enjoy multi-streaming!
