# tpf-loader
Movu JS library for loading Movu form widget on third party web-sites.

## clean install
    $ cd development
    $ npm install
    
## run tests
    $ cd development
    $ grunt test

## build
    $ cd development
    $ grunt build
if build is success files for production are in ROOT\dest
## run development server
    $ cd development
    $ node our_server.js
You can edit widget file and testit on localhost:3002/autoinit

## Options
    data-autoinit="true" 
    data-customer-id="customer id"
    
## Example

    <html>
      <head>
        <script type="text/javascript" src="/js/movu-widget.js"></script>
      </head>
      <body>
        <!-- autoload init -->
        <div id="movu-embedded-widget-holder" data-autoinit="true" data-customer-id="adasaddasd"></div>
      </body>
    </html>

    

