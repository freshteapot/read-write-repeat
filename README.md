# Read Write Repeat

- A little UI to add text and then practice typing it.
- Current thinking, linked to getting familiar typing sentences in a foreign language.

## Install
```bash
npm install
```

## Run
```bash
npm run dev
```

## Build gh-pages
```bash
build-site
```

## Setting up Tachyons with svelte

Install the dependencies...

```sh
npm install --save-dev \
@fullhuman/postcss-purgecss \
purgecss-from-svelte \
postcss-import \
autoprefixer \
tachyons \
rollup-plugin-postcss \
svelte-preprocess postcss
```

## Comment about disappearing sentences
> The workflow was:
- you read the sentence
- the sentence disappears
- then you type from memory
- every time you mistype something -- the next couple of words appears for a few seconds and you keep typing
That way you not only learn to type that foreign language. But you also memorise the sentence in your short-time memory and you get a feel for sentences are created (order of words, phrases, etc.).


# Reference
- [sveltejs/component-template](https://github.com/sveltejs/component-template)
- [Read a book via typing](https://news.ycombinator.com/item?id=24696658)
- [Comment about disappearing sentences](https://news.ycombinator.com/item?id=24697237)
