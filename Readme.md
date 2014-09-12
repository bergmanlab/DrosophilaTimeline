**History of Drosophila Genetics**

The fruitfly Drosophila melanogaster has made fundamental contributions to biology for more than 100 years. To place some of the significant events in the history of Drosophila genetics into context, this project aims to put these events into a web-based timeline. For a preview of the timeline while it is still a work-in-progress, click [here](http://htmlpreview.github.io/?https://raw.githubusercontent.com/cbergman/DrosophilaTimeline/master/timeline.html).

This timeline is being developed by Casey Bergman at the University of Manchester, using the [Timeline-Setter](https://github.com/propublica/timeline-setter/) package developed by ProPublica. 

To regenerate the timeline.html timeline from the DrosophilaTimeline.csv file, install Timeline-Setter as follows:

```
wget https://github.com/propublica/timeline-setter/archive/master.zip
unzip timeline-setter-master.zip 
cd timeline-setter-master
sudo gem install timeline_setter
```

Then from the directory containing DrosophilaTimeline.csv, run 
```
timeline-setter -c DrosophilaTimeline.csv
```