## What is Cloudy With A Chance Of Tests?

Cloudy With A Chance Of Tests is a pared down ant build.xml. This build.xml can be used for Continuous Integration with ColdFusion (with or without unit tests). A syntax and other specific CFML inspections will occur setting the stage for testing and other progressions in the build.xml and your code base.

Some targets in the build.xml are purposely left blank for place holders. 

The build.xml should be able to be used without any CFML code changes to your code base and only a few changes to build.properties that match your environment. 

Have fun, this is a journey not a sprint. Introduce this easy step, sit back and wait till your opportunity to do more Continuous Integration.

## Recorded Presentation, Slides, and Outline

Recorded Presentation - ???

Slides - ???

Outline - https://docs.google.com/document/d/1biLTSfLfZxdwLI78Jo2lID_w-pKAqnR63csfu8mT9EA/edit

## Installation

This build script is decoupled from the environment you can execute it in. You can use the command prompt, Eclipse IDE, or Jenkins with just a few changes to build.properties. 

1) Please add the build.xml to your source control system in your top level folder and build.properties but ignore it from your scs. 

2) You will have to change some build.properties settings to match the environment it will run on.

3) Add the lib folder with the jars at the top level of the project. 

4) To run the VarScope and QueryParam, you will need to download and place them in the top level of the web server (not just the project top level). I would recommend excluding them from your source control system.

* http://varscoper.riaforge.org/

* http://qpscanner.riaforge.org/

## License

This is licensed under [Creative CommonsAttribution-Noncommercial-Share Alike 3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/us/) except for third party software which retains their licenses. 

## Contributors / Originators

Please add yourself if you help:

* @denstar

* @vitrix

* @lmajano

## Git Workflow for Contributors

This project uses the excellent [Git Workflow series](http://www.silverwareconsulting.com/index.cfm/Git-Workflow) by [Bob Silverburg](https://github.com/bobsilverberg/) for contributions.