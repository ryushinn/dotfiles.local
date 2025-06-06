# Dotfiles.local

Install the local dotfiles for different platforms:

```bash
PLATFORM_BRANCH=ubuntu
URL=https://github.com/ryushinn/dotfiles.local
git clone "$URL" && cd dotfiles.local && git checkout "$PLATFORM_BRANCH" && ./install
```

## Platforms branches

The command line to check the Operating System: `hostnamectl`

```text
main
|
+- macos
|
+- WSL (Windows 11)
|
+- ubuntu (22.04)
|
+- arch-linux
|
+- CentOS (UCL HPC Cluster [CentOS Linux 7 (Core)])
```
