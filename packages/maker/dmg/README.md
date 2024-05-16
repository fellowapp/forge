# Fork info
This is a fork of the original `@electron-forge/maker-dmg` package.
The original has a bug https://github.com/electron/forge/issues/3517

It should be added to your package.json like so:
```json
    "@electron-forge/maker-dmg": "https://registry.npmjs.org/@fellow/maker-dmg/-/maker-dmg-7.4.0.tgz",
```

## maker-dmg

`@electron-forge/maker-dmg` builds `.dmg` files, which are the standard format for sharing macOS apps. You can only build the DMG target on macOS machines.

Configuration options are documented in [`MakerDMGConfig`](https://js.electronforge.io/interfaces/_electron_forge_maker_dmg.MakerDMGConfig.html).

```javascript
{
  name: '@electron-forge/maker-dmg',
  config: {
    background: './assets/dmg-background.png',
    format: 'ULFO'
  }
}
```
