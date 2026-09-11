# image-dent.com - Original PHP Website

This repository contains the current live website of **IMAGE Dental Center** (`https://www.image-dent.com`) as PHP/HTML source files, ready for a developer to work on.

## What is inside

- `index.php` — Homepage
- `aboutus.php` — About page
- `services.php` — Services listing
- `doctors.php` — Doctors listing
- `gallery.php` — Photo gallery
- `article.php` — Articles / news
- `contact.php` — Contact page
- `privacy.php` — Privacy Policy
- `assets/` — CSS, JS, fonts, icons (to be copied from live server)
- `images/` — Doctor photos, gallery images (to be copied from live server)
- `.htaccess` — Apache/LiteSpeed rewrite rules for clean URLs

## Important note about assets

The live server blocks direct downloading of CSS/JS/images (returns 403). Therefore this repo includes the PHP/HTML page code but **not the actual assets**.

The developer must copy the `assets/` and `images/` folders from the live server into this repo using:
- cPanel File Manager (download as zip)
- FTP/SFTP credentials
- A backup from the hosting provider

## How to use this repo

1. Clone it locally.
2. Copy `assets/` and `images/` from the live server into the repo.
3. Run locally with any PHP server:
   ```bash
   php -S localhost:8000
   ```
4. Make edits to the PHP files.
5. Upload changed files back to the live server via FTP/cPanel/Git deployment.

## Deployment options

1. **Keep current hosting:** Developer edits files here, then uploads to the existing LiteSpeed server.
2. **Move to new hosting:** Upload this entire repo to a server with PHP + Apache/LiteSpeed.
3. **Convert to static HTML:** Replace PHP includes with plain HTML and host anywhere.
