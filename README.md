SpamJS-Controller
=========
ManiaPlanet XML-RPC (Server controller) in Node.JS for Trackmania².

Installation instructions
=========
1. [Install Node.JS](http://nodejs.org/)
2. Download SpamJS-Controller and extract it somewhere
3. Execute *'npm install'* in the directory the *package.json* file is, or run *Install dependencies.cmd* if you're using Windows.
4. Open the just renamed *config.js* and set the four upper settings correctly.
5. Install MySQL and set up a database. Execute the *Sql/mysql.sql* file on the just made MySQL database.
6. Set the correct values in *config_database.js*.
7. Execute *'node controller.js'* in the directory the *controller.js* is inside. You can also just run *Run.bat* if you're using Windows.

Dependencies
=========
* [sax](http://search.npmjs.org/#/sax).
* [xmlbuilder](http://search.npmjs.org/#/xmlbuilder) (required for partial use of xmlrpc)
* [xmlrpc](http://search.npmjs.org/#/xmlrpc) (partial - serializer and deserializer, modified)
* [mysql](https://github.com/felixge/node-mysql/) (database)

Contributions
=========
Based on original [JsControl](https://github.com/MiniGod/JsControl) by [MiniGod](https://github.com/MiniGod)