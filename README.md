
<h3 align="center">
  
  <p align="center"><img src="https://img.shields.io/badge/WLCM%20TO -NAYAN SERVER-green?colorA=%23ff0000&colorB=%23017e40&style=flat-square">  
  
</h3>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Neuton&size=25&color=30FF40&background=000000&center=true&vCenter=true&width=360&height=60&lines=Hello+World%2C+I'm+Mr-NAYAN+Here+🤙;𝙸𝚃'𝚜+𝙽𝙾𝚃+𝙰+𝙹𝚄𝚂𝚃+𝙽𝙰𝙼𝙴+𝙱𝚁𝙾+🥱;𝙸𝚃'𝚜+𝙰+𝙱𝚁𝙰𝙽𝙳+🔥;Respect+Mr.NAYAN+🥀;Thanks+My+All+Friend+🤙+🥰)](https://git.io/typing-svg)


<a href="https://www.npmjs.com/package/nayan-server"><img alt="npm version" src="https://img.shields.io/npm/v/nayan-server.svg?style=flat-square"></a>
<img alt="version" src="https://img.shields.io/github/package-json/v/MR-NAYAN-404/nayan-server?label=github&style=flat-square">
<a href="https://www.npmjs.com/package/nayan-server"><img src="https://img.shields.io/npm/dm/nayan-server.svg?style=flat-square" alt="npm downloads"></a><br>
[![Socket Badge](https://socket.dev/api/badge/npm/package/nayan-server)](https://socket.dev/npm/package/nayan-server)

## Instalation :
```bash
> npm i nayan-server
```

#### Available Api

```
• gpt
• spotify
• img2text
• pintarest
• textpro
• photoxy
• ip2lucation
• removebg
• upscale
• tokencookie (fb)
• fbinfo
• GDLink
• google web search
```

<h3 align="center">
  
  <p align="center"><img src="https://img.shields.io/badge/MORE%20 -API COMING SOON-green?colorA=%23ff0000&colorB=%23017e40&style=flat-square">  
  
</h3>


## Usage GPT

```javascript

const { gpt } = require("nayan-server");

gpt({
    messages: [
        {
            role: "assistant",
            content: "Hello! How are you today?"
        },
        {
            role: "user",
            content: "Hello, my name is Nayan."//your name
        },
        {
            role: "assitant",
            content: "Hello, Nayan! How are you today?"
        }
    ],
    prompt: "Can you repeat my name?",
    model: "GPT-4",
    markdown: false
}, (err, data) => {
    if(err != null){
        console.log(err);
    } else {
        console.log(data);
    }
});
```

## Usage Spotify

```javascript

const { spotify } = require("nayan-server");

const name = "ghum" //song name

spotify(name).then(data => {
  console.log(data)
 
});
```


## Usage Pintarest
```javascript
const { pintarest } = require("nayan-server");

const search = "Neymar pic"

pintarest(search).then(data => {
  console.log(data)
 
});
```


## Usage img2text
```javascript
const { img2text } = require("nayan-server");

img2text("https://i.imgur.com/2TTyRTo.jpeg").then(data => {
  console.log(data)
});
```
## Usage PHOTOXY
```js
const {photoxy} = require("nayan-server");

const url = "url" // photoxy url

const text = "nayan" // your text

  photoxy(url, [text])
.then((data) => console.log(data))
.catch((err) => console.log(err));
```
## Usage Photoxy 2 text 
```js
const {photoxy} = require("nayan-server");

const url = "url" // photoxy 2 text input url

const text = "Mohammad" // your text
const text2 = "nayan" // your text

  photoxy(url, [text, text2])
.then((data) => console.log(data))
.catch((err) => console.log(err));
```
## Usaage Textpro
```JS
const {textpro} = require("nayan-server");

const url = "url" // textpro url

const text = "nayan" // your text

    textpro(url, [text])
.then((data) => console.log(data))
.catch((err) => console.log(err));
```
## Usage Textpro 2 text 
```js
const {textpro} = require("nayan-server");

const url = "url" // textpro 2 text input url

const text = "Mohammad"//your text
const text2 = "nayan"// your text

    textpro(url, [text, text2])
.then((data) => console.log(data))
.catch((err) => console.log(err))
```
## Usage Ip2Lucation 
```js
const { ip } = require("nayan-server");

const address = "ip" //ip address

ip(address).then(data => {
  console.log(data)

});
```
## Usage removebg 
```js
const { removebg } = require("nayan-server");

const url = "url" //pic url

removebg(url).then(data => {
  console.log(data)

});
```
## Usage upscale 
```js
const { upscale } = require("nayan-server");

const link = "link" //past pic link
const model = "1"// model 1 or 2
upscale(link, model).then(data => {
  console.log(data)
});
```
## Usage TokenCookie (fb)
```js
const { tokencookie } = require("nayan-server");

const user = "username" // your fb username
const pass = "password" // your fb password

tokencookie(user, pass).then(data => {
  console.log(data)
});
```
## Usage Fbinfo 
```js
const { fbinfo } = require("nayan-server");

const token = "token" // your fb access token
const uid = "uid" // fb user uid

fbinfo(token, uid).then(data => {
  console.log(data)
});
```
## Usage GDLink 
```js
const {GDLink} = require("nayan-server");

const url = 'url' // Public Google Drive Url

GDLink(url).then(data => {
  console.log(data)

});
```
## Usage Google Web Search 
```js
const { gwsearch } = require("nayan-server");

const name = "nayan-server" // Name of the website
const limit = "5" // limit of results (total limit 1-20)
  gwsearch(name, limit).then(data => {
  console.log(data)
});
```
## Usage Imagine 
```js
const { imagine } = require("nayan-server");

const promt = "cat, 4k" // your promt
  imagine(promt).then(data => {
  console.log(data)
});
```

