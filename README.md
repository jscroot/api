# api
Restfull API

```js
function GetResponse(result){
    document.getElementById("formsignup").innerHTML = result;
}

let target_url = "https://foo.bar"
let tokenjson = {
    "key" : "Token",
    "value" : "asiuha87fdy87sdf87sfbdsfgds87gf87we87vf87dv"
}
let datajson = {
    "namadepan": namadepan,
    "namabelakang": namabelakang,
    "email": email,
    "password": password
    }

Post(target_url,tokenjson,datajson,GetResponse);

```