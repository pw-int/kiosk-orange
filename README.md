### TheKiosk [PL Orange] Markup project for Dimoco ###

Markup project created by figma design.

Figma link [url](https://www.figma.com/file/fPP8kqT2vGBnwqvHk3zlAI/Poland-Orange_Mind%2B?type=design&node-id=27-3036&mode=design&t=HAkLM2GL1cDgAEOK-0 "Figma link")

Demo 3g link [url](https://pw-int.github.io/kiosk-orange/ "Demo 3g link")

Demo otp link [url](https://pw-int.github.io/kiosk-orange/otp.html "Demo otp link")


## Project structure ##

*src* directory contains source files, like styles, js, and html. Once project is compiled, the *dist* directory will be created and it should be used for the production project.

### Install nodeenv ###

**nodeenv** used to isolate the node versions on the system 

    pip3 install nodeenv

Create a virtualenv with the 18 nod version

    nodeenv -n 18.12.1 env

Active it 

    . env/bin/activate

### How to start the dev server for development? ###

    npm ci
    npm run dev


### How to build the assets? ###

    npm run build

