# robofriends-pwa
adding PWA capabilities to a react app

## To run the project:

1. Clone this repo
2. Run `npm install`
3. Run `npm start`

## if change
`npm run build`

## deploy:
```
git init
git remote add origin <repo_link>
npm run deploy
```

## Favicon Generator

https://realfavicongenerator.net/

## Improve front end performance
https://progressivetooling.com/

## see performance & pwa
lighthouse

# (MAC zsh環境)npm start時遇到‘unsupported’的錯誤時

nodejs 17: digital envelope routines::unsupported #14532
https://github.com/webpack/webpack/issues/14532

在zsh中輸入以下指令解決

`export NODE_OPTIONS=--openssl-legacy-provider`
