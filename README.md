# <p align="center">VueAxios</p>
**Using APIs with Vue js and Axios**
```javascript
const vue = new Vue({
	el:"#root",
	data:{
		infor:null
	},
	mounted(){
	  axios
		.get(['Coloque aqui sua url'])
		.then(response => {
			 this.info = response
	   }).catch(error => {
			    console.log(error)
			        
			 })
		    }
    });
```
