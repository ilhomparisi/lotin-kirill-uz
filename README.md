
# lotin-kirill-uz

Ushbu kutubxona orqali stringni lotindan kirillga yoki aksincha kirilldan lotinga o'girsa bo'ladi.  

### O'rnatish 
package.json filini ochib, dependencies bo'limiga: \
```"lotin-kirill-tarjimon": "github:ilhomparisi/lotin-kirill-uz"``` 
qo'shing.  
keyin ```npm i``` berib o'rnatib oling. 

### Ishlatish
Birinchi import qivolamiz:

```const {lotinga, kirillga } = require('lotin-kirill-tarjimon');```

Keyin funksiya shaklida chaqirseyz bo'ladi:
``` 
    let natija = kirillga("Uz meva uzum, sanoat holding kompaniyasi");
    console.log(natija); //уз мева узум, саноат ҳолдинг компанияси
```
