> **WARNING**: THIS REPO WAS MOVED!
>
> This repo was moved to [it's own repository](https://github.com/allatrendorseg/allatrendorseg.github.io)! 📦

# Animal Police Website

## Development

### Quick start

Requirements:

- Go
- Git

To use the ananke theme, you need to clone the repo with its submodules.

```bash
# Clone with submodules
git clone --recurse-submodules {repo-url}

# Clone first then initialize submodules
git clone {repo-url}
git submodule init
git submodule update
```

To start the server:

```bash
hugo server -D
```

For further set up, read Hugo's [quick start guide](https://gohugo.io/getting-started/quick-start/).

## Theme

Currently using [ananke](https://github.com/theNewDynamic/gohugo-theme-ananke).

Maybe try [rjordaney](https://rjordaney.is/).

Update the theme:

```bash
cd themes/ananke
git pull origin main

cd ../..
git add themes/your-theme
git commit -m "Update theme to the latest version"
```

## Refs

- [Example site](https://github.com/theNewDynamic/gohugo-theme-ananke/tree/master/exampleSite/content/fr)

- Photo by [Pixabay](https://www.pexels.com/photo/adorable-animal-blurred-background-cat-207901/)
