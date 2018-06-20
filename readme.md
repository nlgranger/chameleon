# Chameleon

Chameleon is a WebExtension port of the popular Firefox addon [Random Agent Spoofer](https://github.com/dillbyrne/random-agent-spoofer).

The UI is near identical and contains most of the features found in the original extension.

![chameleon screenshot](https://raw.githubusercontent.com/sereneblue/chameleon/master/screenshot.png)

## Features

### Useragents

- Randomly select from a preset list of user agents.
- Choose between different platforms or device types.
- Use a custom user agent.
- Change user agent at interval.

### Headers

- Spoof some header values.
- Modify referer options.
- Enable Do Not Track.

### Options

- Enable script injection.
- Enable tracking protection/etc.
- Disable WebSockets.
- Spoof screen size.
- Modify cookie options.
- about:config checklist to enhance your privacy.

WebExtensions are unable to modify about:config entries. A workaround for this is to use the checklists that can be found under certain menu options. Right click the option and select "Copy Link Location". Paste this link into your address bar and you'll be presented with the option in about:config.

### Whitelist

- Whitelist a profile for certain sites.

## Contribute

Feel free to send a pull request or open an issue. Keep in mind that some functionality isn't technically possible.

## Credits

<div>Icons made by <a href="http://www.freepik.com" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a></div>

dillbyrne for creating [Random Agent Spoofer](https://github.com/dillbyrne/random-agent-spoofer)