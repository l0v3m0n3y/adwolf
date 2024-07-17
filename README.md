# adwolf
JavaScript library for geo.adwolf.ru
# main
```js
async function main(){
    const {adwolf} = require('./adwolf');
    const ip= new adwolf();
    let req=await ip.my_ip()
    console.log(req)
}
main()
```
