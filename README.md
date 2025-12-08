# AEM / EDS Demo


## Environments
- Preview: https://main--aem-eds-demo--kslg.aem.page/
- Live: Live: https://main--aem-eds-demo--kslg.aem.live/

## Admin Tools

https://tools.aem.live/bot/setup?user=kslg257%40gmail.com&site=aem-eds-demo&url=https%3A%2F%2Fcontent.da.live%2Fkslg%2Faem-eds-demo%2F&org=kslg

## Documentation

Before using the aem-boilerplate, we recommand you to go through the documentation on https://www.aem.live/docs/ and more specifically:
1. [Developer Tutorial](https://www.aem.live/developer/tutorial)
2. [The Anatomy of a Project](https://www.aem.live/developer/anatomy-of-a-project)
3. [Web Performance](https://www.aem.live/developer/keeping-it-100)
4. [Markup, Sections, Blocks, and Auto Blocking](https://www.aem.live/developer/markup-sections-blocks)

## Resources

1. [AEM Discord](https://discord.com/channels/1131492224371277874/@home)
2. [AEM Sidekick](https://www.aem.live/docs/sidekick)


## Installation

```sh
npm i
```

## Linting

```sh
npm run lint
```

## Local development

1. Create a new repository based on the `aem-boilerplate` template
1. Add the [AEM Code Sync GitHub App](https://github.com/apps/aem-code-sync) to the repository
1. Install the [AEM CLI](https://github.com/adobe/helix-cli): `npm install -g @adobe/aem-cli`
1. Start AEM Proxy: `aem up` (opens your browser at `http://localhost:3000`)
1. Open the `{repo}` directory in your favorite IDE and start coding :)
