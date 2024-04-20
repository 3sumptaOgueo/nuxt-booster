> # 🚨 Please update your dependencies. You can still retrieve version 2 (`nuxt-booster@2`), but it will no longer be maintained

# Nuxt Booster

Nuxt Booster takes over the Lighthouse performance optimization of your generated website.
All used components and resources are loaded on demand based on the viewport.

## Demos

- [Nuxt Booster Example](https://basics.github.io/nuxt-booster/playground/) ([Lighthouse](https://pagespeed.web.dev/report?url=https%3A%2F%2Fbasics.github.io%2Fnuxt-booster%2Fplayground%2F), [Sitespeed](https://basics.github.io/nuxt-booster/reports/sitespeed/nuxt-booster/))

## Getting Started

Please follow the [📖 &nbsp;&nbsp;**Documentation**](https://basics.github.io/nuxt-booster/)

## Requirements

- NodeJS `>= 12.x.x`
- NuxtJS `>= 2.15.0`

## Features

- dynamic loading of viewport based page resources like fonts, components, pictures, images and iframes
- optional blocking of javascript execution by initial performance measuring
- optimized initial load of javascript files by eliminating of unnecessary javascript files
- prevents the loading of unnecessary resources (including components) that are outside the current viewport.
- optional info layer concept to inform users about a reduced UX when bandwidth or hardware is compromised.  
- completely new approach of font declaration
- optimized picture component (supports viewport based sources e.g. landscape/portrait)
- optimized image component
- supports SEO-friendly lazy hydration mode (picture + image)
- optimized youtube/vimeo component (auto generated poster image in different resolutions)  

## Results

- delivery of the minimum required resources based on the current viewport
- if you use the tools as specified you will get a lighthouse performance score of 100/100

📖 &nbsp;&nbsp;[Read more](https://basics.github.io/nuxt-booster/)

## Browsers support

> You can use `nuxt-booster` with **Internet Explorer 11** browser. [Learn more at Browser compatibility](https://basics.github.io/nuxt-booster/caveats#browser-compatibility)

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari-ios/safari-ios_48x48.png" alt="iOS Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>iOS Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/samsung-internet/samsung-internet_48x48.png" alt="Samsung" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Samsung | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/opera/opera_48x48.png" alt="Opera" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Opera | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/vivaldi/vivaldi_48x48.png" alt="Vivaldi" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Vivaldi |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Edge                                                                                                                                                                                                            | last 2 versions                                                                                                                                                                                                   | last 2 versions                                                                                                                                                                                               | last 2 versions                                                                                                                                                                                               | last 2 versions                                                                                                                                                                                                               | last 2 versions                                                                                                                                                                                                                     | last 2 versions                                                                                                                                                                                           | last 2 versions                                                                                                                                                                                                   |

## Development

1. Clone this repository.
2. Install dependencies using `npm install` or `yarn install`.
3. Start development server using `npm run dev` or `yarn dev`.

## Preview

1. Clone this repository.
2. Install dependencies using `npm install` or `yarn install`.
3. Build and start with express `npm run start:generate` or `yarn start:generate`.
4. Open [http://127.0.0.1:3000](http://127.0.0.1:3000) in Browser.

## Consulting & Support

Do you need further support, a consultation or a code review for an appropriate fee? Just contact us via eMail: <stephan.gerbeth@gmail.com>. We are looking forward to your request.

## License

[MIT License](./LICENSE)
