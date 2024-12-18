# Onyx Public Releases

This repository contains the public releases of Onyx. The releases are available in the Releases tab.
To quickly install Onyx:

For linux and macOS:

```bash
bash <(curl --proto '=https' --tlsv1.2 -sSf https://raw.githubusercontent.com/onyx-hq/onyx-public-releases/refs/heads/main/install_onyx.sh)
```

To install a certain version of onyx (not the latest version):

```bash
ONYX_VERSION="0.1.24" bash <(curl --proto '=https' --tlsv1.2 -sSf https://raw.githubusercontent.com/onyx-hq/onyx-public-releases/refs/heads/main/install_onyx.sh)
```

For windows:

```powershell
powershell -Command "& { iwr -useb https://raw.githubusercontent.com/onyx-hq/onyx-public-releases/refs/heads/main/install_onyx.ps1 | iex }"
```

Or download the latest binary releases from and copy them to a place where your PATH can reach. (i.e. /usr/local/bin)
