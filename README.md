# Game Jam Site
Site for HackUTD's Fall 2020 Game Jam.

gamejam.hackutd.co

# Development
The site is a plain html/css/js site (yes, they exist). Everything is contained in the `/public` directory. 

# Deployment
The site can be deployed locally on a simple http server. One is included as a
dev dependency and can be invoked with `npm run start`.

To deploy to GitHub pages, simply push to `master`. [This GitHub Action](https://github.com/acmutd/game-jam-site/blob/master/.github/workflows/deploy.yml) will automatically deploy it.