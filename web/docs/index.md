---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: 'Rolldown'
  text: 'Fast Rust-based bundler for JavaScript'
  tagline: 'with Rollup-compatible API'
  image:
    src: /rolldown-round.svg
    alt: Rolldown
  actions:
    - theme: brand
      text: Why Rolldown
      link: /about
    - theme: alt
      text: Contribute
      link: /contrib-guide/

features:
  - title: Speed of Rust
    icon:
      src: /ferris.svg
  - title: Rollup Compatible
    icon:
      src: /rollup.svg
      width: 32px
      height: 32px
  - title: Designed for Vite
    icon:
      src: /vite.svg
      width: 32px
      height: 32px
---

:::warning Work in Progress
Rolldown is currently in active development and not usable for production yet. We encourage you to learn about [why we are building it](/about.md) and welcome community contributions. If you are interested in getting involved, check out the [Contribution Guide](/contrib-guide/) and join us on [Discord](https://discord.gg/vsZxvsfgC5)!
:::

<style>
:root {
  --vp-home-hero-name-color: transparent;
  --vp-home-hero-name-background: -webkit-linear-gradient(90deg, #FF5D13, #F0DB4F);
}
</style>
