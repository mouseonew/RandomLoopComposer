# RandomLoopComposer

Allows you to discover loops in a song with a consistent BPM and arrange a new random song with your selections. The idea is that you'd create a song with sequencer software, set the mp3 in this, look for a new combination of loops to sequence, and use software like Audacity to record the results and remix the original song. It sounds better if you replace the mp3 with another song.

Best results can be had by saving 3-5 loops, a few of them breaks with a double click, test them out with the play saved button, remove the ones that don't mix well, and then save them as a group when a good mix is found. Then clear and create another group. When you play groups it'll randomly switch between the groups created.

An example of this code in action can be [seen here](http://realultimatetv.com/RandomLoopComposer/).

[![realultimatetv.com](http://mouseonew.com/image-rlc2.jpg?)](http://realultimatetv.com/RandomLoopComposer/) 

## Setup

In index.html look for these variables in the start function:

```
	function start(){
	
//#### VARIABLES ##################################

		//tested with this song, fade on: https://soundcloud.com/mitis/mitis-expose-original-mix MitiS - Expose (Original Mix) _Free Download_.mp3
		
		var 	beat =new Audio('mouseonew - discarded torch.mp3'); //main
		var 	beat2=new Audio('mouseonew - discarded torch.mp3'); //skip
		var 	beat3=new Audio('mouseonew - discarded torch.mp3'); //alternate main to fade
		//
		var 	beatMilliseconds=461.538*2; //130bpm 2bars
		var 	beatsMinMax=[1,8];
		var 	loopsMinMax=[4,6];
		var 	groupsMinMax=[3,6];
				fade=false;
			
//##################################################
```
