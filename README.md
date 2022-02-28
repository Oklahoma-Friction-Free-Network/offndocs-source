# OFFN Documentation

## Development requirements:
* nodejs
* npm
* python-sphinx

## Development setup:
1. Clone this repo `` git clone https://github.com/Oklahoma-Friction-Free-Network/offndocs-source ``
2. cd into source directory `` cd offndocs-source ``
3. Install node packages `` npm i ``

## Build:
1. Modify files in `` src  ``
2. Run `` npm run clean `` to clear out old static files
3. Run `` npm run build `` to build html in `` build/html ``
4. Run `` npm run deploy `` to deploy statif files to github
