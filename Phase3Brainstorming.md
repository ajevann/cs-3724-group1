<h1>Phase 3 Interaction Brainstorming</h1>

<h2> Introduction </h2>
<p>
This page contains a written description of the brainstorming we did about interaction design. Both ideas that we rejected and the final design that we decided upon are included. It contains explanations for all the key elements of our interaction design. It includes justification and design rationale. Finally, it includes information about the results of our client meeting with respect to interaction design. </p>

<h2>Brainstorming </h2>
<p>
Our brainstorming session for interaction design proved to be very fruitful for our group's final design. Our group came up with several interesting ideas, all of which were incorporated into the final design of this phase.</p>

<p>
One of the first ideas produced by our brainstorming session was the idea of a menu/form based system. At first we followed the metaphor that creating an event is like filling out a form or picking something from a menu, having the user select which options he/she wanted to complete the event. This type of interaction would give the user a highly structured way of inputting events to the system with a simple pointing device that could be easily used while focusing attention on the game.<br>
<br>
This immediately gave way to the idea that we could have a set of buttons available to the user that would outline all of their options for event creation. However, one problem we encountered with this menu style was that during our requirements analysis it became apparent that end-users (people watching the game online) wanted a record of event locations on the court, an idea that would be hard to create with a solely menu driven interface.<br>
<br>
This idea of a court location quickly gave way to realization that a basketball event could get fairly complex and deep for a menu system (i.e. a certain player shoots, shoots from behind the 3 point line, gets fouled by another player, and makes the shot). This realization lead to the idea of our system automating as many aspects of the event as possible to make the level of user input as small as possible. To do this we wanted our system to be context aware of our user input. For example, when a user selected a shot from behind the 3 point line the system would automatically make it a 3 point event.<br>
<br>
<br>
From here our interaction design shifted to a way that we could incorporate the menu system along with a full court location selection tool that would provide the user with the affordance of selecting a court location with a single click and incorporating the type of shot into the selection. To do this we came up with the idea of when a user selected a location on the court, a bubble menu would appear around the location and prompt the user with a menu that he could then click to select from to define the end result of a shot (miss, made, fouled, etc.)<br>
<br>
At this point our group was originally considering implementing this on a traditional computer with a point and click interface since keyboard shortcuts for such a complex system would carry a steep learning curve, vocal input would be impractical due to the volume of a basketball arena, and other input mediums would be difficult to reproduce court side. Then the idea of a touch interface on a mobile platform occurred to us since the idea of a laptop or desktop court side seemed cumbersome. A touch interface on a mobile platform, such as an iPad, would also allow us to implement fast, natural interaction with the device.<br>
<br>
The idea of using a touch menu interface coupled with a system that would be aware of the context of the event took us in the direction of creating a "drag menu" for selection, that would dynamically create levels a menu based on the current options available to the context of the system. For example, all events revolve around players, so initially the menu would only consist of a menu of players. When a user selects a player then a menu would "spawn" to the right of it where the next level of options relevant to that player would appear (i.e. pass, shot, etc.) The user could then drag their finger from the player to the desired action. This would then either "spawn" another menu or create the event depending on if more information was required (such as, in the event of a steal, the player that stole the ball). To incorporate the ideas of court location into this system, if the shot event was selected then the court map would spawn, allowing the user to select the event location and result with the previously describe bubble menu.<br>
<br>
We chose this interaction system as our final design since the "drag/swipe" touch menu selection system provides a low target selection time according to Fitts law, also the flowing motion of a left to right finger drag produces the metaphor of tracing a line with your finger and lends itself to muscle memory which would allow the user to increasingly record the game fast as he/she became used to it.<br>
<br>
Additionally we decided to implement a "swipe" deletion interface for the recent event list, allowing users to utilize the affordance of scratching something out to delete it. This follows our general interaction style of a fluid touch interface with dynamic menu generation.<br>
<br>
<br>
<br>
<h2>Client Interaction Interview </h2>

Before coming up with the prototype, we worked with our client on interaction design. Because he does<br>
not have any prior knowledge of HCI or software engineering, we used the slides provided to us in<br>
lecture to help explain the concept. After going over the basics of interaction design, we discussed<br>
interaction styles. Out of the three styles, we agreed that the primary interface was gong to be<br>
based on direct manipulation. Menus and forms are also going to be used, but they will be applied to<br>
less common tasks. We quickly ruled out a command line interface because it does not make sense to<br>
use in this software. Our client was interested in the direct manipulation tree diagram that we came<br>
up with during our activity and information design so we decided to implement the interface for the<br>
prototype.<br>
<br>
We also discussed our choice of hardware with our client. He agreed that the best choice to implement<br>
our prototype on is some sort of touch device. Fortunately, there are two members on our team with<br>
multi-touch tablets. Tablets are an ideal choice because they are portable and can rest comfortably<br>
on one's lap. Also, they are not too expensive and are easy to program.<br>
<br>
After discussing these fundamentals of interaction design, we decided the best choice for the<br>
prototype was an app on the iPad 2. We decided to omit certain features that do not pertain with the<br>
overall use of the interface. Certain setup menus were ignored because they do not interfere with<br>
the central task: recording the events of a basketball game. With these ideas in mind, we set out<br>
to implement a functional prototype.<br>
<br>
<br /><br />

<a href='http://code.google.com/p/cs-3724-group1/wiki/Phase3HomePage'>Back to Phase 3 Home</a>