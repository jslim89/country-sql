# About

A list of countries in in SQL form together with flags.

**Note that the flag image name is based on country ISO 2**

Feel free to contribute.

## Usage

### Import mysql

```sh
$ mysql -u root -p database_name < /path/to/mysql/country.sql
# enter your root password
```

### Resize the flags

#### Mac OS X

Example below shows to resize all images width to **44px**, its height will be scaled proportionally.

```sh
$ sips -Z 44 /path/to/flags/*.png
```

## Credits
Most of the countries flag are taken from [http://flagpedia.net](http://jsl.im/vbgpc).
Some of them taken from [Wikipedia](http://jsl.im/vkcau).

Coordinates get from Google API

`https://maps.googleapis.com/maps/api/geocode/json?components=country:Malaysia|administrative_area=Kuala+Lumpur&key=<API KEY>`

## License
The MIT License (MIT)

Copyright (c) 2014 - 2016 Js Lim

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
