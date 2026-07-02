# SC File Renamer 🎬
SC File Renamer is a modern, blazing-fast, open-source desktop application designed to elegantly organize and rename your messy media files. Built with React, TypeScript, Vite, and Electron, it serves as a lightweight yet incredibly powerful alternative to traditional file batch renamers.
## Features ✨
- **Smart Media Matching**: Automatically matches your movie and TV show files against the TMDB database to pull accurate titles, season, and episode metadata.
- **Cross-Platform & Native**: Beautiful, native-feeling desktop experience with zero bloat, powered by Electron.
- **Advanced Subtitle Search**: Built-in, ad-free subtitle workspaces (OpenSubtitles, SubDL, Addic7ed, YifySubtitles, etc.) featuring an enterprise-grade network interceptor that blocks popups and malicious redirects before they even load.
- **SFV & Checksum Workspace**: Generate and verify `CRC32`, `MD5`, `SHA1`, and `SHA256` hashes for large media files using a fully non-blocking native streaming backend.
- **Smart Upgrades**: When moving files across drives or overwriting old files, the app intelligently checks file sizes to only replace files if the incoming file is a higher-quality upgrade.
- **Live Preview & History**: Instantly preview your renamed files before committing, and rollback entire batches of renames using the persistent history log.
- **Cross-Drive Progress Tracking**: Deep OS-level integration pipes chunk-by-chunk copy progress directly to the UI when transferring massive files across physical drives.
## Tech Stack 🛠️
- **Frontend**: React 18, TypeScript, TailwindCSS, Lucide Icons
- **Backend/Desktop**: Electron, Node.js (IPC Streaming)
- **Bundler**: Vite, electron-builder
- **Security**: @ghostery/adblocker-electron (Native Network Interception)
## Installation & Setup 🚀
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/sc-file-renamer.git
   cd sc-file-renamer
   ```
2. **Install dependencies**
   ```bash
   npm install
   ```
3. **Run the development server**
   ```bash
   npm run dev
   ```
4. **Build the production executable**
   ```bash
   npm run build
   ```
   *The `.exe` installer will be output to the `dist-release` directory.*
## License 📄
This project is licensed under the MIT License.

<a href="https://www.producthunt.com/products/sc-file-renamer?embed=true&amp;utm_source=badge-featured&amp;utm_medium=badge&amp;utm_campaign=badge-sc-file-renamer" target="_blank" rel="noopener noreferrer"><img alt="SC File Renamer - Organize and rename messy media files instantly. | Product Hunt" width="250" height="54" src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=1185667&amp;theme=dark&amp;t=1782977378999"></a>
