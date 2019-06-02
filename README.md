# RandomLoopComposer

Allows you to discover loops in a song with a consistent BPM and arrange a new random song with your selections. An example of this code in action can be [seen here](http://realultimatetv.com/RandomLoopComposer/).

[![realultimatetv.com](http://mouseonew.com/image-rlc1.jpg?)](http://realultimatetv.com/RandomLoopComposer/) 

## Setup

In index.html look for these variables in the start function:

```
	function start(){
	
		var beat=new Audio('song_untitled_130bpm.mp3');
		var beat2=new Audio('song_untitled_130bpm.mp3');
		//
		var beatMilliseconds=461.538*2;//130bpm 2bars
		var loopsMinMax=[4,6];
		var beatsMinMax=[1,8];
```
