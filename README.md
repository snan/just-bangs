# Just Bangs

A clone of duck duck go, but with no index. Just the bangs!

## Installation and Usage

1. Install and start the server
    ```
    git clone https://github.com/thavelick/just-bangs
    cd just-bangs
    curl -fLO https://duckduckgo.com/bang.js
    ./just_bangs
    ```
2. Optionally, create a `custom-bang.js` file that will shadow the
   downloaded bangs. You only need the `t` and `u` fields on the
   custom bangs.
3. Open your browser to http://localhost:8484/
4. Append your search query to the url, with a bang:
   http://localhost:8484/gh!+just+bangs

## Dependencies
* Python 3.10
  * That's it
  * It probably works with most any Python 3.x but I didn't test it.

## Created By
* [Idiomdrottning](https://idiomdrottning.org/about) - idea, finding the bangs data file, adding `custom-bang.js`
* Tristan Havelick ([@Natris1979@social.linux.pizza](https://social.linux.pizza/@Natris1979)) - programming

## TODO
* Add environment variables for:
  * Location of bangs file
  * Port
* Add a homepage with a simple search box
* Make a cute logo and put it on the homepage
