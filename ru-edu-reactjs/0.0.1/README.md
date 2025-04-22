# RuEdu Admin Dashboard

![RuEdu Admin Preview]()

A modern admin dashboard template built with Vite, React, TypeScript, and Ducor UI components.

## 🚀 Quick Start

### 1. Create New Project
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
- **`DevMode`** - Development helpers
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
