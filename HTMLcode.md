Heres the code for the web page just save it as HTML and open it in crome

<!DOCTYPE html>


&lt;html&gt;




&lt;head&gt;




&lt;script class="jsbin" src="http://ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js"&gt;



&lt;/script&gt;




&lt;meta charset=utf-8 /&gt;




&lt;title&gt;

JS Bin

&lt;/title&gt;


<!--[IE](if.md)>
> 

&lt;script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"&gt;



&lt;/script&gt;


<![endif](endif.md)-->


&lt;style&gt;


.vid{
position:absolute;
top:30px;
left: 650px;
width:500px;
height:430px;
border: double;
}

.ppt{
position:absolute;
top:30px;
left: 100px;
width:500px;
height:430px;
border: double;
}
.stt{
position:absolute;
top:480px;
left: 350px;
width:650px;
height:200px;
<!--border: double;-->
}
> article, aside, figure, footer, header, hgroup,
> menu, nav, section { display: block; }
> body {font-family:Arial; padding: 30px;}
> input { padding: 5px 10px; width: 300px; }
> .response { padding:20px; background-color: #EFEFEF; margin-top: 20px; border-radius: 8px; display:none; }
> .response h2 {margin: 0 0 10px 0;}


&lt;/style&gt;




&lt;style id="jsbin-css"&gt;



&lt;/style&gt;



&lt;/head&gt;




&lt;body&gt;



<div>
<h2>Powerpoint of Lecture here</h2>
</div>

<div>
<h2>Video of lecturer here</h2>
<!--<video width="320"  height="180" src="<a href='http://www.youtube.com/demo/google_main.mp4'>http://www.youtube.com/demo/google_main.mp4</a>"  controls autobuffer> <br>
<br>
Unknown end tag for </video><br>
<br>
--><br>
<br>
<br>
<object classid="clsid:d27cdb6e-ae6d-11cf-96b8-444553540000" width="320" height="180" codebase="http://download.macromedia.com/pub/shockwave/cabs/flash/swflash.cab#version=6,0,40,0"><br>
<br>
<br>
<br>
<br>
<param name="allowFullScreen" value="true" /><br>
<br>
<br>
<br>
<br>
<param name="allowscriptaccess" value="always" /><br>
<br>
<br>
<br>
<br>
<param name="src" value="http://www.youtube.com/v/oHg5SJYRHA0&hl=en&fs=1&" /><br>
<br>
<br>
<br>
<br>
<param name="allowfullscreen" value="true" /><br>
<br>
<br>
<br>
<br>
<embed type="application/x-shockwave-flash" width="425" height="344" src="http://www.youtube.com/v/oHg5SJYRHA0&hl=en&fs=1&" allowscriptaccess="always" allowfullscreen="true"><br>
<br>
<br>
<br>
<br>
</embed><br>
<br>
<br>
<br>
<br>
</object><br>
<br>
<br>
</div>

<div>
<blockquote>

<label for="txtSearch">

Pretend your the lecturer:<br>
<br>
</label><br>
<br>
<br>
<input type="text" id="txtSearch" x-webkit-speech /><br>
<div></div>
</div>
<br>
<br>
<script><br>
<br>
<br>
$(document).ready(function() {</blockquote>

> $("#txtSearch").bind(
> > "webkitspeechchange",
> > function(evt) {


> $(".response")
> > .html(
> > > "<h2>Lecturer said</h2>" + $(this).val())

> > .fadeIn();

> });
});


&lt;/script&gt;




&lt;script src="http://static.jsbin.com/js/render/edit.js"&gt;



&lt;/script&gt;




&lt;script src="http://static.jsbin.com/js/vendor/eventsource.js"&gt;



&lt;/script&gt;




&lt;script src="http://static.jsbin.com/js/spike.js"&gt;



&lt;/script&gt;




&lt;script&gt;


var _gaq =_gaq || [.md](.md);
_gaq.push(['_setAccount', 'UA-1656750-13']);
_gaq.push(['_trackPageview']);

(function() {
> var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
> ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
> (document.getElementsByTagName('head')[0](0.md) || document.getElementsByTagName('body')[0](0.md)).appendChild(ga);
})();


&lt;/script&gt;





&lt;/body&gt;




&lt;/html&gt;

