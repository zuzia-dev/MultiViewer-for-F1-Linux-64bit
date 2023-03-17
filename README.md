### MultiViewer for F1 
Program for Linux distributions based on Debian and Ubuntu.
- Source: https://multiviewer.app/

### Prerequisites
Requires a paid F1TV subscriptions.

### Installation & Usage
- `wget https://releases.multiviewer.io/download/99792816/multiviewer-for-f1_1.14.1_amd64.deb `
- `mkdir multiviewer-for-f1_1.14.1_amd64 `
- `cd multiviewer-for-f1_1.14.1_amd64 `
- `ar -x ../multiviewer-for-f1_1.14.1_amd64.deb `
- `zstd -d *.zst `
- `ar r multiviewer-for-f1_1.14.1_amd64.deb debian-binary control.tar.xz data.tar.xz `
- `sudo dpkg -i multiviewer-for-f1_1.14.1_amd64.deb `
- `apt-get update && apt-get install -f `
- `/usr/bin/multiviewer-for-f1 `
 
