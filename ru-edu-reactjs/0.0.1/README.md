# RuEdu Admin Dashboard

![RuEdu Admin Preview]()

A modern admin dashboard template built with Vite, React, TypeScript, and Ducor UI components.

## 🚀 Quick Start

### Create New Project
Run the following command to generate a new admin dashboard:

```bash
ducor admin:vite-react-ts
cd vite-react-ts
```

###  Install Dependencies
```bash
npm install
# or
yarn install
```

### Start Development Server
```bash
npm run dev
# or
yarn dev
```

## ✨ Key Features

### ⚡ Performance
- **Vite-powered** for instant hot module replacement
- **Code splitting** for optimized loading
- **Production-ready** builds with minification

## 🎨 Available UI Components

### 📦 Layout Components
- **`ScrollArea`** - Custom scrollable container
- **`Container`** - Responsive layout wrapper
- **`Box`** - Flexible layout primitive
- **`Flex`** - Flexbox container
- **`Grid`** - CSS Grid layout

### 🔘 Interactive Elements
- **`Button`** - Clickable action element
- **`Disclosure`** - Collapsible content area
- **`Dropdown`** - Contextual menu
- **`Drawer`** - Slide-out panel
- **`TreeView`** - Hierarchical data display

### 🖼️ Display Components
- **`Typography`** - Text styling system
- **`Avatar`** - User/profile image display
- **`Badge`** - Status indicator
- **`Card`** - Content container with shadow
- **`Alert`** - Notification message box
- **`Kbd`** - Keyboard key styling
- **`Divider`** - Visual separator line

### ⚙️ Utility Components
- **`Loading`** - Activity indicator

  ## 💻 Basic Usage
```jsx
import { Button, Card, Alert } from '@ducor/react';

function App() {
  return (
  Card color="default" variant="solid">
  <Card.Header>
    <Card.Title>default - solid Card</Card.Title>
  </Card.Header>
  <Card.Body>
    Card content goes here
  </Card.Body>
  <Card.Footer>Card Footer</Card.Footer>
</Card>
  );
}
```

## 🛠️ Available Hooks

- **`useBoolean`** - Toggle true/false state
- **`useClipboard`** - Copy text to clipboard
- **`useElementSize`** - Track element dimensions
- **`useFullscreen`** - Toggle fullscreen mode
- **`useHover`** - Detect element hover
- **`useIdle`** - Detect user inactivity
- **`useInterval`** - Run code at intervals
- **`useOutsideClick`** - Detect clicks outside element
- **`usePlacement`** - Calculate element positioning
- **`useProcessing`** - Manage loading states
- **`useScroll`** - Track scroll position
- **`useTimeout`** - Execute delayed callbacks
- **`useUnmountEffect`** - Cleanup on unmount
- **`useUuid`** - Generate unique IDs
- **`useWindowEvent`** - Add window event listeners

 ```jsx
import { useBoolean } from '@ducor/hooks';

function ToggleComponent() {
  const [flag, { on, off, toggle }] = useBoolean(false);

  return (
    <div>
      <p>Current state: {String(flag)}</p>
      <div className="button-group">
        <button onClick={on}>Turn On</button>
        <button onClick={off}>Turn Off</button>
        <button onClick={toggle}>Toggle</button>
      </div>
    </div>
  );
}
``` 
## 📚 Sources & Credits

### Core Libraries
- [React](https://react.dev) - JavaScript library for building user interfaces
- [Tailwind CSS](https://tailwindcss.com) - Utility-first CSS framework
- [Axios](https://axios-http.com) - Promise-based HTTP client
- [React Router](https://reactrouter.com) - Client-side routing

### UI Components
- [Ducor UI](https://ducorui.com) - Internal component library (`@ducor/react`, `@ducor/hooks`, `@ducor/form`)
- [Headless UI](https://headlessui.com) - Unstyled accessible components
- [React Icons](https://react-icons.github.io/react-icons) - Icon library
- [Sonner](https://sonner.emilkowal.ski) - Toast notifications

### Data Visualization
- [Chart.js](https://www.chartjs.org) + [React ChartJS 2](https://react-chartjs-2.js.org) - Interactive charts
- [Recharts](https://recharts.org) - Composible charting library

### Calendar
- [FullCalendar](https://fullcalendar.io) - Full-featured calendar system

### Utilities
- [Tailwind Plugins](https://tailwindcss.com/docs/plugins) - Official Tailwind extensions:
  - `@tailwindcss/forms`
  - `@tailwindcss/typography`
  - `@tailwindcss/aspect-ratio`
  - `@tailwindcss/container-queries`
- [Tailwind Merge](https://github.com/dcastil/tailwind-merge) - Conditional Tailwind class merging

### Internationalization
- [React i18next](https://react.i18next.com) - Internationalization framework

### Development Tools
- [Prettier](https://prettier.io) - Code formatter
- [Prop Types](https://github.com/facebook/prop-types) - Runtime type checking

## 📜 License
All third-party libraries are used under their respective open-source licenses.
