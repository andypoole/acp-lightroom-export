# acp-lightroom-export
This is a simple Lightroom web engine template plugin that will allow exporting and uploading a web album that fits within the SSI template I use on my website.

# Installation
Installation is pretty straightforward.  Simply copy the acp.lrwebengine directory into your user's Web Galleries directory.  Usual locations for this are:

Windows: `%APPDATA%\Adobe\Lightroom\Web Galleries`

Mac OS: `~/Library/Application Support/Adobe/Lightroom/Web Galleries`

# Usage
After installation, an "Andrew Poole" option will appear in the layout style panel of Lightroom's Web module.  The preview within Lightroom will look a little broken, but that's because the SSI template only works once it's uploaded.  You'll want to edit it for your own website's setup before using it properly.

The most obvious first job will be to edit the SSI to point at your own template header/footer.  This is fairly striaghtforward and self-explanitory in the grid.html and large.html files.  You'll also want to create some CSS for the various classes used in the templates.

# Sample output
A working example of this can be found on [my website's photo pages](http://www.andrewpoole.org.uk/photos/).  It should be noted that the index of albums is not managed by this template - only the albums and images contained within.