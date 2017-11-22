<h1>Arduino Puzzle Box</h1>

<h3>PUZZLE BOX: INTRODUCTION</h3>
The Puzzle Box is a mid-term challenge to assess two criteria: (1) how much of Arduino and physical computing have students learned; (2) willingness to step beyond comfort zones and test learnings by building a puzzle box with familiar and unfamiliar components, the latter requiring self-initiative and exploration. I was quite excited, if also apprehensive, about this assignment, but I felt the result had a distinctive and somewhat whimsical quality that invited conversations and further questions from all who saw it. I ended up building a force-driven puzzle box with LEDs, Piezo speaker, accelerometer, sound sensor, servo motors, two Arduino boards, laser-cut box with polarisation properties, and an overarching theme from Star Wars.

The following entry documents this week’s topics and processes. The accompanying blog entries detail my thoughts, insights, analysis, and code blocks + recommendations (where feasible) on the week’s topic(s). References and bibliographies for all sourced and cited content has been provided at the end of this page. Note: The references made to Star Wars themes and related items have been used here strictly for educational and personal project purposes only, and are not intended for commercial or official use of any kind whatsoever. Nothing in this project is endorsed or sponsored by the Star Wars brand.

<h3>PUZZLE BOX: ESSENCE</h3>
The essence of this puzzle box is to tilt the box along different axes and listen to each tone that plays. For those who are familiar with Star Wars, the clue easily suffices. The addition of the laser-cut Darth Vader head in the front of the box is probably a dead giveaway. For people with hearing disabilities, I also integrated a lighting system to indicate the combination. When the tones are played in the correct order, and all three LEDs light up, the box opens. However, to counter this easiness for those without impairment, I used a particular colour of acrylic for my box. Orange has a polarising effect on blue LEDs, the last one required to open the box. Therefore while the box is transparent, there is no way to tell whether the blue LED is on or off just by looking at it, since the orange acrylic cuts out the blue emission. This makes it more of a challenge to open the box. The result is a puzzle box that uses the force of light, the force of sound, the force of planetary spin, and “the Force” or instinct to open.

<h3>PUZZLE BOX: INSPIRATION</h3>
Having covered LEDs, buttons, and speakers quite extensively in the first few weeks, I decided to create a theme for my project along forces and energy. Essentially the LEDs are light energy, and speakers are sound energy. This gave me an idea for using “the Force” to open the box. From the various components I considered and experimented with, the accelerometer held most utility, which gave rise to the thinking: how cool would it be to use the Earth’s spin to open a puzzle box? Plus the idea of tying in the project with a favourite show was appealing enough to title the project, ‘Use the M•A’. In this instance the M•A serves as both the qualification of this masters as well as the elements of Newton’s famous equation: Force (F) = Mass (M) x Acceleration (A). Combining an accelerometer with Star Wars made perfect sense. However, I also wanted to create a box that would serve a purpose beyond just opening and closing, which I figured would get stale quite quickly, no matter how appealing the initial process of opening the box might be.