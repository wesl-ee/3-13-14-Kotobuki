3-13-14寿
========

Static HTML gallery generator. Create a simple website from a folder of
pictures.

Dependencies
------------

There are a few things to get make sure you have before we begin

### Basics

- Web server
- Perl 5
- ImageMagick

If you are a gentle and blessed soul using a source-based package manager
(i.e. portage) please ensure that

### Perl Modules

Install these either globally or locally (for the user running 3-13-14寿)
using cpan or any other technique.

- HTML::Template
- Image::ExifTool
- Image::Magick::Thumbnail
- File::Find
- File::Basename
- Config::IniFiles

Installation
------------

First, create an empty directory which your web server can access and serve.
This is where your static HTML pages will go.

Next, move your pictures (or if you are fancy, use _symbolic_links_) so they
are accessible by your webserver. These may be put in a subdirectory of the
directory you created earlier. Please ensure that you can access your
pictures on-line by using a web browser.

Then copy `config.example.ini` to `config.ini` and make adjustments as
necessary. Finally run `gallery-create` to generate your website in the `www`
folder that you specified.

Author
------
3-13-14寿 is authored by Wesley Coakley.

License
-------
Modified BSD 3-clause license. See `LICENSE` for more details
