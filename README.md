# cyan-cloud

This repository contains the code for first major release of [totaldecoy.net](https://totaldecoy.net). To clone this repository to your local machine, run the following commands from the terminal:


```sh
git clone https://github.com/evilguyyyy/cyan-cloud.git
cd cyan-cloud
npm install
```

## Project Structure

This project contains the following folders and files:

```text
/
├── public/
│   ├── favicon.svg
│   └── power.svg
├── src/
│   ├── assets/
│   │   └── astro.svg
│   ├── components/
│   │   └── Welcome.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

## Commands

All commands run from the project root:

| Command           | Action                                  |
| :---------------- | :-------------------------------------- |
| `npm install`     | Install dependencies                    |
| `npm run dev`     | Start local dev server (localhost:4321) |
| `npm run build`   | Build production site to `./dist/`      |
| `npm run preview` | Preview production build locally        |

## Notes

- Astro version: ^6.4.7 (see `package.json`)
- Node engine: >=22.12.0
- Assets: the `public/` folder contains `power.svg` and favicons used by the site.
- Main page: `src/pages/index.astro` contains the primary content.

## Contributing

Contributions and issues are welcome. Please open a PR or issue and include a short description of changes.

## License

This project is MIT licensed. See LICENSE.md for more information.

## Learn more

Astro docs: https://docs.astro.build