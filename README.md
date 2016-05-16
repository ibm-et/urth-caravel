Install
=======

Install and start separate caravel server.  Must run example with same-domain policy disabled, e.g.

  Google\ Chrome --disable-web-security --user-data-dir=/tmp

To build assets for this widget:

  npm install; cd assets; npm install; npm run prod; rm -rf node_modules assets/node_modules 

  //TODO:
  // fix installation so webpack runs automatically
  // docker will not start unless node_modules are removed, not sure why
  // stylesheets aren't building, only js
  // need to migrate caravel server-side to run in kernel with comm proxy