[![Built with Starlight](https://astro.badg.es/v2/built-with-starlight/tiny.svg)](https://starlight.astro.build)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![renovate](https://img.shields.io/badge/maintaied%20with-renovate-blue?logo=renovatebot)](https://app.renovatebot.com/dashboard)
[![GitHub last commit (branch)](https://img.shields.io/github/last-commit/2rabs/nito-docs)](https://github.com/2rabs/nito-docs/commits/main/)
[![Discord](https://img.shields.io/discord/1183966017987301406?logo=discord&color=blue)](https://discord.gg/jzkHZu6Hxv)

# nito-docs

NITO's documentation site.

## Features

TBD

### Screenshots

TBD

## Get Started

After git clone, run the following command

```shell
$ make bs
```

What is being processed by bootstrap is shown below.

- Configuring git commit message templates
- Installation of various tools by mise
- Installation of dependencies by bun
- Installation of husky by bun

### Add template

You can generate code from a template using plop by executing the following command.

```shell
$ bun plop
```

## Development Environment

TBD

## Project Structure

Inside of your Astro + Starlight project, you'll see the following folders and files:

```
.
├── public/
├── src/
│   ├── assets/
│   ├── content/
│   │   ├── docs/
│   │   └── config.ts
│   └── env.d.ts
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

Starlight looks for `.md` or `.mdx` files in the `src/content/docs/` directory. Each file is exposed as a route based on its file name.

Images can be added to `src/assets/` and embedded in Markdown with a relative link.

Static assets, like favicons, can be placed in the `public/` directory.

## Architecture

- [Astro](https://astro.build/)
- [Starlight](https://starlight.astro.build/)

## Build

TBD

## Testing

TBD

## Performance

TBD

## Contributors

Thanks to our wonderful contributors!

<a href="https://github.com/2rabs/nito-docs/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=2rabs/nito-docs" alt="Contributors" />
</a>

## Repo Activity

![Repobeats](https://repobeats.axiom.co/api/embed/afec44d7ae1e867b6f245390f5cc3f5d2484e8b5.svg "Repobeats analytics image")

## License

nito-docs is distributed under the terms of the MIT License. See the [license](LICENSE) for more
information.
