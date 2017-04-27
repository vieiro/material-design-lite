# A fork of Material Design Lite

This is a fork of [Material Design Lite](https://getmdl.io/) with the following changes:

* Includes the excellent [mdl-selectfield](https://github.com/mebibou/mdl-selectfield) by mebibou (MIT License).
* Adds a new mdl-flow-grid container where mdl-flow-cells are inline-block components (see test/visual/test.html)
* Modifies media-query breakpoints for a nicer experience in iOS Devices:
    * Cards fit an iPhone screen of 320px with padding (card size changed to 304px)
    * tablet-desktop breakpoints make iPad's behave differently in portrait (tablet) and landscape (desktop).


## Building

Same building instructions as [MDL](https://getmdl.io/started/index.html#tab3):

    # Clone/copy the Material Design lite source code.
    git clone https://github.com/vieiro/material-design-lite.git
    # Go into the newly created folder containing the source code.
    cd material-design-lite
    # Install necessary dependencies.
    npm install && npm install -g gulp
    # Build a production version of the components.
    gulp
    


