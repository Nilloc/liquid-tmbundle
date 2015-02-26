# Liquid for Shopify TextMate bundle

To install with Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/Nilloc/liquid-tmbundle.git "Liquid-for-Shopify.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

To updated with Git:

    cd ~/Library/Application\ Support/TextMate/Bundles/Liquid-for-Shopify.tmbundle
    git pull origin master
    osascript -e 'tell app "TextMate" to reload bundles'


To install without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget http://github.com/Nilloc/liquid-tmbundle/tarball/master
    tar zxf nilloc-liquid-tmbundle*.tar.gz
    rm nilloc-liquid-tmbundle*.tar.gz
    mv nilloc-liquid-tmbundle* "Liquid.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'


Mirrored from: <http://blog.radixhound.com/2007/1/31/liquid-textmate-bundle>