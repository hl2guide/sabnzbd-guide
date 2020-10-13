# Guide for sabnzbd

This guide contains useful tips for sabnzbd that you may or may not know already.

Most tips are extra steps that improve security or usability.

## Preparation

To download sabnzbd visit: https://www.sabnzbd.org

Before using this guide ensure that you have:
1. **sabnzbd** installed and running on a local PC, e.g: https://127.0.0.1:9090/sabnzbd/
2. If you use an adblocker in your browser, whitelist https://127.0.0.1:9090/sabnzbd/
3. Open the web interface in a browser
4. Pause the queue by pressing the pause button in the top left
5. Access the **sabnzbd** config by pressing the cog wheel icon in the top right
6. Click the **General** tab at the top
7. Check the **Advanced Settings** checkbox to the top right

Please Note: Changes I recommend often require sabnzbd to restart (fast and simple).

Click the "Save Changes" button after each section in the interface.

## General Tab

### SABnzbd Host

Set it to: 0.0.0.0

Meaning "this PC".

### Web interface

Choose "Glitter - Night" if you like darker interfaces.

### SABnzbd Username

Set it to a unique name that you remember (avoid "admin" or similar).

### SABnzbd Password

Set it to a complex password and record it and the username in a password manager (like LastPass) or similar.

### Maximum line speed

Set this to the very maximum speed your internet can download files (test using https://www.speedtest.net or similar).

Doing this allows for speed limiting to become an option.

## Folders Tab

### Temporary Download Folder, Completed Download Folder and Watched Folder

Set all three to your largest disk volume that is fast and large enough for file storage.

### Watched Folder Scan Speed

Set to: 2

### .nzb Backup Folder

Set it to a folder, preferrably cloud synced.

## Switches Tab

### Check before download

Tick this checkbox if you prefer a basic availability test to be done before each download is attempted.

(Increases the download time, I leave it unchecked)

### Unwanted extensions

Setting this option helps avoid any potential viruses, malware etc on usenet.

Set this to a list of file types you never want to download on purpose. I recommend:

` bat, cmd, com, db, dll, doc, docm, docx, exe, gif, hta, htm, html, idx, inf, info, ini, jar, js, jse, lnk, md5, nfo, nzb, pdf, png, ps1, ps2, py, scf, scr, sfv, sfx, srr, sub, tmp, txt, url, vb, vbe, vbs, jpg, jpeg `

### Direct Unpack

Tick this checkbox to improve unpack times.

### Ignore Samples

Tick this checkbox to ignore sample files.

### Cleanup List

Set this to a list of file types you want to remove after a download completes. I recommend:

` bat, cmd, com, db, dll, doc, docm, docx, exe, gif, hta, htm, html, idx, inf, info, ini, jar, js, jse, lnk, md5, nfo, nzb, pdf, png, ps1, ps2, py, scf, scr, sfv, sfx, srr, sub, tmp, txt, url, vb, vbe, vbs, jpg, jpeg `

## Scheduling Tab

You can schedule actions for sabnzbd on this tab.




Thanks for reading 😁
