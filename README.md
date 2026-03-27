# `govuk-exports` sandbox

A minimal reproduction of `govuk-exports` to understand how to make it work with both `@import` and `@use`.

## Usage

1. Install dependencies with `npm ci`
2. Compile stylesheets with:
    - `npx sass index.scss` for including files with `@use`
    - `npx sass with-import.scss` for including files with `@import`
