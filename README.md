<p align="center">
<img src="https://github.com/Riyanid/RubotXmd/blob/V8/image/lol.jpg" alt="RUBOTX" width="100"/>


</p>
<p align="center">
<a href="#"><img title="RUBOTX MULTI DEVICE" src="https://img.shields.io/badge/RUBOTX MULTI DEVICE-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
<p align="center">
<a href="https://github.com/DikaArdnt"><img title="Author" src="https://img.shields.io/badge/Author-Dika-red.svg?style=for-the-badge&logo=github"></a>
<a href="https://github.com/zeeone-ofc/Alphabot-Md"><img title="Recode" src="https://img.shields.io/badge/Recode-ZeeoneOfc-red.svg?style=for-the-badge&logo=github"></a>
<a href="https://github.com/Riyanid/RubotXmd8"><img title="Colong" src="https://img.shields.io/badge/Colong-RiyanID-red.svg?style=for-the-badge&logo=github"></a>
</p>
<p align="center">
<a href="https://github.com/zeeone-ofc/followers"><img title="Followers" src="https://img.shields.io/github/followers/zeeone-ofc?color=red&style=flat-square"></a>
<a href="https://github.com/zeeone-ofc/Alphabot-Md/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/zeeone-ofc/Alphabot-Md?color=blue&style=flat-square"></a>
<a href="https://github.com/zeeone-ofc/Alphabot-Md/network/members"><img title="Forks" src="https://img.shields.io/github/forks/zeeone-ofc/Alphabot-Md?color=red&style=flat-square"></a>
<a href="https://github.com/zeeone-ofc/Alphabot-Md/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/zeeone-ofc/Alphabot-Md?label=Watchers&color=blue&style=flat-square"></a>
<a href="https://github.com/zeeone-ofc/Alphabot-Md"><img title="Open Source" src="https://badges.frapsoft.com/os/v2/open-source.svg?v=103"></a>
<a href="https://github.com/zeeone-ofc/Alphabot-Md/"><img title="Size" src="https://img.shields.io/github/repo-size/zeeone-ofc/Alphabot-Md?style=flat-square&color=green"></a>
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fzeeone-ofc%2FAlphabot-Md&count_bg=%2379C83D&title_bg=%23555555&icon=probot.svg&icon_color=%2300FF6D&title=hits&edge_flat=false"/></a>
<a href="https://github.com/zeeone-ofc/Alphabot-Md/graphs/commit-activity"><img height="20" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg"></a>&nbsp;&nbsp;
</p>

<p align="center">
  <a href="https://github.com/zeeone-ofc/Alphabot-Md#requirements">Requirements</a> •
  <a href="https://github.com/zeeone-ofc/Alphabot-Md#instalasi">Installation</a> •
  <a href="https://github.com/zeeone-ofc/Alphabot-Md#thanks-to">Thanks to</a> •
  <a href="https://github.com/zeeone-ofc/Alphabot-Md#Official-Group"> Official Group Bot</a> •
  <a href="https://github.com/zeeone-ofc/Alphabot-Md#donate">Donate</a>
</p>
</div>


---

