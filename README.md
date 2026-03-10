# Experiment2

Aim
A shape shows up the moment someone opens the app. Right after, lines join circles fast - no waiting at all. Once it starts, tapping once adds another form onto the screen. During use, hues change just a little whenever fingers move. Over minutes, designs spread slowly across the whole area. Just before shutting down, bits pile up in lopsided groups. As you work, strokes follow every tap without delay.

To understand how to create a custom View class in Android.
Start by learning how to sketch forms with Canvas and Paint together. You’ll dive into techniques that make graphics show up via programming. Layout gets managed here, while there color and outline take shape elsewhere. With time, handling what you see becomes more natural. Step after step, it clicks - how pictures come together one tiny dot at a time.

A single straight form often leads things off. After it, step-by-step, four corners build a box shape. Next arrives something curved, perfectly even with no points. Instead of stopping there, a longer rounded version leans outward gently. Finally, characters appear - built out of fine specks lined into words.

Behind every visual on screen lies the work of onDraw(). Step by step, it builds images each time it runs. Needed updates cause automatic activation - no delays wait around. Pixel by pixel, its inner actions decide exactly what appears. Something happens behind the scenes each time a picture shows up automatically. This hidden system handles every change you see on screen.

Begin with color tweaks using the Paint tool before shifting to design details. After that, handle line width just like the earlier steps. Every control fits within this single feature. Change numbers gradually instead of jumping. See how things transform right in front of you. Move through every choice at a calm pace. Start by spotting tiny changes that show clear results. Move ahead slowly, fixing one piece at a time till the look fits.
Starting over, hooking up a custom view to MainActivity shifts perspective. Inside the app’s display, that piece now appears. Bypassing usual methods, connection happens by assigning a layout. When things start, correct setup matters most. It is when things connect that the screen lights up. If wires go wrong, the display stays blank.
Start by building basic UI parts through code rather than designing them in XML files.





Algorithm
After powering on the device, open Android Studio. Only when everything shows up clearly should you touch any part of the screen. The moment it’s ready, go directly to the workspace area. Starting up happens before anything else begins.
Open a new Android project first thing. Next up, go ahead with the blank activity choice instead. Once it loads, settle on the empty template so you start clean.
First up, enter a title for your work - try naming it TestLook - and once the system asks which programming tongue you want, go with Java.

Let Android Studio generate the default project structure.
Open the AndroidManifest.xml file right away. Within it, look for MainActivity set as the starting point. This one should carry the launchable tag. It needs to appear at launch without delay. Another activity must not run instead of this one.
A brand new Java class named MyClass takes shape by extending View. Built into its design is a mirror of the parent’s setup, yet shaped with individual traits. Through inheritance, actions flow naturally from one to the other. Clear in purpose, the title MyClass shows exactly what it is. A wider view brings more reach, skills flowing forward on their own. Inside this container, instructions wait, built into the structure. When called upon, they move without delay.

A new Paint begins within MyClass's constructor. Right there, it stands by - set up ahead of time for drawing shapes down the line. Initialization handles everything one time only. When marks need making, they depend on this pre-built tool. How each line looks ties back to its setup.

Start at the end - drawing takes place within onDraw(Canvas canvas). Rewrite that method if you want a different outcome. Once inside, the canvas gives access to its tools. What appears on screen shifts with every instruction changed right here.
A lone mark forms the moment canvas.drawLine() activates. Point meets point, linked only by what this tool provides. Right there on the surface, drawing takes place - no detours, just direct output. Once executed, a line becomes visible, nothing held back. Each shift across positions gets painted simply by invoking it.

Pick a color first - adjust its appearance using Paint settings before laying down the line. What you see changes once those tweaks happen ahead of drawing.

A lone rectangular figure shows up after using canvas.drawRect(). The moment it runs, edges form right where pixels live. Its location and dimensions depend entirely on what numbers go in. Corners land exactly at those specified points.
A dot appears every time canvas.drawCircle() runs. Position changes happen when number inputs shift. Movement flows just by adjusting those figures. Each spot gets unique placement through altered coordinates. Sliding numbers pushes circles elsewhere on display. New locations form as values drift across range. Watch where they land after tweaking X and Y. Every run places a mark at fresh location. Shifting digits steers them to different zones. Exact spots depend on updated numerical entries.
A shape begins to show once canvas.drawOval() is called. As the program moves forward, an elliptical figure fills into view. Through this function, the screen captures a smooth curve. Appearance of the form relies entirely on that execution. Paint shows up when it runs. This piece takes care of how things look.
Show "Graphic Primitives" on display when canvas.drawText() runs.
Open MainActivity.java.
A fresh MyClass object takes shape inside the onCreate() method. Creation happens right there when the function runs. That is where the instance first appears. It shows up each time without delay. The moment arrives, the class comes alive.
Show the custom view on screen by calling setContentView(view).

Before putting the pieces together, save each document. Files need securing first, that way everything stays ready when it's time to build.

Open the app through an actual phone or by running an Android simulator instead.
A shape appears here, then a word there across the display. Sometimes letters follow circles, sometimes squares come before numbers. Each time, something new shows up without warning. Screen changes keep happening, one after another. What was visible earlier shifts into something else entirely.

See if the program runs without hiccups. When it boots up cleanly and shuts down right, you know it passed.