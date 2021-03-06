# Discord-Bot-Statistics-API
Discord Bot Statistics Web Api made with Discord.js

### Açıklama

- Bu API ile Discord Bot İstatistiklerinizi Sitenizde Gösterebilirsiniz.

- API erişmi için http://ip_address:80/api şeklinde API sitesine ulaşabilirsiniz.

- Yardım için Discord üzerinden MOSCAR#6388 İletişime geçebilirsiniz.

![ÖRNEK](https://github.com/1MOSCAR/Discord-Bot-Statistics-API/blob/main/example.png?raw=true)

# Anlatım

- `$ node main.js` yazarak apiyi başlatabiliriniz. Erişim için http://ip_address:80/api girmelisiniz.

- main.js dosyasının içerisindekini `14. satırı` istediğiniz gibi değiştire bilirsiniz. Örnek `app.listen(8080)` şeklinde yapar iseniz api sitesine http://ip_address:8080/api şeklinde giriş yapmanız gerekecektir.

- main.js dosyasının içerisindekini `15. satırı` istediğiniz gibi değiştire bilirsiniz. Örnek `app.get('/bot', (request, response) => {` şeklinde yapar iseniz api sitesine http://ip_address:80/bot şeklinde giriş yapmanız gerekecektir.

### Kullanılan Modüller
#### [discord.js](https://www.npmjs.com/package/discord.js)
#### [express](https://www.npmjs.com/package/express)
#### [moment](https://www.npmjs.com/package/moment)
#### [moment-duration-format](https://www.npmjs.com/package/moment-duration-format)
