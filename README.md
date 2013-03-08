expresslog
==========

Simple logger for using with ExpressJs

Usage
````
express.logger.format('expresslog', utils.expresslog);
app.use(express.logger('expresslog'));
````

Output
````
[Fri Mar 08 2013 22:42:12] GET : 200 3ms /
[Fri Mar 08 2013 22:42:12] GET : 304 6ms /stylesheets/style.css
[Fri Mar 08 2013 22:42:20] POST: 302 2ms /login
````
