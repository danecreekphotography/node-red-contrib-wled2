# Changelog

## Unreleased

- Corrected the name of the node in package.json. Resolves [issue 42](https://github.com/danecreekphotography/node-red-contrib-wled2/issues/42).
- Disconnected state shows correctly now. Resolves [issue 41](https://github.com/danecreekphotography/node-red-contrib-wled2/issues/41).

## v1.3.1 - 2020-07-04

- Clean up an error when retrieving effects and palettes. Resolves [issue 35](https://github.com/danecreekphotography/node-red-contrib-wled2/issues/35).
- Clean up an unnecessary error when the node is first created. Resolves [issue 37](https://github.com/danecreekphotography/node-red-contrib-wled2/issues/37).

## v1.3.0 - 2020-07-04

- Effects and palettes are now properly loaded from the devices, with fallback to defaults. Resolves [issue 33](https://github.com/danecreekphotography/node-red-contrib-wled2/issues/33).
- Miscellaneous auto-discovery improvements. Resolves [issue 29](https://github.com/danecreekphotography/node-red-contrib-wled2/issues/23) and [issue 30](https://github.com/danecreekphotography/node-red-contrib-wled2/issues/23).

## v1.2.1 - 2020-07-03

- Auto-discovery now works for NodeRed installs hosted inside Home Assistant. Resolves [issue 27](https://github.com/danecreekphotography/node-red-contrib-wled2/issues/23).

## v1.2.0 - 2020-07-03

- Auto-discovery of WLED devices is now supported. Resolves [issue 23](https://github.com/danecreekphotography/node-red-contrib-wled2/issues/23).
- Node name now shows in italics if set to a custom name. Resolves [issue 20](https://github.com/danecreekphotography/node-red-contrib-wled2/issues/20).

## v1.1.0 - 2020-07-02

- Delay field is now validated to confirm it is a number. Resolves [issue 15](https://github.com/danecreekphotography/node-red-contrib-wled2/issues/16).
- A default list of effects and palettes is shown when retrieving the lists from a WLED
  device fails. Resolves
  [issue 16](https://github.com/danecreekphotography/node-red-contrib-wled2/issues/16).
