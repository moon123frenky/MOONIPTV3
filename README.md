# IPTV Web Player

Jednostavan HTML5 IPTV web player koji koristi `hls.js`. Kompatibilan sa HLS (.m3u8) i .ts streamovima.

## 🔗 Korištenje

Nakon što deployaš na GitHub Pages, koristi URL u formatu:

```
https://tvojusername.github.io/iptv-web-player/player.html?url=ENCODED_STREAM_LINK
```

## 💡 Primjer

```
https://tvojusername.github.io/iptv-web-player/player.html?url=http%3A%2F%2Fbalkan-x.net%3A80%2Flive%2FSerifVillach2023%2Fserif1234%2F12345.ts
```

## 🎮 Funkcionalnosti

- ✅ HLS podrška preko `hls.js`
- ✅ Fallback za Safari
- ✅ Auto start
- ✅ Prikaz grešaka

## 🧪 Testirano na

- Chrome
- Firefox
- Safari (bez `hls.js`)

## 🛠️ Napomena

Ne čuva podatke. Sve ide direktno iz linka. Ako stream ne radi, provjeri da li je HLS kompatibilan.
