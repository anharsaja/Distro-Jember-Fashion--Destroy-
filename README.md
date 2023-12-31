
# Distro Clothes Fasion
## Store : Distro Jember. F

Ini adalah website E-Commerce yang bertemakan Distro dengan nama website "Destroy". Website ini dibuat untuk memenuhi pemesanan dari Store Distro Jember yang menjual aneka Fasion dengan tema distro. Untuk lebih lengkapnya bisa lihar di halaman website Funspooky Jember, alamat Jl. MT. Haryono Np. 101a.


## Screenshots

![App Screenshot](./public/assets/imgs/contoh.png)
![App Screenshot](./public/assets/imgs/contoh2.png)


## Run Locally

Clone the project

```bash
  git clone git@github.com:anharsaja/clothes_E-Commerce.git
```

Go to the project directory

```bash
  cd my-project
```

Buat database dan kaitkan pada .ENV
```SQL
  php artisan migrate
```

Install dependencies

```bash
  npm install
```
```bash
  npm run dev
```

Start the server

```bash
  php artisan serve
```

## Demo

http://localhost:8000




## Install any library

* Livewire
```Powershell
  composer require livewire/livewire
```


* Breeze
```Powershell
  composer require laravel/breeze:1.9.4
  php artisan breeze:install
  npm install
  npm run dev
```

* Turbolinks

Add the turbolinks package to your application:
```Powershell
  npm install --save turbolinks
```
Require and start Turbolinks in your JavaScript bundle:
```code
  var Turbolinks = require("turbolinks")
      Turbolinks.start()
```
