# Science Communication static site

## install pelican

[from the quickstart guide](http://docs.getpelican.com/en/3.6.3/quickstart.html)

    pip install pelican markdown

## install plugins

    git clone git@github.com:getpelican/pelican-plugins.git

## install images

    cd content
    unzip images.zip

## generate content

    cd www
    pelican content -t theme

## serve...

    cd output
    python -mSimpleHTTPServer
