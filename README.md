# fits-ui - Elegant CSS Modules-Based UI Library

FitsUI is a sophisticated UI library built on the foundation of CSS Modules, designed to help you create stunning user interfaces for your web applications. With fits-ui, you can effortlessly develop visually appealing and responsive UI components, all while benefiting from the modularity and encapsulation provided by CSS Modules.

## Features

- **Modular CSS:** fits-ui leverages the power of CSS Modules to encapsulate styles and prevent clashes with other styles in your application.

- **Elegant Design:** With a focus on simplicity and elegance, fits-ui is based in shadcd-ui, provides carefully crafted components that enhance the aesthetic appeal of your web app.

- **Responsive Ready:** All fits-ui components are designed to seamlessly adapt to different screen sizes, ensuring a consistent and visually pleasing experience across devices.

- **Customization:** While fits-ui offers a beautiful default style, you can easily customize the components to match your brand's colors and design preferences.

- **Easy Integration:** Getting started with FitsUI is as simple as installing the package and importing the components you need.

## Installation

You can quickly integrate FitsUI into your project using npm:

```bash
npm install fits-ui
```

## Usage

1. Import the FitsUI component styles using CSS Modules:

```jsx
import React from 'react';
import 'fits-ui/dist/fits-styles.css'; // Import FitsUI CSS Module
```

2. Import and utilize FitsUI components in your React application:

```jsx
import React from 'react';
import 'fits-ui/fits-styles.css';
import { Button } from 'fits-ui';

const App = () => {
  return (
    <div>
      <Button>Get Started</Button>
    </div>
  );
};

export default App;
```

## Contribution

We warmly welcome contributions from the community! If you're interested in contributing to fits-ui, please follow our **Contribution Guidelines**:.

- Create a issue with description and exemples
- Create a fork
- Create a branch in you fork using convencional commits
- Open a pull request to the repository 
- Wait util your pr be reviewed 
- If we don't find have any issue we will merge you pull request, otherwise we will send tips to fix you code.


## License

FitsUI is released under the [MIT License](https://opensource.org/licenses/MIT).