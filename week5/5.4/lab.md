Lab
--------

### Basic: [API and Demo Documentation](http://maggie.lt.informatik.tu-darmstadt.de/jobimtext/jobimviz-web-demo/api-and-demo-documentation/)  
1. Try the [Web Demo](http://maggie.lt.informatik.tu-darmstadt.de:10080/jobim/)
2. Try the examples. _e.g._
	- [Sentence processing with default JSON output](http://maggie.lt.informatik.tu-darmstadt.de:10080/jobim/ws/holing?s=The%20cat%20chases%20mice)
	- [ISAs for cat#NN](http://maggie.lt.informatik.tu-darmstadt.de:10080/jobim/ws/api/stanford/jo/isas/cat%23NN?format=rdf)
	- [Related features for mouse#NN](http://maggie.lt.informatik.tu-darmstadt.de:10080/jobim/ws/api/stanford/jo/bim/score/mouse%23NN?format=tsv)
3. Hack the URLs to try other sentences and terms.
4. Optional: Use [RESTClient](http://restclient.net/) to experiment more with API
5. Programmatically get and parse JSON data from API using Python 

### Advanced: [JoBimText Tutorial](https://sites.google.com/site/jobimtexttutorial/resources)  
1. D/L and install [Virtual Box](https://www.virtualbox.org/wiki/Downloads)
2. D/L and extract the [prepared VM image](https://sourceforge.net/projects/jobimtextgpl.jobimtext.p/files/hadoop-VM/)
3. Follow the instructions and terminal commands in [JoBimText-Tutorial-Practice-Commands.txt](http://maggie.lt.informatik.tu-darmstadt.de/jobimtext/wordpress/wp-content/uploads/2014/04/JoBimText-Tutorial-Practice-Commands.txt)
	- Warning: Upload corpus is _two_ (2) commands:
		1. `hadoop fs -mkdir mouse_corpus`
		2. `hadoop fs -put mouse_corpus mouse_corpus/corpus.txt`
	- replace `HOLING_OPERATION` with a holing operation (I did `stanford`)
	- Notice: `sh corpus_stanford_s0.0_f2_w2_wf0_wpfmax1000_wpfmin2_p1000_sc_one_LMI_simsort_ms_2_l200.sh ` took me 30 min.
