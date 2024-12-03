## Excali Studio
Excalistudio is a project aiming to build a self-hosted alternative to Excalidraw, using the original open-source Excalidraw editor. The project consists of a backend service, a frontend app built with React, and supports the Excali-room service for live collaboration features. If you think our project is worth noting, please consider leaving a star or contributing to its development.


### How to run?
If you want to run whole application you will need to start all three apps: 
- [Excalistudio API](https://github.com/Excali-Studio/excali-api)
- [Excalistudio Frontend](https://github.com/Excali-Studio/excali-front-wrapper)
- [Excalistudio Room](https://github.com/Excali-Studio/excalidraw-room)

1. Setup postgres database (for example in docker),
2. Clone [Excalistudio Frontend](https://github.com/Excali-Studio/excali-front-wrapper), install dependencies, configure your `.env` from `.env.example` and run `pnpm run dev`.
3. Clone [Excalistudio API](https://github.com/Excali-Studio/excali-api), install dependencies, configure your `.env` from `.env.example` and run `pnpm run start:dev`. For more complex tutorial check readme in api repository.
4. Clone [Excalistudio Room](https://github.com/Excali-Studio/excalidraw-room), install dependencies, run `pnpm run start:dev`.


__Currently maintained with ❤️ by SilkSH__
<img src="../docs_static/silksh_logo.png" width="50">
