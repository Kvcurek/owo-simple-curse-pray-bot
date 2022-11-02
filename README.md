# OWO-SIMPLE-CURSE/PRAY BOT
This method give you `288` pray/curse per `24` hours.


#### 🌐 Runing project.
1) Complete the configuration in `config.json` file,
2) Paste discord account token in `.env`.
3) Install modules 
```js
npm install . 
```
4) Run bot
```js
npx ts-node .
```
5) Enjoy! :D
#### 🕵️‍♂️ How to get DISCORD TOKEN to run bot? This is easy, click **`ctrl + shift + i`** in discord window and paste this code to console.
```js
window.webpackChunkdiscord_app.push([
  [Math.random()],
  {},
  req => {
    for (const m of Object.keys(req.c)
      .map(x => req.c[x].exports)
      .filter(x => x)) {
      if (m.default && m.default.getToken !== undefined) {
        return copy(m.default.getToken());
      }
      if (m.getToken !== undefined) {
        return copy(m.getToken());
      }
    }
  },
]);
console.log('%cWorked!', 'font-size: 50px');
console.log(`%cYou now have your token in the clipboard!`, 'font-size: 16px');
```
Next step is paste your token to `.env` file, this is all! 

#### ⚙️ Config Tutorial
`userID` - this is the user who gets pray or curse.

`channelID` - this is the channel where it sends pray or curse.
###### Contact to me in Discord: [Kvcurek#0703](https://discord.com/users/927328599000875088)
