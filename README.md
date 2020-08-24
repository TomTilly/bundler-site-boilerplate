# Basic NPM scripts starter template

Starter template I use for building simple static sites. Uses npm scripts to watch files and build. Requires Node and NPM (or yarn).

✓ Compresses images

✓ Compiles sass

✓ Compresses JS

✓ Autoprefixes CSS

✓ Live browser refreshing

✓ Includes Normalize CSS

✓ Sass architecture

## Usage

__1) Clone this repo__

__2) Install dependencies__

```

npm i

```

__3) Start server and start building__

```

npm start

```

Defaults to using a development build. When going into production, change `"build:css"` value (in package.json) from `"npm run dev:scss && npm run autoprefixer"` to `"npm run prod:scss && npm run autoprefixer"`.

## Credits

- [sass styleguide](https://sass-guidelin.es/) by Hugo Giraudel. 
- Based on foundation referenced in [this article](https://css-irl.info/a-modern-front-end-workflow-part-1/)