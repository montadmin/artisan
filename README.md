# News

## Pages

-   [API](docs/api.md)

## Demo Login Details

-   Email : admin-0@gmail.com
-   Password : 12345678

### Create a New News Type


### Cache Driver setup 

- if CACHE_MODE set null data retireve form backend query 
- if set CACHE_MODE= "file" data retrive from file cache
- if set CACHE_MODE= "redis" data retrive from redis cache and also must connect with redis server


```cmd
git add .
git commit -m "get pull from main"
git pull origin main
chmod -R 777 ./
composer update
php artisan optimize:clear
php artisan migrate:fresh --seed

```

# install imagick extenstion
brew install pkg-config

pecl install imagick
brew install imagemagick
extension=imagick.so

# Installing Imagick Extension

This guide outlines the steps to install the Imagick extension for PHP. Imagick is a PHP extension that enables image processing and manipulation capabilities in PHP scripts.

## Prerequisites

Before installing Imagick, ensure you have the following prerequisites installed:

- [Homebrew](https://brew.sh/) (For macOS)
- [pkg-config](https://formulae.brew.sh/formula/pkg-config) (For macOS)

## Installation Steps

1. **Install pkg-config:**

```bash
   brew install pkg-config
```
pkg-config is a helper tool used when compiling applications and libraries. It helps manage the necessary compilation flags for the installed libraries.


Install Imagick Extension:
```bash
pecl install imagick
```
This command installs the Imagick PHP extension using PECL (PHP Extension Community Library), which is a repository for PHP extensions.


```bash
brew install imagemagick
```
ImageMagick is a powerful image manipulation library. The Imagick extension relies on ImageMagick for its underlying image processing capabilities.


## Enable the Imagick Extension:

Once Imagick is installed, you need to enable it in your PHP configuration. Locate your php.ini file and add the following line:

```bash
extension=imagick.so
```

## Verifying Installation
To verify that Imagick is installed and enabled correctly, you can run the following command in your terminal:
```bash
php -m | grep imagick
```


# Installing Imagick Extension on Windows
This guide outlines the steps to install the Imagick extension for PHP on Windows. Imagick is a PHP extension that enables image processing and manipulation capabilities in PHP scripts.
## Installation Steps

1. **Download Imagick DLL:**

   Download the appropriate DLL file for your PHP version and architecture from the [PECL repository](https://pecl.php.net/package/imagick). Make sure to select the version that matches your PHP version and architecture (e.g., x86 or x64).

2. **Copy DLL File:**

   Copy the downloaded DLL file (e.g., `php_imagick.dll`) to your PHP extensions directory. You can typically find this directory in your PHP installation folder under the `ext` directory (e.g., `C:\php\ext`).

3. **Enable the Imagick Extension:**

   Once the DLL file is copied, you need to enable the Imagick extension in your PHP configuration file (`php.ini`). Open your `php.ini` file in a text editor and add the following line:

```ini
   extension=php_imagick.dll
```

## Restart Web Server:

After enabling the Imagick extension, restart your web server (e.g., Apache or Nginx) to apply the changes.

##video type example
#$soundcloud
                        
<iframe width="100%" height="450" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/41395010&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false&amp;visual=true"></iframe>

vimeo
<iframe width="100%" height="550" src="https://player.vimeo.com/video/403530213" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen=""></iframe>
youtube

<iframe width="420" height="315"
src="https://www.youtube.com/embed/tgbNymZ7vqY">
</iframe>
