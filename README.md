# Anjrot Components

Anjrot Components is a collection of reusable UI components built with React, TypeScript, and Tailwind CSS. This library is designed to provide a set of flexible and customizable components for modern web applications.

## YouTube Tutorial Series

This project was created as part of a YouTube tutorial series. You can follow along with the development process and learn more about building a component library by watching our series at:

[![React Typescript: Crea una libreria de Componentes](https://img.youtube.com/vi/9CU4jkxm-Ps/maxresdefault.jpg)](https://www.youtube.com/playlist?list=PLoOnCUvhzJYOk_s-NQOeWdzPaYmXZGzDj "React Typescript: Crea una libreria de Componentes")
https://youtu.be/9CU4jkxm-Ps

## Project Overview

This component library includes several key components:

- Button
- Text
- Stack

Each component is built with TypeScript and styled using Tailwind CSS, ensuring type safety and easy customization.

## Class Variance Authority

We utilize Class Variance Authority (CVA) in this project to manage component variants. CVA allows us to create flexible and type-safe component APIs, making it easier to handle multiple variants and props for our components.

## Getting Started

To use Anjrot Components in your project:

1. Install the package (once it's published):

   ```
   npm install anjrot-components
   ```

2. Import and use the components in your React application:
   ```jsx
   import { Button, Text, Stack } from "anjrot-components";
   ```

## Development

To set up the project for development:

1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```
3. Run Storybook to view and develop components:
   ```
   npm run storybook
   ```

## Building

To build the project:

```
npm run build
```

## Testing

(Add information about testing once test files are added to the project)

## Contributing

We welcome contributions to this project! We use semantic-release to manage our releases, which means we follow specific guidelines for our commit messages. This helps us automatically determine version bumps and generate changelogs.

### Commit Message Format

Each commit message should follow this format:

```
<type>[optional scope]: <description>

[optional body]

[optional footer]
```

Where `<type>` is one of the following:

- feat: A new feature
- fix: A bug fix
- docs: Documentation only changes
- style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- refactor: A code change that neither fixes a bug nor adds a feature
- perf: A code change that improves performance
- test: Adding missing tests or correcting existing tests
- chore: Changes to the build process or auxiliary tools and libraries such as documentation generation

The `<scope>` is optional and can be anything specifying the place of the commit change.

The `<subject>` is a short description of the change.

The `<body>` is optional and should include the motivation for the change and contrast this with previous behavior.

The `<footer>` is optional and should contain any information about Breaking Changes and is also the place to reference GitHub issues that this commit closes.

For example:

```
feat(Button): add primary variant
```

### Pull Request Process

1. Ensure any install or build dependencies are removed before the end of the layer when doing a build.
2. Update the README.md with details of changes to the interface, this includes new environment variables, exposed ports, useful file locations and container parameters.
3. You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

## Acknowledgements

This project uses various open-source packages, including Class Variance Authority. We're grateful to the maintainers and contributors of these projects.

---

For more information, please check the individual component files and stories in the `src` directory. Don't forget to subscribe to our YouTube channel for more tutorials and updates!