## Information
> Alpahbot-Md adalah bot yang awalnya memakai base dari [Chikabot](https://github.com/rashidsiregar28/chikabot/blob/main/README.md), sekarang pindah base [Hisoka-Morou](https://github.com/DikaArdnt/Hisoka-Morou). Alphabot-Md is a bot whatsapp using a Baileys library.
> Jika kamu menemukan semacam bug, harap untuk dimaklumi sementara

## Bugs and Tester
* Jika kamu menemukan bug jangan lupa buka Issues
* Info Lebih Lanjut, Chat [owner-alpha](https://wa.me/62887435047326)

# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip) (for sticker command)

# Instalasi
## Heroku Buildpack
```bash
heroku/nodejs
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```
## For Termux
```ts
termux-setup-storage
apt update && apt upgrade
pkg install nodejs git ffmpeg libwebp imagemagick
git clone https://github.com/zeeone-ofc/Alphabot-Md.git
cd Alphabot-Md
pkg install yarn
yarn install
npm i -g typescript
tsc -p ./node_modules/@adiwajshing/baileys-md/
rm -rf session.json
rm -rf store.json
npm start
```

## Edit file
`./settings.js`
```ts
global.autoread = false // auto read pesan / message
global.autorecording = true //status auto merekam ( auto record )
global.autoketik = false //status auto mengetik (auto typing)
global.available = false //status online (online)

// Other
global.botname = "RubotX-Mdོ" //namabot kalian
global.ownername= "༄ᶦᶰᵈ᭄Mr.|2!¥απαDΔ࿐" //nama kalian
global.myweb ="https://rest-api-riyanid.herokuapp.com/" //bebas asal jan hapus
global.youtube = "https://youtube.com/channel/UC1XsDCuEyez3gcogOMgOJxw" //bebas asal jan hapus
global.github = "https://github.com/riyanid/" //bebas
global.email = "riyanriyanr84@gmail.com" //bebas
global.region = "Indonesia" //bebas
global.ownernomer = "6285711450232" // nomor wa kalian
global.ownernomerr = "+6285711450232" //nmr wa kalian
global.thumbnail = "./image/lol.jpg" // ini lol.jpg adalah nama foto di folder image. untuk foto bot
global.donasi = "./image/donasi.jpg" // foto donasi di folder image
global.background_welcome = "https://telegra.ph/file/42ba3c11e05ac23a66b16.jpg" // maks size 30kb, agar welcome image nya tdk delay
global.owner = ["6285711450232","6285711450232","6285711450232"] //ganti agar fitur owner bisa di gunakan
global.packname = 'RubotXོ' //sticker wm ubah
global.author = 'By R1Y4N4D4' //sticker wm ganti nama kalian
global.sessionName = 'session'

```

## Installing the FFmpeg for Windows
* Unduh salah satu versi FFmpeg yang tersedia dengan mengklik [di sini](https://www.gyan.dev/ffmpeg/builds/).
* Extract file ke `C:\` path.
* Ganti nama folder yang telah di-extract menjadi `ffmpeg`.
* Run Command Prompt as Administrator.
* Jalankan perintah berikut::
```cmd
> setx /m PATH "C:\ffmpeg\bin;%PATH%"
```
Jika berhasil, akan memberikanmu pesan seperti: `SUCCESS: specified value was saved`.
* Sekarang setelah Anda menginstal FFmpeg, verifikasi bahwa itu berhasil dengan menjalankan perintah ini untuk melihat versi:
```cmd
> ffmpeg -version
```

## Donate
- [Saweria](https://saweria.co/Riyanid)
- [Dana](https://telegra.ph/file/096d42dedcddef8085691.jpg)
- [Ovo](https://telegra.ph/file/986bb741b0c1f7517972f.jpg)
- [Qris](https://telegra.ph/file/cb879819dbed154671d86.jpg)

# Official Group
- [Group 1](https://chat.whatsapp.com/EU890BcXjyBDkNaUT5WmYV)
- [Group 2](https://chat.whatsapp.com/E8NExJwIbhBJYzssfqJNsE)
- [Group 3](https://chat.whatsapp.com/KCSqHTky1apG7ApePsfiPy)
- [Group 4](https://chat.whatsapp.com/KwmvHr7VMFj7r5ry9xmMsU)
- [Group 5](https://chat.whatsapp.com/ELa7GhU0sP4EvXcVimQYtz)

# Thanks to
<a href="https://github.com/DikaArdnt"><img src="https://github.com/DikaArdnt.png?size=100" width="100" height="100"></a> | [![NURUTOMO](https://github.com/Nurutomo.png?size=100)](https://github.com/Nurutomo) 
---|---
[Dika](https://github.com/DikaArdnt)  | [Nurutomo](https://github.com/Nurutomo)
Owner Hisoka-Morou | Constributor |
<a href="https://github.com/MhankBarBar"><img src="https://github.com/MhankBarBar.png?size=100" width="100" height="100"></a> | [![FATIH](https://github.com/fatiharridho.png?size=100)](https://github.com/fatiharridho) 
[Mhankbarbar](https://github.com/MhankBarBar)  | [Fatih A.](https://github.com/fatiharridho)
Constributor | For Help |
<a href="https://github.com/FERDIZ-afk"><img src="https://github.com/FERDIZ-afk.png?size=100" width="100" height="100"></a> | [![RASHID](http://github.com/rashidsiregar28.png?size=100)](http://github.com/rashidsiregar28) 
[Ferdiz](https://github.com/FERDIZ-afk)  | [Rashid](https://github.com/rashidsiregar28)
For Help | Owner Chikabot |
<a href="https://github.com/adiwajshing"><img src="https://github.com/adiwajshing.png?size=100" width="100" height="100"></a> | [![ZEEONE](http://github.com/zeeone-ofc.png?size=100)](http://github.com/zeeone-ofc) 
[Adiwajshing](https://github.com/adiwajshing) | [zeeone-ofc](https://zeeone-ofc.github.io)
Owner of Baileys | Owner of Api Alphabot |

