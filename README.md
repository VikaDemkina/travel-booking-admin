# Travel Booking Admin Microfrontend

This repository contains the admin panel microfrontend for the Travel Booking application, built with Svelte.

## Installation

```bash
npm install
```

## Development

```bash
npm run dev
```

## Build

```bash
npm run build
```

## Features

- Dashboard with key metrics
- Tour management
- User management
- Booking administration
- Reports and analytics

## Architecture

This is part of a microfrontend architecture using:
- Svelte as the framework
- Single-spa for microfrontend integration

## CI/CD

This repository uses GitHub Actions for CI/CD pipeline, which will:
- Build and type check the code on every PR and push to main
- Collect build metrics
- Deploy to GitHub Pages on push to main