# Next.js Starter Project

This is a Next.js starter project using the following stack:

- **Prettier**, **ESLint**, **commitizen**, and **Husky** for linting and code formatting
- **next-intl** for internationalization (i18n)
- **Tailwind CSS** and **Shadcn UI** for styling

## Project Structure

The repository consists of multiple branches for modular setup:

### 1. `feat-init-project-with-shadcn`

This branch includes:

- Initial setup of Next.js
- Integration of **Shadcn UI** with **Tailwind CSS**

### 2. `feat-next-intl`

This branch adds:

- **next-intl** integration for managing internationalization
- All required i18n configurations

### 3. `feat-prettier-husky`

This branch focuses on:

- Setting up **Prettier**, **ESLint**, and **Husky**
- Commit convention using **commitizen**

## Main Branch

The main branch combines all the features:

- Full integration of **Shadcn UI**, **next-intl**, and **Prettier** + **Husky**
- Ready for production or further customization.

## Getting Started

1. **Clone the repo** and switch to the desired branch:

   ```bash
   git clone <repo-url>
   cd <repo-folder>
   git checkout <branch-name>
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Run the development server:**

   ```bash
   npm run dev
   ```

4. **Build for production:**

   ```bash
   npm run build
   ```

## Contributing

- Use **commitizen** for commit messages:

  ```bash
  git add .
  npm run commit
  ```

## License

This project is licensed under the MIT License.
