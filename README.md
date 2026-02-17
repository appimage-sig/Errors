# Errors

A list of common errors encountered when running or building AppImage.

# Flutter-related issues

- [ ] Failed to initialize GLArea on linux:
  - [ ] <https://github.com/hiddify/hiddify-app/issues/1599>
  - [ ] <https://github.com/ente-io/ente/issues/7646>

# Tauri-related issues

- [ ] Could not create default EGL display: EGL_BAD_PARAMETER. Aborting...
  - [ ] <https://github.com/tiny-craft/tiny-rdm/issues/525>

Solution: <https://github.com/tauri-apps/tauri/pull/12491>

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
