# Thesis

This repository contains the source code and documentation for my undergraduate thesis project at the University of Trento on computer science.

## Development

### Requirements

| **Name**   | **Homepage**                  |
| ---------- | ----------------------------- |
| `Node.js`  | <https://nodejs.org>          |
| `npm`      | <https://www.npmjs.com>       |
| `TeX Live` | <https://www.tug.org/texlive> |

### Preparation

1. Clone

   ```sh
   git clone https://github.com/GabrieleBocchi/LT-thesis.git
   cd LT-thesis
   ```

2. Install Dependencies

   ```sh
   npm ci
   ```

### Build

```sh
npm run build
```

### Scripts

> **Note**: Execute with `npm run <NAME>`

| **Name** | **Description**  |
| -------- | ---------------- |
| `build`  | Build PDF        |
| `check`  | Check for errors |
| `clean`  | Clean            |
| `fix`    | Fix errors       |

## License

This project is licensed under the [MIT](https://opensource.org/licenses/MIT) license \
See [LICENSE](./LICENSE) file for details
