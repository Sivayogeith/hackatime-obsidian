# Hackatime for Obsidian
**NOTE: This project is a fork of [obsidian-wakatime](https://github.com/wakatime/obsidian-wakatime) + custom project names and hackatime branding**

[Hackatime][hackatime] Obsidian is an open source Obsidian plugin for metrics, insights, and time tracking automatically generated from your Obsidian usage activity.

## Installation

1. Inside Obsidian, click `Settings` → `Community Plugins` → `Browse`.

2. Search for `hackatime`, click on the Hackatime plugin.

3. Click the `Install` button.

4. Click the `Enable` button.

5. Enter your [api key][api key], then press `enter`.

6. Use Obsidian and your activity will be displayed on your [Hackatime dashboard][hackatime]

## Usage

Visit [https://hackatime.hackclub.com][hackatime] to see your coding activity.

To edit your api key, open the `Command Palette` then type `Hackatime` and select the `Hackatime API Key` command.

## Troubleshooting
For general troubleshooting info, see the [wakatime-cli Troubleshooting Section][wakatime-cli help].

## Contributing

- Clone this repo.
- `npm i` or `yarn` to install dependencies
- `npm run dev` to start compilation in watch mode.

## Manually installing the plugin

- Copy over `main.js`, `styles.css`, `manifest.json` to your vault `VaultFolder/.obsidian/plugins/your-plugin-id/`.

## FAQ
#### Is this README.md AI generated?
No, it's just obsidian-wakatime's readme that I changed into hackatime-obsidian


[hackatime]: https://hackatime.hackclub.com/
[api key]: https://hackatime.hackclub.com/my/settings
[wakatime-cli help]: https://github.com/wakatime/wakatime-cli/blob/develop/TROUBLESHOOTING.md
