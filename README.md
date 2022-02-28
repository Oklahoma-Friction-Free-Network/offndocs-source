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
2. Clear out old static files `` npm run clean ``
3. Build html `` npm run build ``
4. Deploy static files to github `` npm run deploy ``
