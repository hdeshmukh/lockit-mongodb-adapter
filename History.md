
##### 0.3.0 - 2014-04-11

- key `username` is now `name`
- use built-in [pbkdf2](http://nodejs.org/api/crypto.html#crypto_crypto_pbkdf2_password_salt_iterations_keylen_callback)
  instead [bcrypt](https://github.com/ncb000gt/node.bcrypt.js/)

##### 0.2.0 - 2014-04-03

- simplify `remove()` method

  ```js
  adapter.remove(match, query, callback)
  ```

  becomes

  ```js
  adapter.remove(username, callback)
  ```

...

##### 0.1.0 - 2013-01-22

 - drop `dbUrl` and use `db` instead
 - use new `config.js` structure
