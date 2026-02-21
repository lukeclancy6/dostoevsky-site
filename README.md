# Dostoevsky Personal Website

A personal website written entirely in the voice of Fyodor Dostoevsky, styled as a 19th-century Russian literary journal. The anachronism is played completely straight.

Built with [Astro](https://astro.build). Zero client-side JavaScript except for the quote flipper, rotating pull quote, and random page navigation.

## Pages

| Route | Title |
|-------|-------|
| `/` | An Address to the Reader |
| `/works` | My Works, Such As They Are |
| `/bio` | A Man of My Acquaintance |
| `/diary` | The Diary of a Writer |
| `/underground` | The Underground & The Faith |
| `/from-the-pages` | From the Pages |
| `/library` | The Reading Room |

## Stack

- **Framework**: Astro 5
- **Styling**: Pure CSS with custom properties — no Tailwind
- **Fonts**: IM Fell English, Spectral, Cormorant SC (self-hosted via fontsource)
- **Content**: Astro pages + TypeScript data file for quotes

## Development

```sh
npm install
npm run dev       # localhost:4321
npm run build
npm run preview
```

## Design

Aged paper palette (`#F5EDD6` background, `#1A1209` ink), sidebar navigation, drop caps, ornamental dividers, and a CSS paper texture. Portrait: Vasily Perov, *Portrait of Fyodor Dostoevsky*, 1872. Public domain.
