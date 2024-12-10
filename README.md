# Synteruptor web

## Description

This is a website tool to help explore Synteruptor databases.

## Installation

Install this web folder and use it in a PHP based website (e.g. in public_html to use it locally).

### Local instance

Requirements: php & php-sqlite3 should be installed on your computer

1. Clone this web folder
2. Create a `db` directory within this folder or adjust the path in the `settings.ini` file if you want to use another directory
3. Add your databases (*sqlite files) to this directory (NB: if their name is `mgnXXXXXX.sqlite`, then they won't appear in the main exploration table but you'll be able to access them using the direct link <http://127.0.0.1:8000/summary.php?version=mgnXXXXXX>)
4. Run `php -S 127.0.0.1:8000` from within the cloned directory
5. Open the provided link (<http://127.0.0.1:8000/>) in any web browser

## Usage

Put database files created by the Synteruptor scripts in the db folder to access them in the website.
