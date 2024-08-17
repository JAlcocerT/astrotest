<div align="center">

[![CI/CD to Github Pages](https://github.com/JAlcocerT/astrotest/actions/workflows/deploy.yml/badge.svg)](https://github.com/JAlcocerT/astrotest/blob/main/.github/workflows/deploy.yml)
[![Astro npm version](https://badge.fury.io/js/astro.svg)](https://badge.fury.io/js/astro)

</div>


---

## Getting Started with Astro

A feature full Astro documentation template...

...that works out of the box with Github Pages

<details>
  <summary>Run it locally with: 👈</summary>
  &nbsp;

```sh
cd Docs
npm install
npm run dev #http://localhost:4321/astrotest/

npm run build
#npm install -g http-server
#http-server

#python3 -m http.server 8080
```

Deploy it with any of:

* [GH Pages](#github-pages)
* [Cloudlfare Pages](#cloudflare-pages)
* [Google Firebase Hosting](#firebase)

### Github Pages

* Use [this workflow](https://github.com/JAlcocerT/astrotest/blob/main/.github/workflows/deploy.yml)
    * You can see the GH Actions status [here](https://github.com/JAlcocerT/astrotest/actions)

### Cloudflare Pages

* Deploying [Astro with Cloudflare Pages](https://fossengineer.com/hosting-with-cloudflare-pages/)

```sh
#npx wrangler pages project create
npx wrangler pages deploy dist #<BUILD_OUTPUT_DIRECTORY>
```

### Firebase

* Deploying [Astro with Google Firebase](https://fossengineer.com/hosting-with-firebase/)

```sh
npm install -g firebase-tools
firebase --version

firebase init
firebase deploy
```

</details>

---

## Thanks to ❤️

- Thank you for your hard work [@TheOtterlord](https://github.com/TheOtterlord) aka Gianmarco - https://github.com/TheOtterlord/manual | https://manual.otterlord.dev/ 