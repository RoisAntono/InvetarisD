Transaksi Single Produk
============
TRASIPRO yaitu Transaksi Single Produk, ini bertujuan untuk mengembangkan platform web e-commerce yang dirancang khusus untuk melakukan transaksi satu produk dalam satu kali pembelian. Sistem ini didesain dengan fokus pada kemudahan penggunaan dan efisiensi dalam proses transaksi, terutama untuk produk-produk yang ditujukan untuk penjualan tunggal.

- [Laravel v10.35.0](https://laravel.com/)
- [AdminLTE-3.1.0](https://adminlte.io/)
## Authors

- [Rois Antono](https://www.github.com/RoisAntono)
## Features

- Login 2 User -> Soon
- CRUD Produk (Tambah,Tampil, Update, Delete)
- Transaksi Single Produk
- Detail Transaksi
- History Log -> Soon

## Plugins

Trasipro saat ini memiliki beberapa plugin tambahan.

| Plugin | README |
| ------ | ------ |
| Carbon | [https://carbon.nesbot.com/][PlDb] |

## Installation

Instalasi dan Menjalankan project

```bash
  git clone https://github.com/RoisAntono/Transaksi-Single-Produk.git
```
Atau Download langsung
```bash
  https://github.com/RoisAntono/Transaksi-Single-Produk/archive/refs/heads/main.zip
```
Extract here RAR bernama ( **env dan vendor.rar** )
Atau
install composer untuk vendor
```bash
  composer install
```
copy .env.example kemudian rename jadi .env kemudian generate key
```bash
  php artisan key:generate
```
Buat database dengan nama inventarisd kemudian lanjut ke terminal lakukan migrate
```bash
  php artisan migrate
```
Untuk data seeder bisa lakukan command
```bash
  php artisan migrate:fresh --seed
```
Jalankan server LARAVEL
```bash
  php artisan serve
```
Buka melalui browser kalian dan boom, selesai

## FAQ

#### Apakah dapat saya gunakan untuk tugas saya?

Boleh, silahkan.

#### Apakah dapat saya modifikasi?

Boleh.

<!--## Support

<a href="https://www.buymeacoffee.com/roisantono" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/purple_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

<p>Atau</p> 

<a href="https://saweria.co/RoisAntono" target="_blank" alt="Saweria">
    <img src="https://saweria.co/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fcapy_happy.603c7293.svg&w=384&q=75" alt="Saweria" style="height: 41px !important;) !important;" >
</a>-->

## Feedback

If you have any feedback, please reach out to us at fake@fake.com

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>

