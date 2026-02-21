# Errors

A list of common errors encountered when running or building AppImage.

# Flutter-related issues

- [ ] Failed to initialize GLArea on linux:
  - [ ] <https://github.com/hiddify/hiddify-app/issues/1599>
  - [ ] <https://github.com/ente-io/ente/issues/7646>

# Tauri-related issues

- [ ] Could not create default EGL display: EGL_BAD_PARAMETER. Aborting...
  - [ ] <https://github.com/tiny-craft/tiny-rdm/issues/525>
  - [ ] <https://github.com/gitbutlerapp/gitbutler/issues/11945>
  - [ ] <https://github.com/nab138/iloader/issues/77>
  - [ ] <https://github.com/shadps4-emu/shadPS4-launcher/issues/39>
  - [ ] <https://github.com/decentpaste/decentpaste/issues/21>

Proof-of-concept: <https://github.com/tauri-apps/tauri/pull/12491>
Work in action: <https://github.com/readest/readest/pull/2985>

Working apps (tested on Fedora 44, GNOME 50: wireguard-gui, Handy) uses next deps: 

```shell
libappindicator3-dev
librsvg2-dev
patchelf
libwebkit2gtk-4.1-0=2.44.0-2 \
libwebkit2gtk-4.1-dev=2.44.0-2 \
libjavascriptcoregtk-4.1-0=2.44.0-2 \
libjavascriptcoregtk-4.1-dev=2.44.0-2 \
gir1.2-javascriptcoregtk-4.1=2.44.0-2 \
gir1.2-webkit2-4.1=2.44.0-2
```

# Electron-related issues
