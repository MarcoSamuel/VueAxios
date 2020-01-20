# <p align="center">VueAxios</p>
**Using APIs with Vue js and Axios**<br/>
Check if you have the node js installed on your machine **node --version**</br>
If you have not https://nodejs.org/en/
To use db.json you need an json server  **npm install -g json-server**
Then run the command **json-server file_name.json**
```javascript
const vue = new Vue({
  el:"#root",
  data:{
    infor:null
   },
   mounted(){
     axios
      .get(['Coloque aqui sua url'])
      .then(response => { this.info = response })
      .catch(error => { console.log(error) })
    }
});
```
