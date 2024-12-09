# @crittercodes/critter-kit-react

A collection of reusable and responsive React components for building modern web applications with ease. Designed and maintained by CritterCodes.

---

## Installation

Install the package via npm:

```bash
npm install @crittercodes/critter-kit-react
```

Or via yarn:

```bash
yarn add @crittercodes/critter-kit-react
```

---

## Components

Here are the components included in the library:

- **CallToAction**: A customizable call-to-action banner.
- **HeroCarousel**: A full-width image carousel with titles and descriptions.
- **ImageWithText**: A clean layout for showcasing images alongside text.
- **GalleryGrid**: A responsive gallery with zoomable images.
- **ContactForm**: A simple and customizable contact form.
- **ServiceCards**: Beautiful cards for showcasing services or features.

---

## Usage

Import the components you need into your project:

```javascript
import { CallToAction, HeroCarousel, ContactForm } from '@crittercodes/critter-kit-react';

function App() {
  return (
    <div>
      <HeroCarousel
        slides={[
          { image: '/path/to/image1.jpg', title: 'Slide 1', description: 'Description for slide 1' },
          { image: '/path/to/image2.jpg', title: 'Slide 2', description: 'Description for slide 2' },
        ]}
      />
      <CallToAction
        heading="Ready to Start?"
        description="Join us today and create something amazing."
        buttonText="Get Started"
        buttonLink="/signup"
      />
    </div>
  );
}

export default App;
```

---

## Documentation

### CallToAction

```jsx
<CallToAction
  heading="Your Heading"
  description="Your description here."
  buttonText="Primary Button"
  buttonLink="/primary"
  secondaryButtonText="Secondary Button"
  secondaryButtonLink="/secondary"
  backgroundImage="/path/to/image.jpg"
/>
```

| Prop                | Type     | Description                       |
|---------------------|----------|-----------------------------------|
| `heading`           | `string` | The heading text.                 |
| `description`       | `string` | The description text.             |
| `buttonText`        | `string` | Text for the primary button.      |
| `buttonLink`        | `string` | Link for the primary button.      |
| `secondaryButtonText` | `string` | Text for the secondary button.    |
| `secondaryButtonLink` | `string` | Link for the secondary button.    |
| `backgroundImage`   | `string` | URL of the background image.      |

### HeroCarousel

```jsx
<HeroCarousel
  slides={[
    { image: '/path/to/image.jpg', title: 'Title 1', description: 'Description 1' },
    { image: '/path/to/image.jpg', title: 'Title 2', description: 'Description 2' },
  ]}
/>
```

| Prop   | Type     | Description                   |
|--------|----------|-------------------------------|
| `slides` | `array`  | Array of slide objects. Each object should contain `image`, `title`, and `description`. |

---

## Contributing

Contributions are welcome! If you have ideas for improving the library or find bugs, feel free to open an issue or submit a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---

## Author

Developed and maintained by **CritterCodes**.

