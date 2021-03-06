# Method #1: Direct Huffman

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

If you use this method in your work, please cite the DBDP: dbdp.org and the references at the bottom of this page.

This method uses Butterworth filter and resampling to preprocess the raw data. And then applies the Huffman encoding directly on the quantized data without any transfermation.

The detailed steps are listed in the code by comments and markdown.


### Instructions

Input the signal to be compressed and define the parameters listed below

1. Sampling frequency
2. Decimal in quantization
3. Useful length of the signal
4. Name of the saved files


Dependencies:

```sh
matplotlib.pyplot
pandas
numpy
scipy
os
```

### Evaluation

The results of this method on the following wearable sensors:

| Wearable Sensor | Compression Ratio | Percentage RMS difference |
| ------ | ------ | ------ | 
| ECG | 55.5 | 1.02 |
| PPG | 13.68 | 0.22 |
| ACC | 10.99 | 0.02 |
| EDA | 12.34 | 0.49 |
| TEMP | 11.94 | 0.45 |



### References

Rajankar, S.O., Talbar, S.N. An electrocardiogram signal compression techniques: a comprehensive review. Analog Integr Circ Sig Process 98, 59–74 (2019). https://doi.org/10.1007/s10470-018-1323-1

tcmpr 0.2, Konrad Poreba: https://tcmpr.readthedocs.io/en/latest/index.html
PyPI: https://pypi.org/project/tcmpr/


License
----

MIT



[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
