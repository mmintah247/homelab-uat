**On mac**

**Install homebew**

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

**Install cloudflared**

```bash
brew install cloudflared
```

**Get the path of cloudflared after install**

```bash
which cloudflared
```

**mine can be found below**

```bash
/opt/homebrew/bin/cloudflared
```

**Switch to the .ssh directory in your home folder**

```
cd ~/.ssh
```

Copy the config from /vpn/cloudflare/config into [config](/vpn/cloudflare/config) and replace the example values with your own.
