# Copilot Instructions for react-first-build

This document outlines key patterns and conventions for AI agents working with this React project.

## Project Overview
- Modern React application (React 19.2.0) using Create React App scaffolding
- Organized with component-based architecture
- Development focused on Pages-and-layout branch

## Project Structure
```
src/
  components/
    layouts/     # Layout components and templates
    pages/       # Page-level components representing routes
  App.js         # Root component
  index.js       # Application entry point
```

## Component Conventions
Components follow a structured pattern with clear section comments:
```javascript
function ComponentName() {
    // Properties
    // Hooks
    // Context
    // Methods
    // View
    return (
        // JSX
    )
}
```

## Development Workflow
Common commands (run from project root):
- `npm start` - Start development server
- `npm test` - Run test suite
- `npm run build` - Create production build

## Testing
- Uses React Testing Library (@testing-library/react v16.3.0)
- Jest as test runner
- DOM-based testing approach (@testing-library/dom v10.4.1)

## Code Quality
- ESLint configured with react-app and react-app/jest presets
- Browser compatibility managed via browserslist configuration

## Remaining Questions
- Routing strategy and implementation
- State management approach
- API integration patterns
- CSS/styling conventions
- Environment configuration

Note: This is an initial version based on current codebase analysis. Please provide feedback on unclear sections or additional patterns that should be documented.