PresentationTimetable.js
========================

Presentationtimetable syncs [SpeackerDeck](http://speackerdeck.com) presentations with YouTube videos using a time/slide table.


### Example Usage
	$(document).ready(function(){
		$.ptt({
			timetable: {'00:08':'2', '00:14':'3', '00:15':'6', '00:16':'7', '00:17':'8', '00:18':'9', '00:19':'10', '00:20':'11'},
			video_container:'ytapiplayer',
			ytvideo_url: 'http://www.youtube.com/v/gxeT8vX5FFc',
			video_width:'430',
			video_height:'393',
		});
	})

### Requirements
	<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/swfobject/2.2/swfobject.js"></script>
	<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>

### TODO
- Embed SpeackerDeck through PTT
- Support more than one Presentation/Video combo on a single page


Licensing
---------
PresentationTimetable is released under the MIT License.