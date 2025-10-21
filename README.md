# Structurize Viewer

This is a basic utility that takes in a .blueprint file, reads in the nbt data, processes it , and then renders the resulting structure using [DeepSlate](https://github.com/misode/deepslate). It's not intended to be a fully featured tool, just a simple thing hacked together to allow viewing Minecolonies and Structurize .blueprints in the browser/without having to boot up minecraft.

Load in the schematic with the upload button (or drag and drop) OR by pasting a URL into the text bar and hit submit. You can navigate the loaded schematic using WASD and shift/space to move around, and left click / middle click to drag the camera/view (check settings for this). There is also basic mobile device support with standard touch controls. You can also set which layers are rendered using the two sliders on the left, which may be useful for layer-by-layer building, and there is a button for a (very crude) material list, which you can also download as a CSV file.

Limitations:
* We'll find out!

For comments/suggestions/bugs, best thing to do is create an issue on [Github](https://github.com/acockerham/structurize-viewer/). 

This is a current obsession of mine, and I'm not sure how much further I will take it once it does the bare minimum I need.  But I am open to PRs and discussion.

To run locally, use rubygem for github pages
https://kbroman.org/simple_site/pages/local_test.html

install ruby
gem install github-pages
to update: gem update github-pages
jekyll build
jekyll serve


To deploy to github pages, used settings > pages.  pretty sure it will automatically redeploy after pushing to main