# RandomLoopComposer

Allows you to discover loops in a song with a consistent BPM and arrange a new random song with your selections. The idea is that you'd create a song with sequencer software, set the mp3 in this, look for a new combination of loops to sequence, and use Audacity to record the results and remix the original song. An example of this code in action can be [seen here](http://realultimatetv.com/RandomLoopComposer/).

[![realultimatetv.com](http://mouseonew.com/image-rlc2.jpg?)](http://realultimatetv.com/RandomLoopComposer/) 

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
