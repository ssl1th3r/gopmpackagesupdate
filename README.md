# GoPM - Go Package Manager for Linux

**GoPM** is a lightweight and easy-to-use package manager for Linux, written in Go.  
It supports installing standalone binaries package.  
Provides detailed output, progress bars, and automatic installation of CLI binaries.

---

## / Features /

- Install packages directly from GitHub
- Supports `.tar.gz` packages and plain binaries
- Automatic installation of binaries to `/usr/local/bin/`
- Self-update feature for GoPM
- Detailed action logs with color-coded messages
- Download progress bar
- Simple configuration
- Linux only (Windows not supported)

---

## / Installing GoPM /

1. Clone the repository or download the source:

```bash
git clone https://github.com/ssl1th3r/gopm.git
cd gopm
go build -o gopm main.go
