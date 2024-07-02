<p align="center">
  <img src="https://raw.githubusercontent.com/exhausted-yami/OverGuild/main/logo/banner.png" alt="OverGuild Logo" />
  <a style="text-decoration:none" href="https://guilded.gg/OverGuild">
    <img src="https://img.shields.io/static/v1?label=Chat%20on&message=Guilded&style=flat-square&color=F5C400&logo=guilded&logoColor=white" alt="Chat on Guilded" />
  </a>
  <a style="text-decoration:none" href="https://github.com/exhausted-yami/OverGuild/issues">
    <img alt="Open Issues" src="https://img.shields.io/github/issues-raw/exhausted-yami/OverGuild?style=flat-square">
  </a>
  <a style="text-decoration:none" href="https://wakatime.com/badge/user/93ce9d23-40bd-42bc-8938-e94ba1d005cd/project/3b823344-d8a4-412c-8e24-45177c61480c">
    <img alt="WakaTime" src="https://wakatime.com/badge/user/93ce9d23-40bd-42bc-8938-e94ba1d005cd/project/3b823344-d8a4-412c-8e24-45177c61480c">
  </a>
  <a style="text-decoration:none" href="https://guilded.gg/OverGuild">
    <img src="https://img.shields.io/static/v1?label=Looking%20for&message=Contributors&style=flat-square&color=orange" alt="Chat on Guilded" />
  </a>
</p>

**OverGuild** is a client injector/client mod that allows you to extend the functionality of Guilded's client by providing theme and addon support.

> **NOTE:** OverGuild isn't fully stable and you may encounter some bugs and/or shortcomings. We are always looking for more contributors to help work on OverGuild.

## Installation

Currently Non Available

## Will you get banned for using OverGuild?

OverGuild is not associated with Guilded in any capacity. We have sought permission, and waiting for Guilded to confirmed that it take no/any action towards using OverGuild. 
> Note However, abusing OverGuild using plugins or any other means to violate [Guilded TOU](https://support.guilded.gg/hc/en-us/articles/360039728313-Terms-of-Use) could result in your account being banned.

**Be sure to also read [our license](https://github.com/OverGuild/OverGuild/blob/main/LICENSE).**

## Contributing

Pull requests and Issues are welcome. You may want to coordinate with us on our [Guilded Server](https://guilded.gg/OverGuild) in advance.

You can get the project's dependencies by running `npm i` in the repositories' root folder.

Steps for testing:
1. Run `npm run inject` - This will run `npm run build` and `npm run injectbare` which will automatically put the asar into the right folder.
2. There are two ways to update this asar after injecting:
   1. Running `npm run inject` - This will build, then uninject and inject.
   2. Copy the `OverGuild.asar` in the `out` directory to one of the following directories.
      1. Linux: `/user/local/share/OverGuild`
      2. Mac: `/Applications/OverGuild`
      3. Windows: `%PROGRAMFILES%/OverGuild`
3. After updating the asar file you can press CTRL/CMD + R while focused on Guilded and the changes you made will be loaded.

## Project Status

As mentioned at the top of this document, OverGuild is currently under active development and is not fully stable yet. Please leave suggestions and ideas in the Community Tab or our [Guilded Server](https://guilded.gg/OverGuild). Contributions are welcome.

## Credits

Our Patcher code is influenced by [Powercord's Patcher Code](https://github.com/powercord-org/powercord/blob/1bf24bf87b417d22851a77d1e009d25cba493818/src/patcher.js), all credit goes to them for this file.

## License

OverGuild is licensed under the [MPL 2.0](https://github.com/OverGuild/OverGuild/blob/main/LICENSE) license.
