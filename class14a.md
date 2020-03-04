# Transitions
_for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes._

**Transitional Property**
_The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties. By default, all of the properties within an element’s different states will be altered upon change. However, only the properties identified within the transition-property value will be affected by any transitions._

1. .box {
2.  background: #2db34a;
3.  border-radius: 6px
4.    transition-property: background, border-radius;
5.    transition-duration: 1s;
6.    transition-timing-function: linear;
7.  }
8.  .box:hover {
9.    background: #ff7b29;
10.   border-radius: 50%;
11.   }

## CSS3 has introduced countless possibilities for UX designers, and the best thing about them is that the coolest parts are really simple to implement.

+ Just a couple of lines of code will give you an awesome transition effect that will excite your users, increase engagement and ultimately, when used well, increase your conversions. What’s more, these effects are hardware accelerated, and a progressive enhancement that you can use right now.

+ Here are 8 really simple effects that will add life to your UI and smiles to your users’ faces.

+ All of these effects (bar one) are controlled with the transition property. So we can see these effects working, we’ll set up a div in an HTML page:

1. fade in 
2. .fade
+ {
+         opacity:0.5;
+ }
+ .fade:hover
+ {
+         opacity:1;
+ }

2. change color 
3. grow and shrink 
4. rotate elements 
5. square to circle 
6. 3D shadow
7. Swing
8. Inset border

#### 
@import url(https://fonts.googleapis.com/css?family=Droid+Sans:700);
1.		*{
2.			margin: 0;
3.			padding: 0;
4.			box-sizing: border-box;
5.			transition: all .1s;
6.		}
7.		body{
8.		background-color: #424242;
9.			font-family: 'Droid Sans', sans-serif;
10.		}
11.		.group{
12.			text-align: center;
13.			margin: 20px auto;
14.		}
15.		.group button{
16.			margin-top: 10px;
17.		}
18.		button{
19.			box-sizing: border-box;*/
20.			background: NONE;
21.			border: none;
22.			outline: none;
23.			border-radius: 3px;
24.			padding: 15px 70px;
25.			color:white;
26.			text-transform: uppercase;
			font-weight: 700;
			text-shadow: 0 1px 3px rgba(0, 0, 0, 0.41);
			box-shadow: 0 3px 0 0 #383838;
			border:3px solid transparent;
			
		
			animation: pulse 1s linear infinite alternate;
			-webkit-animation: pulse 1s linear infinite alternate;
		}
		.active,
		button:active{
			background-image: linear-gradient(rgba(0,0,0,.1) 13%, transparent 13%,transparent);
			box-shadow: 0 1px 0 0 #383838;
			color: rgba(0, 0, 0,.45);
			text-shadow: none;
			
			
			-webkit-animation-play-state: paused; 
    	animation-play-state: paused;
		}
		button:focus,
		button:hover{
			-webkit-animation-play-state: paused; 
    	animation-play-state: paused;
		}
		
		
		.blam:focus,
		.blam:hover{
			background-color:#0097bd;
		}
		.blam{
			background-color:#00bff0;
			border-color: #00bff0;
		}
		
		.syke:focus,
		.syke:hover{
			background-color:#ad4e4e;
		}
		.syke{
			background-color:#e06464;
			border-color:#e06464;
		}
		
		.later:focus,
		.later:hover{
			background-color:#7c8b8f;
		}
		.later{
			background-color:#a8bdc2;
			border-color:#a8bdc2;
		}
		
		@-webkit-keyframes pulse {
			100% {
				transform: translateY(6.9px); 
			} 
		}

		@keyframes pulse {
			100% {
				transform: translateY(6.9px); 
			} 
		}

**there a way to do animation by frame keyframe and pure css rules**

