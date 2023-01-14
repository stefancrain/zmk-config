# ZMK Config

This is a zmk config focused around the idea of switching branches quickly.

## How to use, with a local focus

1. Fork this repo
2. Clone the repo to your computer
3. Setup ENV for Local Building
   - `task west:init` :  Setup the build env locally, in docker
   - `task west:convert2task` : Convert ZMK build.yaml to Tasks
4. Edit the config and keymap files
5. Build all of the firmware
     - `task west:build:all`
6. Deploy changes to keyboard, test
7. Push your changes to github
8. Download the firmware from the actions tab

Alternatively, you could probably even use github's built-in editor to edit the keymap and config file after forking.

## References

- [nahz3matics/zmk-config-sofle](https://github.com/nahz3matics/zmk-config-sofle)
- [infused-kim/zmk-config](https://github.com/infused-kim/zmk-config)
