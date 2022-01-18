# Fathom app for XP

Enonic XP Application for adding [Fathom Analytics](https://usefathom.com/ref/SVGDJS) tracking script to your website.

[![](https://jitpack.io/v/no.item/xp-fathom.svg)](https://jitpack.io/#no.item/xp-fathom)

<img src="https://github.com/ItemConsulting/xp-fathom/raw/main/docs/fathom-logo-small-blackbg.svg?sanitize=true" width="150">

## Installation

Download this application from Jitpack, and install the jar.

## Usage

### Configuration

When you add the Fathom application to your *site*, you can to configure these fields under site config.

 1. [Fathom site key](https://usefathom.com/docs/script/script) (required)
 2. [Tracking type – SPA modes](https://usefathom.com/docs/script/script-advanced#spa)
 3. [Honor Do Not Track](https://usefathom.com/docs/script/script-advanced#dnt)
 4. [Ignore canonicals](https://usefathom.com/docs/script/script-advanced#canonicals)

## Deploying

### Building

To build he project run the following code

```bash
enonic project build
```

### Deploy locally

Deploy locally for testing purposes:

```bash
./gradlew publishToMavenLocal
```

## Deploy to Jitpack

Go to the [Jitpack page for xp-fathom](https://jitpack.io/#no.item/xp-fathom) to deploy from Github.
