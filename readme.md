# React JSON-Server



# json-server

```sh

$ npm i -g json-server

$ npm i -D json-server


```




# faker.js

https://www.npmjs.com/package/faker

```sh

$ npm i -D faker


```

# yarn

```sh

$ yarn add -D json-server

$ yarn add -D faker


```



<script>
    fetch('https://github-cloud.s3.amazonaws.com/', {
        method: 'post',
        headers: {
            'Accept': 'application/json',
            'Content-Type': 'application/json'
        },
        body: JSON.stringify({
            "title":   "Add a blogpost about Angular2",
            "dueDate": "2015-05-23T18:25:43.511Z",
            "done": false
        })
    }).then(function(response) {
            return response.json()
    }).then(function(json) {
            console.log('parsed json: ', json)
    }).catch(function(error) {
          console.log('parsing failed: ', error)
    });




    fetch('https://cdn.xgqfrms.xyz/json/cats.json', {
        method: 'get',
        headers: {
            'Accept': 'application/json',
            'Content-Type': 'application/json'
        }
    }).then(function(response) {
            return response.json()
    }).then(function(json) {
            console.log('parsed json: ', json)
    }).catch(function(error) {
          console.log('parsing failed: ', error)
    });
</script>


























