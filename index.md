<!DOCTYPE html>
<html>
<head>
<style>
*{font-family: Helvetica, sans-serif;
		}
.item1 { grid-area: header; 
	background-image: url("bilder/header.png"); 
	height: 750px;
  	background-position: center;
	background-repeat: no-repeat; 
	background-size: cover;
  	position: relative;}
.item2 { grid-area: main1; }
.item3 { grid-area: right; margin-right: 60px;}
.item9 { grid-area: right1; margin-left:0px; margin-right: 60px;}
.item4 { grid-area: mitten1; background-color: #000000;color: orange;}
.item5 { grid-area: main; }
.item6 { grid-area: mitten2;}
.item10 {grid-area: mitten3; 
	background-image: url("bilder/footer.png"); 
	height: 500px;
  	background-position: center;
	background-repeat: no-repeat; 
	background-size: cover;
  	position: relative;}
.item11 { grid-area: mitten0;}

.item7 { grid-area: footer; background-color: #000000; color: white;}

.item8 { grid-area: footer2; background-color: #000000; color: white;}

.card-img-1 {
    height:100%;
    width: 100%; 
    }
.card-img-3{margin-left: 150px;}


article	{
	color:grey;	
	text-align:right;
	font-size: 150%;
	margin-right: 250px;
		}

.grid-container {
  display: grid;
  grid-template-areas:
    	' header header header  header'
	' mitten0 mitten0 mitten0  mitten0'
	' main1 main1 right right'
	' mitten1 mitten1 mitten1 mitten1'
    	' main main right1 right1'
	' mitten2 mitten2 mitten2 mitten2'
	' mitten3 mitten3 mitten3 mitten3'
    	' footer footer footer2 footer2';
  grid-gap: 0px;
 background-color: #FFFFFF;
  padding: 0px;
}

.grid-container > div {

  text-align: left;
  padding: 0px 0;
	background-color: #ffffff;
 }

p {color:grey; 
	font-size: 120%;
	margin-right: 80px;
	text-align:right;
	}
.p1 { margin-top: 100px; margin-left: 10px;  text-align:right;}
.p2 { margin-left: 150px; margin-right: 20px; text-align:left;}
.p20 { margin-left: 150px; margin-right: 20px; text-align:left;margin-bottom:100px;}
.p3 { margin-left: 150px; margin-right: 150px; text-align:left;}
.p4 { position: absolute;
  	top: 50%;
  	left: 50%;
  	transform: translate(-50%, -50%);
	text-align:center;
 	}
.p5 { position: absolute;
  	top: 10%;
  	left: 50%;
  	transform: translate(-50%, -50%);
	text-align:center;
 	}
.p6 { position: absolute;
  	top: 95%;
  	left: 60%;
  	transform: translate(-50%, -50%);
	text-align:center;
 	}


#grey {color:grey;font-size:20px;}

#svart {background-color: #000000;height:400px;}
#right {margin-right:40%;}

.youtube {margin-top: 100px;}

.svart {background-color: #000000; height: 600px;}

.video-responsive{
    overflow:hidden;
    padding-bottom:56.25%;
    position:relative;
    height:0;
}
.video-responsive iframe{
    left:0;
    top:0;
    height:100%;
    width:100%;
    position:absolute;
}

.p0 {
  	margin-left:40%;
	margin-right:20%;
	margin-top:100px;
	text-align:left;
	
	background-color: #000000; color:white;
	}
.livestream2 {
	
	margin-right:40%;
	margin-top:150px;
	
	text-align:right;
	background-color: #000000; 
	
	}
.p7 { 
	text-align:left;
	margin-left:40%;
	margin-right:20%;
	color:white;
 	}
.p8 { 
	text-align:right;
	
	color:black;
 	}

</style>
</head>



<body>
<p>This grid layout contains four columns and åtta rows:</p>

<div class="grid-container">
  	<div class="item1">
		<div class="p5">
			<h2>Voodoo</h2>
		</div>
		<div class="p6">	
			<h1> 
				Hey guys, 
			</h1>
		</div>
		

	</div>
	<div class="item11">
			
			<article>
				This week we’ll be discussing the concept of <strong>"Youtubability"</strong>- 				 
			</article>
			<article>
    			another important game guideline. 
			</article>
		
	</div>
  	<div class="item2">
		<div class="youtube">
		
			<h2 class="p2">
    				Youtubability
			</h2>
			
			
				<p class="p2">
    				A key driver of youtubability is <strong>the clarity of your gameplay 				</strong>to a potential player.
				</p>
				<p class="p2">
				Gameplay clarity will help you achieve the full potential of your 		game by working on getting <strong>the lowest possible CPIs </strong>for your games.
			</p>
			<p class="p2">
				Many elements can be used to make your game clearer :
			</p>
			<p class="p2">	
				For instance, ask yourself if a user’s interaction with the game is 						<strong>evident</strong>, for example, can she tell which character she 					<strong>controls</strong>? Is the <strong>objective clear?</strong> Does it
    				look <strong>fun to play?</strong> Has she understood the game after 1 second 					(great!) or after 10 seconds (too long!).
			</p>
			<p class="p20">
				Make sure to <strong>use colours</strong> to help indicate the gameplay rules. 				For instance, in Helix Jump, obstacles are <strong>clearly contrasted</strong> 				(in orange here) and instantly recognized as a threat.
			
			</p>
		
		</div>
		
	</div>

  	<div class="item3"><img class="card-img-2" src= "bilder/phone1.png" alt=""></div>  
	<div class="item4">	
		<nav class="svart">
			Mitten1
			<div class="video-responsive">
    				<iframe width="420" height="315" src="bilder/video_comp.mp4" frameborder="0" allowfullscreen></iframe>
			</div>
			
		</nav>
	</div> 
	<div class="item5"><img class="card-img-3" src= "bilder/phone2.png" alt=""></div>
	<div class="item9">
		<p class="p1"> 
			<p> 
			If you want to run user tests with friends and family or even random
			people in the street, it is interesting to show them the 30 second video before
			making them try to prototype in order to <strong>understand their 						</strong>expectations from the video vs. the actual game they try.
			</p>
			<p>	
			<strong>Make it obvious </strong> with visual elements that help <strong>understand 				the objective and controls </strong> of the game, like with the target used in 					Viatcheslav Tarasov’s Purple Diver or Fabrika Games’ Draw Car with the space dedicated 			to drawing.
			</p>
			
		</p>
		
	</div> 

  
	<div class="item6">

			<p class="p3">	
			People will be watching the gameplay videos of your games <strong>on their
			phone’s Facebook feed</strong>, everything will seem smaller than when displayed in 			Unity or as a video on your computer screen. <strong>You should also consider whether 			your gameplay video is understandable if someone watches it on a smallscreen.</strong>  With 			an average watch time of 3 to 5 seconds, this is an <strong>accelerated elevator 			pitch!</strong>
			</p>
			<p class="p3">
			Think of the moment when you decide to click on a random video on YouTube just because 			it has an attractive thumbnail - it’s the same idea for your game videos.
			</p>
			
	</div>
	<div class="item10">
			<h1></h1>
			
			
		<div class="p4">
    			<h1 style="font-size:50px">Tip of the week</h1>
    			<div id="grey">
				Livestreams we hold every two weeks are an interesting resource for you
				to consult. There are plenty of relevant subjects covered to guide and
				orient you towards best practices and they are <strong>all replayable on the
				dashboard </strong>so don’t hesitate to check them out!
			</div>
    
  		</div>
	</div>
  	<div class="item7" id="svart">
		
		<div class="p0">  
			<h2> Livestream </h2>
			<div>
			The next publishing livestream will
        		be held this Thursday (7th November)at 3pm CET (Paris time).
			</div>
			<div class="p8"> 
        			You’ll receive a reminder e-mail tomorrow.
			
			</div>
			<div> 
        			You’ll receive a reminder e-mail tomorrow.
			</div>
		</div>
	</div>
	<div class="item8" id="svart">
		<p class="livestream2">
			
			<div> <em>We look forward to seeing</em></div>
			<div> <em>your next prototype!</em></div>
			
			<div class="p8"> 	
			<em>The Publishing team</em>
			</div>
    			<div> 	
			<em>The Publishing team</em>
			</div>
		
		</p>
		
	</div>
</div>

</body>
</html>
