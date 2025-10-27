![assets/project.svg](https://raw.githubusercontent.com/CarlosEGuerraSilva/react-tw-layouts/refs/heads/main/assets/project.svg)

<p align="center">
  Headless Tailwind-based layout components for React applications.
</p>

<!-- TODO: Add badges -->

# Installation

```bash
npm install react-tw-layouts
```

or

```bash
yarn add react-tw-layouts
```

or

```bash
pnpm add react-tw-layouts
```

# Available Layout Components

> [!NOTE]
> **WORK IN PROGRESS**: This project is currently under active development. Some components may be incomplete or subject to change. See the [Roadmap](https://github.com/users/CarlosEGuerraSilva/projects/3) for development status and [Changelog](CHANGELOG.md) for the latest updates.

### AspectRatio

A component that maintains a specified width-to-height ratio for its content, useful for embedding media like videos or images.

### Container

A responsive container component that centers your content and applies appropriate padding and custom max-widths at different breakpoints or fluid width.

### ContentSwitcher

A component that allows switching between two components using breakpoint-based conditions. Also allows you to use React's [`<Activity>`](https://react.dev/reference/react/Activity) component if that suits your needs better.

### Divider

A simple horizontal or vertical divider component to separate content visually.

### Grid

A flexbox-based grid layout component that allows you to create responsive grid layouts with customizable columns, gaps, and alignment, heavily inspired by Material UI & Radix UI Grid component.

### Responsive

A component to conditionally render its children based on specified breakpoints, with options to hide or show content at specific breakpoints.

### Screen

A component to display content using the full device viewport size, with paddings and alignment options. Useful for creating full-screen sections or base layouts.

### Section

A semantic section component that provides consistent styling and spacing for different sections of your application with also required accessibility attributes.

### SnapContainer

A scrollable container that enables snap scrolling behavior for its child elements, allowing for smooth and controlled scrolling experiences.

- #### SnapItem
  A child component of SnapContainer that defines individual items that can snap into place when scrolling within the SnapContainer. They also allow you to define how each item should align and stop when snapped.

### Stack

A flexbox-based layout component that arranges its children in a vertical or horizontal stack with customizable spacing, alignment, and distribution options.

### Surface

A versatile container component that allows you to define shadow-based surfaces with customizable elevation levels, border options, and spacing, inspired by Material UI's Paper component.

# Usage

Please refer to the [Documentation](#) (TBD) for detailed usage instructions and examples for each component.

# Want to Contribute?

Contributions are welcome! Please feel free to open issues or submit pull requests for bug fixes, enhancements, or new features. Make sure to follow our [contribution guidelines](CONTRIBUTING.md).

# License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
