# playgta5 Source Code
This code is grabbed from playgta5.com before it got took down. You can run this locally or make it public hehe.

# Credits
Shoutout to Sebas Furbastian on Telegram for scrapping this code using codex.

Telegram: @SebasKitten

X: @Sebas_Kitten

# Disclaimer
I don't host the `.\mirror` folder since it has copyrighted content from Rockstar Games. Please find the files by yourself.
No copyrighted file is included in this repo. If Rockstar Games or any affiliated group think this repo has copyright infringement things, Kindly email me at hirushiru3@gmail.com for me to took it down.

# How to use
1. Download the ZIP or just `git clone` it. It should have all this file and folders.
<p align="center">
  <img src="media/Screenshot 2026-10-07 172103.png" alt="playgta5 SC">
</p>

2. Paste your `.mirror` folder at your desired path. (It should have 19.7 GB of file size. Check the pic below.)
<p align="center">
  <img src="media/Screenshot 2026-10-07 172216.png" alt="Folder Properties">
</p>
<p align="center">
  <img src="media/Screenshot 2026-10-07 172718.png" alt="Folder Properties">
</p>
<p align="center">
  <img src="media/Screenshot 2026-10-07 172758.png" alt="Folder Properties">
</p>

3. For Localhost:
Run the `Launch-Local.cmd` and it will automatically open the URL at `http://localhost:8000/`.

5. For LAN :
### Client browser setting for LAN HTTP

WebGPU and shared-memory WebAssembly require a secure browser context.
On each client PC, open:

- Chrome: `chrome://flags/#unsafely-treat-insecure-origin-as-secure`
- Edge: `edge://flags/#unsafely-treat-insecure-origin-as-secure`

Add the exact server origin, e.g. `http://192.168.1.100:8080`, enable the setting,
and restart the browser. A trusted HTTPS setup is the alternative. This setting
is unnecessary for localhost. The server supplies the required COOP/COEP headers.

6. Voila!

# Requirement
Scripts require standard-library Python 3.11 or newer. The bundled Python path
in the commands above is specific to the original PC; the portable ZIP instead
provides `runtime\python.exe` and the double-click launcher.
Completed files and `.part` transfers are retained for resumption. Final checks
cover inventory sizes, runtime hash samples, WASM signature, HTTP isolation,
range reads and both batch formats. Actual gameplay requires separate browser
validation. A public client snapshot is not the site's original development repository.

To resume with the current uncapped settings, append `--workers 32 --rate-mib 0`
to the downloader command. Content lengths from HTTP take precedence over the
source manifest when it is stale; mismatches are recorded explicitly.
