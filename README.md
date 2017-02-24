# Duniter button

[![Ğ1 button](https://cdn.rawgit.com/duniter/duniter_button/e9c04159/duniter_button.svg)](https://g1.duniter.fr/#/app/wot/GfKERHnJTYzKhKUma5h1uWhetbA8yHKymhVH2raf2aCP/Moul)

## URI

```bash
duniter://currency_name:public_key
```

This URI could open Duniter wallets like Cesium or Sakia.

## Install on my website

- Retrieve the image:

```bash
wget https://raw.githubusercontent.com/duniter/duniter_button/master/duniter_button.svg
```

- Add following line on your website replacing _currency_name_, _public_key_ and _path/to/_ arguments:
 - With Cesium link:

```html
<a href="https://g1.duniter.fr/#/app/wot/public_key/identity"><img src="path/to/duniter_button.svg" /></a>
```

 - With URI:

```html
<a href="duniter://currency_name:public_key"><img src="path/to/duniter_button.svg" /></a>
```

## License
This work is under GNU GPLv3 license.
