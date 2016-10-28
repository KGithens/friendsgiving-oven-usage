```mermaid
gantt
	dateFormat hh-mm
    title Friendsgiving Oven Usage

    section Katie
    Turkey           :crit, turkey, 09-30, 5h % start at 9:30 am
    section Mike
    Potatoes      	 :after turkey  , 2h
```

This text file turns into an HTML gantt chart. View that chart [here](https://rawgit.com/mogenson/friendsgiving-oven-usage/master/gantt.html).

The chart is written in Markdown using [mermaid](https://knsv.github.io/mermaid/).

The HTML is generated with [Typora](http://www.typora.io/).