## About Me
```js
async function zenAjg() {
  return new Promise(async(resolve, reject) => {
    try {
      let data = {
        name: "Zen",
        bio: {
          fullName: "Muhammad Zainal Arifin",
          hobby: "Turu",
          age: "18",
          region: "Pasuruan - Jatim"
        },
        social: {
          instagram: "https://instagram.com/nal.jnl99",
          whatsapp: "http://wa.me/6281230987025"
        }
      }
      resolve(data)
    } catch (e) {}
  })
}
console.log(zenAjg())
```
