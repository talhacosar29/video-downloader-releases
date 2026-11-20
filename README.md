# Video Downloader — downloads

Installers for the Video Downloader desktop app. The source code is kept in a separate private
repository; this repository only holds the built installers under [Releases](../../releases).

## Install

- **macOS (Apple Silicon):** open the `.dmg` and drag *Video Downloader* into *Applications*.
- **Windows (x64):** run the `-setup.exe` installer.

Each release lists the exact version. Older versions remain available on the Releases page.

## Licenses of bundled tools

The app bundles third-party command-line tools. Their licenses apply to those tools:

| Tool | License | Source |
| --- | --- | --- |
| FFmpeg (ffmpeg, ffprobe) | GPL (built with GPL components) | https://ffmpeg.org/download.html |
| Ghostscript | AGPL-3.0 | https://ghostscript.com/releases/ |
| yt-dlp | The Unlicense | https://github.com/yt-dlp/yt-dlp |
| pandoc | GPL-2.0-or-later | https://github.com/jgm/pandoc |
| qpdf | Apache-2.0 | https://github.com/qpdf/qpdf |
| Poppler (pdftoppm, pdftotext) | GPL-2.0-or-later | https://poppler.freedesktop.org/ |
| potrace | GPL-2.0-or-later | https://potrace.sourceforge.net/ |
| LibreDWG (dwg2dxf) | GPL-3.0-or-later | https://www.gnu.org/software/libredwg/ |
| yq | MIT | https://github.com/mikefarah/yq |

Source code for the GPL and AGPL components is available from the links above. Copies of the
upstream license texts are available from the same projects.

The application's own source code is not included in this repository.
