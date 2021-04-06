# Eloquent ORM - Laravel 8

ini adalah pembelajaran menggunakan Eloquent yang menggunakan teknik ORM pada Laravel 8.

## Eloquent ORM

### 1. Eloquent

-   Eloquent adalah salah satu fitur di laravel, fitur ini untuk mengelola sebuah data yang ada pada database, menjadi sangat mudah.
-   Eloquent sudah menyediakan fungsi-fungsi active record.

### 2. ORM ( Object Relation Mapping )

-   ORM merupakan teknik yang mengubah suatu table menjadi sebuah object, yang nantinya mudah untuk digunakan. Object yang dibuat memiliki property yang sama dengan field-field yang ada pada table.

## Migration & Seeder

### 1. Migration

-   Migration adalah sebuah fitur yang ada pada laravel, migration merupakan Control Version System untuk database. dengan menggunakan migration laravel, memungkinkan kita untuk mengelola database dengan lebih mudah.

### 2. Seeder ( Seeding )

-   Seeder (Seeding) pada laravel adalah sebuah fitur untuk mengisi data pada database dengan data sembarangan atau data testing.

```
php artisan migrate:refresh --seed
```
## Example ERD

![Tabel Relasi ORM](https://user-images.githubusercontent.com/52828971/113700907-9e358080-9701-11eb-943d-cff67be73cbd.jpg)

## Quick Start

Silahkan melakukan konfigurasi database pada config/config.json, dengan mengisikan sesuai data autentikasi pada database anda.

Ubah nama file .env-example menjadi .env dan lakukan penyesuaian pada JWT_SECRET_KEY dan COMPANY_NAME

Lakukan setup dengan menjalankan perintah berikut pada terminal anda

```
composer Install
```

Server akan berjalan pada http://
