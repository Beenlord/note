```js
export default ({ app, redirect, $axios }) => {

let data = {

'userid': app.$cookies.get('user_id'),

'token': app.$cookies.get('auth_token'),

};

$axios.post(`/tokenVerify`,data)

.then(res => {

console.log(res)

})

}
```