## Week 3: Unstructured Information Management Architecture

1. __UIMA Overview & SDK Setup__  
    - Before Class:
        + Finish Lecture 5: UIMA in IBM Watson
        + Read through the [one time setup](https://uima.apache.org/one-time-setup.html) instructions.
            * OSX comes with a SVN command line client, but unfortunately they do not include the JavaHL library so you will need to use HomeBrew or MacPorts (_i.e._ `brew install --universal --java subversion`) to install
            * Read through the installation instructions for [Subclipse](http://subclipse.tigris.org/servlets/ProjectProcess?pageID=p4wYuA) carefully. Notice that UIMA needs the 1.6.x or the 1.8.x SVN client but the Eclipse Marketplace only offers the latest version of Subclipse so you will have to follow [these](http://blog.zvikico.com/2009/07/ten-tips-for-installing-plugins-in-eclipse-galileo.html) instructions.
        + Read [Setting up the Eclipse IDE to work with UIMA](https://uima.apache.org/d/uimaj-current/overview_and_setup.html#ugr.ovv.eclipse_setup)
    - Lab:
        + Install 
            * SVN
            * Maven
            * Eclipse
            * Subclipse
            * m2e
            * UIMA
        + `HelloWorld` and `HelloWorldSWT` tutorials in Eclipse

2. __Annotators and Analysis Engines__ 
    - Before Class: Read [Chapter 1. Annotator and Analysis Engine Developer's Guide](https://uima.apache.org/d/uimaj-current/tutorials_and_users_guides.html#ugr.tug.aae)
    - Lab: Follow the instructions for [Writing My First UIMA Annotator](https://uima.apache.org/doc-uima-annotator.html)

3. __Building UIMA Analysis Engines__
    - Lab: Create a component that annotates email addresses (feel free to borrow a regex from the web, but be careful because Java regex ≠ Python regex) 

4. __Getting started with Watson Developer Cloud and Bluemix__
    - Before Class:
        + Browse the [Watson Services Documentation](http://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/doc/)
        + Read [Getting started with Watson Developer Cloud and Bluemix](http://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/doc/getting_started/)
        + Read [Getting started with the Personality Insights service](http://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/doc/personality-insights/)
    - Optional (recommended if you are doing a UIMA project): 
        + Read [Chapter 3. Application Developer's Guide](https://uima.apache.org/d/uimaj-current/tutorials_and_users_guides.html#ugr.tug.application)
        + Browse through [UIMA Addons components](https://uima.apache.org/sandbox.html)
    - Lab: 
        + [Sample Python Application for the IBM Watson Personality Insights Service](https://github.com/watson-developer-cloud/personality-insights-python)

