# Week 8 -- Data Visualization with D3

> Throughout this week, you will learn how to make an interactive map of AirBnB listings in SF

Here are the material for week 8 of DSCI6008.  Much of the code/exercises will be working through public and open examples of other's charts and visualizations.  The purpose being twofold:

1. Data visualization is an inherently example driven (and inspiration driven) field
2. Educational to adapt someone else's work by deconstructing what they ahve done and rebuilding

To help facilitate this, I encourage you to use the following tools to rapidly experiment and iterate for yourself:
* [bl.ocks.org](http://bl.ocks.org/): D3.js Gist renderer and online community
* [Building Blocks](http://blockbuilder.org/about): In-browser interactive D3.js bl.ock editor
* [Tributary.io](http://tributary.io/): an experimental environment for rapidly prototyping visualization code

### The Data

The [data](http://insideairbnb.com/get-the-data.html) comes from [Inside AirBnB](http://insideairbnb.com/index.html) and it is available below under a [Creative Commons CC0 1.0 Universal (CC0 1.0) "Public Domain Dedication"](http://creativecommons.org/publicdomain/zero/1.0/) license.

> Inside AirBnB is an independent, non-commercial set of tools and data that allows you to explore how Airbnb is really being used in cities around the world.

## Day 1: Introduction to the Web, making visualization accessible

### Before Class

* [Data Visualization with D3.js: 1a Visualization Fundamentals](https://www.udacity.com/course/viewer#!/c-ud507/l-3068848585/m-3095208720)
* [Data Visualization with D3.js: 1b D3 Building Blocks](https://www.udacity.com/course/viewer#!/c-ud507/l-3168888599/m-3095208755)

### Theory

* Visual Encodings

#### Code

* HTML
* SVG
* CSS
* Javascript primer
* Introduction to D3: selections, mutation, and attributes

### Homework

* [DOM manipulation with D3](day1.md)
* Finish any of the Udacity video (Lesson 1) you haven't already watched.

## Day 2: Getting Started with Visualization

### Before Class

* [Data Visualization with D3.js: 2a Design Principles](https://www.udacity.com/course/viewer#!/c-ud507/l-3063188874)
* Data Visualization with D3.js: 3 Narrative Structures
  * [Demystifying D3](https://www.udacity.com/course/viewer#!/c-ud507/l-3069149263/m-3071139018) to [Styling Home Games with D3 Code](https://www.udacity.com/course/viewer#!/c-ud507/l-3069149263/e-3071139007/m-3071139008)

### Theory

* Process
      * Visualization Pipeline
      * EDA
* Design Principles, creating a visual vocabulary
      * Perception
      * Gestalt Principles
      
### Code

* Async data loading
* Data binding
* Scales + Axes
* Our first chart(s)!
    * line
    * bar
    * area
    * Choosing the right chart

### Homework

* Bar -> Line (for AirBnB listings)
* Stacked bar chart of types of listing per neighborhood
* Multiline chart for AirBnB listings (one for each neighborhood)
* Find a visualization that you would like to recreate
    * https://github.com/mbostock/d3/wiki/Gallery
    * https://t.co/qxQAjVqzuK

## Day 3: Data Narratives

### Before Class

* [Data Visualization with D3.js: 3 Narative Structures](https://www.udacity.com/course/viewer#!/c-ud507/l-3069149263/m-3071138957)
* [Extra: Narrative Visualization](http://vis.stanford.edu/files/2010-Narrative-InfoVis.pdf)

### Theory

* Adding Context
  * Juxtaposition
  * Linking (next day)
  * Annotation
* Narrative Structures
  * Author Driven
  * User Driven
  * Martini Glass
* Drill Down story
* Maps + Geographic Data

### Code

* Legends + Text
* Brushing
* Transitions
* Events/buttons

### Homework

* Animated Bar chart of growth of each neighborhood's listings
* Brushable line chart of AirBnB reviews
* Animated cartogram/choropleth of growth of listings
  * Extra credit: Use a [geographic grid](http://bl.ocks.org/mbostock/29cc3cc4078091fd2115)

## Day 4: Making it extensible

### Before Class

* [Data Visualization with D3.js: 4 Animation and Interaction](https://www.udacity.com/course/viewer#!/c-ud507/l-3066258748/m-3105808719)

### Theory

* Towards Reusable Charts
* Dashboards

### Code

* Visualization Servers
* Small multiples
* Linked Charts
* Crossfilter + dc.js
* Streaming Data with Rickshaw

### Homework

* Create a small-multiples line chart of each neighborhood's growth
* Create a linked map + line chart of each neighborhood

## The Future

* 3D and immersive VR/AR
* ML Visualized
* Large Scale Data Visualization
    * tile based
    * abstract rendering
* Data Art, generative visualizations
* Installation Art -- physical interaction
