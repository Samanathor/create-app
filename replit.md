# Expo React Native Web Application

## Overview
This is an Expo React Native application with web support, successfully imported and configured to run in the Replit environment. The project uses Expo Router for file-based routing and includes a complete tab-based navigation setup.

## Project Architecture
- **Framework**: Expo (~54.0.8) with React Native (0.81.4)
- **Routing**: Expo Router (~6.0.6) with file-based routing
- **Navigation**: React Navigation with bottom tabs
- **UI**: Themed components with dark/light mode support
- **Build System**: Metro bundler with React Compiler enabled

## Current Setup
- **Development Server**: Running on port 5000 via Expo CLI
- **Build Process**: Metro bundler handles both web and server-side rendering
- **Deployment**: Configured for autoscale deployment with static web export

## Recent Changes (September 17, 2025)
- Successfully imported GitHub project to Replit
- Installed all dependencies (963 packages)
- Configured workflow to run Expo web server on port 5000
- Set up deployment configuration for production builds
- Verified application runs correctly with screenshot testing

## Key Files
- `app/`: Main application directory with file-based routing
- `app/(tabs)/`: Tab navigation screens (index, explore)
- `components/`: Reusable UI components (themed, parallax, etc.)
- `constants/`: Theme and styling constants
- `app.json`: Expo configuration with web output settings

## Development Notes
- The application uses React 19.1.0 with React Compiler enabled
- Server supports both web and mobile platforms (iOS/Android via Expo Go)
- Web version accessible at http://localhost:5000 during development
- Minor deprecation warning for `props.pointerEvents` noted in browser console