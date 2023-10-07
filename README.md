# ImgGen

The **AI Image Generator** is a React component designed to generate images based on user-provided descriptions. It leverages OpenAI's powerful image generation API to create unique visuals.

## Features

- Generates images based on user input.
- Supports descriptive prompts to guide image generation.
- Provides a loading indicator while images are being generated.

## Getting Started

To use the AI Image Generator component in your React application, follow these steps:

1. Install the component:

```bash
npm install @your-package-name/ai-image-generator
```

2. Import the component into your React file:

```jsx
import ImageGenerator from '@your-package-name/ai-image-generator';
```

3. Use the component in your JSX:

```jsx
<ImageGenerator />
```

## Usage

```jsx
import React from 'react';
import ImageGenerator from '@your-package-name/ai-image-generator';

const App = () => {
  return (
    <div className="App">
      <ImageGenerator />
    </div>
  );
}

export default App;
```

## Props

The component accepts the following props:

- `None` - This component does not require any additional props.

## Example

```jsx
import React from 'react';
import ImageGenerator from '@your-package-name/ai-image-generator';

const App = () => {
  return (
    <div className="App">
      <ImageGenerator />
    </div>
  );
}

export default App;
```

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/awesome-feature`)
3. Commit your changes (`git commit -m 'Add awesome feature'`)
4. Push to the branch (`git push origin feature/awesome-feature`)
5. Open a pull request
