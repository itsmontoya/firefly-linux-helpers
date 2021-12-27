# Firefly Linux Helpers
## Instructions for downloading Firefly
### Download Firefly Wallet 
Download Firefly from the IOTA Foundation. Be sure to only download directly from the IOTA Foundation.
```cURL
curl https://dl.firefly.iota.org/firefly-desktop-1.3.0.AppImage -o firefly-desktop-1.3.0.AppImage
```

*Note: To get the most up to date URL, please visit https://firefly.iota.org*

### Copy icon file
Copy `firefly-256x256.png` to wherever you prefer to keep your applications. 

*Note: I keep my assets in `~/applications/assets`, but this is all personal preference*

### Create Linux Launcher file
Copy `firefly.desktop` to ~/.local/share/applications and update paths for `Exec` and `Icon`.

*Note: `Exec` will point to your `firefly-desktop-1.3.0.AppImage` and `Icon` will point to your `firefly-256x256.png`.

## TODO:
[ ] Look into ability to grab `Latest`, instead of referencing a specific version
[ ] Create install utility which follows steps set within `README.md`