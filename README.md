# Single Pane of Glass AD Lookup Toolkit — releases

The two files browsers need to install and update the extension. Served with GitHub Pages at
https://aio-toolkit.github.io/ad-lookup-releases/

| File | What it is |
|---|---|
| `update.xml` | The address Edge and Chrome check for new versions |
| `single-pane-of-glass-ad-lookup.crx` | The signed extension |

The source code and the PC helper are kept privately and deployed through Intune.

Intune value (Edge "Control which extensions are installed silently" and Chrome "Configure the list of force-installed apps and extensions"):

```
bgognegigfjkjiajdgdkkpfgjcfplfgl;https://aio-toolkit.github.io/ad-lookup-releases/update.xml
```

## AIO M365 Admin Tool

| File | What it is |
|---|---|
| `admin/update.xml` | The address Edge and Chrome check for new versions |
| `admin/aio-m365-admin-tool.crx` | The signed extension |

Intune value (same two settings, assigned to the M365 admins group):

```
jdnhhogiboinpkmlelgcgbhbmgfnbjpk;https://aio-toolkit.github.io/ad-lookup-releases/admin/update.xml
```

