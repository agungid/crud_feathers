# intro_backend

> Membuat CRUD sederhan sebagai API dengan Feathers dan Database Postgre

[Feathers](http://feathersjs.com)

## Cara Instal

Getting up and running is as easy as 1, 2, 3.

1. Anda harus sudah mengistall [NodeJS](https://nodejs.org/) dan [npm](https://www.npmjs.com/).
2. Clone project
    ```
    git clone https://github.com/agungid/crud_feathers.git
    ```
3. Install dependencies

    ```
    cd path/to/crud_feathers;
    ```
    dan jalakan 
    ```npm install```
4. Membuat database di postgresql dan edit 
  ```config/default.json ```
  ```
  "postgres": "postgres://username_db:password_db@localhost:5432/nama_database"
  ```
5. Selanjutnya jalankan 
    ```
    npm start
    ```
Untuk frontend menggunakan vue dapat dilihat [Vue+Vuex](https://github.com/agungid/vue_vuex)
dokementasi feathersjs dapat dilihat di [Feathers](http://feathersjs.com)
