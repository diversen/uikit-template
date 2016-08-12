# uikit-template 

Playing around with uikit. This is just a repo to see how to set up a uikit development env for creating a uikit 
template. The template is not for public use, only if you want a crappy looking template .)

    git clone https://github.com/uikit/uikit

Enter `uikit` and clone template into `custom`

    cd uikit && git clone https://github.com/diversen/uikit-template custom

Inside `custom` the template exists - called `blue`

(Only changes are in `blue/core/base.less` - smallere font, grey background)

Build the `blue` template

    gulp dist -t blue 

css files are now available in `dist/`

