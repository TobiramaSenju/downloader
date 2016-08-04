# Manga Downloader

This downloads manga from [MangaReader](http://www.mangareader.net).

## Requirements

* Python 3.4

## How to use

* Edit the script to contain the name of the manga you want to download
  * IMPORTANT: each word must start with an uppercase letter
  * Examples:
    * `name = "One Piece"`
    * `name = "Fairy Tail"`
    * `name = "Bleach"`
* Run the script in the terminal
  * Syntax: `python3 script.py <OPT start_chapter> <OPT end_chapter>`
  * Examples:
    * All chapters: `python3 script.py`
    * Chapters 53 to the end: `python3 script.py 53`
    * Chapters 53 to 60: `python3 script.py 53 60`
