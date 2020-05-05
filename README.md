# AcBlog

![CI](https://github.com/acblog/acblog/workflows/CI/badge.svg)

## Features

- Based on WebAssembly
- Single Page APP
  - Installable
  - Offline
- Frontend
  - Full static files
- Backend
  - Static-file backend with generator
  - Dynamic server backend
- Post
  - Category & Keywords
  - Markdown rendering
  - LaTeX math rendering
  - Password protection

## Build

1. Install .NET Core SDK 3.1.201, NodeJS 12.x and npm.
2. Install Gulp

```sh
npm install -g gulp
```

3. Restore dependencies

```sh
pwsh -c tools.ps1 restore
```

4. Build project

```sh
dotnet build
```

## Test & Benchmark

```sh
pwsh -c tools.ps1 test

pwsh -c tools.ps1 benchmark
```
