# Additional Projects Setup

This exercise will guide you through setting up two additional GitHub repositories that complement our main performance workshop project.

## Overview

During the workshop, you may need access to these additional repositories:

1. **perf-playground** (Required) - Additional performance examples and exercises
2. **js-playground** (Optional) - Lightweight JavaScript/TypeScript playground for specific exercises

## Prerequisites

- Git installed on your system
- Node.js and npm available
  - `node ^20.19.0 || ^22.12.0 || ^24.0.0`
  - `npm > 10`
- Basic familiarity with command line operations

## 1. Perf Playground Setup (Required)

The perf-playground repository contains additional performance examples and exercises that we'll reference throughout the workshop.

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/push-based/perf-playground.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd perf-playground
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Start the development server**
   ```bash
   npm run start
   ```

5. **Verify installation**
   - The application should open in your browser
   - You should see the perf-playground application running

## 2. JS Playground Setup (Optional)

The js-playground is a lightweight repository for JavaScript/TypeScript exercises. This is primarily used as a fallback for the [Event Loop exercise](./event-loop.md) if you encounter issues with StackBlitz.

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/push-based/js-playground.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd js-playground
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Start the development server**
   ```bash
   npm run start
   ```

5. **Verify installation**
   - The playground should be accessible in your browser
   - You can now use this for JavaScript exercises if needed

## When to Use These Projects

### Perf Playground
- Referenced throughout various performance exercises
- Contains additional examples and demos
- Required for completing certain workshop tasks

### JS Playground
- Alternative to StackBlitz for the [Event Loop exercise](./event-loop.md)
- Use this if you experience issues with online code editors
- Provides a local environment for JavaScript/TypeScript experiments

## Troubleshooting

### Common Issues

**Port conflicts:**
- If you get port errors, make sure no other applications are running on the same port
- You can usually change ports in the package.json or by setting environment variables

**Node version issues:**
- Ensure you're using a compatible Node.js version 
- Consider using nvm to manage Node versions if needed

**Installation failures:**
- Try clearing npm cache: `npm cache clean --force`
- Delete node_modules and run `npm install` again

### Getting Help

If you encounter any issues during setup:

Ask the workshop instructor


> **Note:** You can work through most workshop exercises using just the main project. These additional repositories are supplementary and will be explicitly mentioned when needed.
