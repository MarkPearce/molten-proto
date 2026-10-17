# molten-proto

A redesign prototype of the Molten Hosting server management page, built with MUI.

Open `index.html` in a browser. React, MUI and Babel load from unpkg, so no build step is needed.

## Layout

- **Header:** server name, status, region, Foundry version and one primary button (Start server when stopped, Open Foundry when running), with the clickable invite link directly under them.
- **Server:** power, Foundry version, storage, region.
- **Files & access:** Foundry URL and admin password; FileBrowser, username, password and WebDAV host.
- **Backups:** game data export, then your backups and automatic backups in one table.
- **Settings:** Discord notifications and the danger zone.

Red is reserved for the logo and destructive actions. Amber marks the Stop button. Everything else uses neutral tones.

## License

This work is dedicated to the public domain under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/). You may copy, modify, distribute and use it for any purpose, including commercial use, without asking permission or giving credit. See [LICENSE](LICENSE) for the full text.
