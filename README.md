![EcoEarth](https://i.imgur.com/mZUFdKB.jpg)

<h1>Game Design Documentation</h1>
<h6>Version 2.0
</br>Produced by: Rebecca Nash
</br>29-10-17</h5>

</br></br>

<h1>Contents</h1>
<ol>
  <li><a href="#history">Design History</a></li>
  <li><a href="#overview">Game Overview</a></li>
  <li><a href="#story">Story</a></li>
  <li><a href="#mechanics">Core Game Mechanics</a></li>
  <li><a href="#flowchart">Interface Flowchart</a></li>
  <li><a href="#elements">In-Game Elements</a></li>
  <li><a href="#characters">Characters</a></li>
  <li><a href="#gametext">In-Game Text</a></li>
  <li><a href="#assets">Required Assets</a></li>
</ol>
<br />

</br></br>

</br>
<div><div id="history">
<h1>Design History</h1>
<br />

25-10-17
Initial design document created.

29-10-17
Amendments to storyboard layout and in-game flowchart.

</br>
<div><div id="overview">
<h1>Game Overview</h1>
<br />
  
# I. Introduction

In this 2D web application game, the players will walk through the greenhouse gas footprint chain for four products; mobile phones, beef, leaving electronic devices on standby and plastic bottles. Along the chain journey players will take ownership of releasing the gases into the atmosphere, and as a result will see and hear about the effect on the four related habitats; the arctic tundra, rainforest, ocean and British countryside. A habitat animal narrator will guide players through the journey providing educational facts for enhanced learning. Players will have the opportunity to participate in mini games during the chain journey to select the animals who reside in the habitats they’re learning about, and to provide a pledge on how they promise to try and help.

# II. Objective of the Game

The objective of the game is for each player to learn about, and take ownership of, the greenhouse gas footprint chain for each of the four products, as well as providing a pledge of what they’ll do to reduce greenhouse gas emissions.

# III. Genre

Interactive, educational puzzle game.

# VI. Features

<li>2D game</li>
<li>Team play</li>
<li>Visual feedback</li>
<li>Educational</li>
<li>Interactive</li>
<li>Real-time in-game updates</li></br>

# V. Platform

This game will be a web-based application, designed for use with on an Apple iPad using iOS 10.3.3. 

# VI. Intended Audience

The intended audience of this game is for casual or non-gamers of both genders from the age of 11 to 16, however the primary age range is 11 to 12 years old. 

# VII. Language

The game will only be in English.

# VIII. Sound Consideration

The game play experience is not dependant on sound and as such the game does not require speakers of any kind.
  
<br />
<div><div id="story">
<h1>Story</h1>
<br />

# I. Outline

Production and disposal of mobile phones, beef, leaving electronic devices on standby and plastic bottles are having a detrimental impact on four habitats around the world. An understanding of this process, and a pledge to help, is absolutely vital to the future of these habitats and the animals that live there.

# II. Story Synopsis

The story relates the greenhouse gas footprint chain of production to disposal of four products to four habitats from around the world. At each stage of the chain, players are presented with a fact and relevant image, and the responsibility to release the emitted gases into the atmosphere. Upon release, the habitat view becomes darker and bleaker as the on-screen greenhouse gas meter rises. An animal narrator for each habitat describes the impact the gases are having on the habitat and once the chain journey is completed, they return to ask for help saving their home giving the players the option to provide select a predefined pledge to help, or not. Players who pledge will witness the on-screen pledge meter rising, which will impact their overall score at the end of the game.

# III. Cut Scene Screens

# Splash Screen
![Splash](https://i.imgur.com/dOuCeWs.png)</br>
Loading screen.

# Rotate Window
![Rotate](https://i.imgur.com/4yR89Ck.png)</br>
Window that will display if/when iPad is put into a portrait position.

# Login Window
![Login](https://i.imgur.com/Uw8FClA.png)</br>
Players are requested to create and input a team name. A team name accommodates any number of players to one iPad.

# World View
![World](https://i.imgur.com/htk2lof.png)</br>
The chosen team name, score, a pledge meter and a greenhouse gas meter display on screen. All four habitats are unlocked and ready for selection by touch.

# Chain View Introduction
![Intro](https://i.imgur.com/23sMj5x.png)</br>
Players are provided with an introductory text for each habitat to provide an understanding of how the habitat links to its product.

# Chain View Incomplete
![Incomplete](https://i.imgur.com/vzAWR2K.png)</br>
Each habitat opens with an incomplete, unexplored chain. Players are directed on where to click by the visual aid of an unlocked padlock display. 

# Chain Fact
![Fact](https://i.imgur.com/SOoogGl.jpg)</br>
Each chain element displays a pop-up with each chain stage, a representative image and a slider for players to ‘release the gases’ into the atmosphere. Where applicable, animal narrators return to provide facts.

# Chain Game
![Game](https://i.imgur.com/7KZXUPj.jpg)</br>
Players are requested to select three animals who live in their playing habitat from a pack of nine animals. Four games are presented to players throughout each of the four chains.

# Chain View in Progress
![InProgress](https://i.imgur.com/29VCbLP.jpg)</br>
The greenhouse gas meter rises, and the habitat view becomes darker and darker as each chain journey progresses. Animal narrators return to provide updates on the effects the greenhouse gases are having on the habitat

# Chain View Complete
![Complete](https://i.imgur.com/5eRldvr.jpg)</br>
The view of a completed chain.

# Question Window
![Question](https://i.imgur.com/95SvHjZ.png)</br>
After each chain is completed, players are required to answer four questions based on their learning of the chain journey that they have just completed.

# Help Window
![Help](https://i.imgur.com/UHyLM0V.png)</br>
Habitat animal narrators return to ask players to help save their home, presented with a real-life image of the destruction caused.

# Pledge Window
![Pledge](https://i.imgur.com/3g0ePyD.png)</br>
Players are asked to select one pledge out of three displayed that they promise to try and commit to in order to help save the habitat.

# Thank You Window
![ThankYou](https://i.imgur.com/Ckt7XyF.png)</br>
Players are presented with their chosen pledge and thanked for their input.

# World View Complete
![WorldComplete](https://i.imgur.com/zDdzI1P.png)</br>
All habitats completed and locked. Display showing game with only 3 out of 4 habitat pledges inputted.

# Game End Window
![End](https://i.imgur.com/tHFxPiy.png)</br>
Players are thanked for playing and requested to return the iPads to their group leader.

<br />
<div><div id="mechanics">
<h1>Core Game Mechanics</h1>
<br />
  
# I. Camera

The camera will be stationary, with a top-down view of the world map or a zoom of each habitat during all scenes.

# II. Team Play

This game will be played in teams. 

# III. General Movement

Players will be required to tap and slide during game play. 

Tap: Required for habitat selection within the World View, to answer questions, participate in game play and select each stage of the chains on each habitat window.

Slide: Required to ‘release the gases’ into the atmosphere within the habitat chain facts.

# VI. Initial Set Up

The web app opens with a request for the team to create a team name and select an animal character of their choice. A ‘start’ button will move them into the World View, where the world is displayed with four unlocked habitats to select.

# VII. Points

All teams will begin with 10,000 points, the maximum points. Each team must answer questions correctly to maintain their score, as each incorrect answer will reduce the score by 500 points. 

<br />
<div><div id="flowchart">
<h1>Interface Flowchart</h1>
<br />

![EcoEarthFlowchart](https://i.imgur.com/xgSWj36.png)

<br />
<div><div id="elements">
<h1>In Game Elements</h1>
<br />
  
# I. Colour Pallet

![EcoEarthColourPallet](https://i.imgur.com/0pei6Yh.jpg)

# II. Fonts

In-game font: Lucida Grande, Regular, Strong

Logo font: Phosphate

In-game narrator text font size: 24pt

In-game chain facts text font size: 36pt

In-game HUD header font size: 60pt

<br />
<div><div id="characters">
<h1>Characters</h1>
<br />

# Habitat: British Countryside</br>
Name: Olivia</br>
Animal: Tawny Owl</br>
![TawnyOwl](https://i.imgur.com/ER5oRr8.png)</br>

# Habitat: Arctic Tundra</br>
Name: Malcolm</br>
Animal: Moose</br>
![Moose](https://i.imgur.com/hy7m5N8.png)</br>

# Habitat: Rainforest</br>
Name: Susan</br>
Animal: Emerald Tree Boa</br>
![EmeraldBoa](https://i.imgur.com/97bPamz.png)</br>

# Habitat: Ocean</br>
Name: Rocky</br>
Animal: Rock Hopper Penguin</br>
![RockHopper](https://i.imgur.com/iIaSp5T.png)</br>

</br>
<div><div id="gametext">
<h1>In-Game Text</h1>
<br />

The game text doc can be downloaded from [here.](https://github.com/RebootGames/ZSL-Eco-Earth/blob/master/Eco%20Earth%20Game%20Text.docx)

# Login Window
_“Please enter your team name”_<br>
_Start [BUTTON]_

# World View
_“Welcome to Eco Earth! You’ll learn about the greenhouse gases that are emitted from production to disposal of four products; mobile phones, plastic bottles, leaving electronic devices on standby and beef, and how each of these impact the habitats you’re exploring during your time at the zoo today._

_At the end of each chain you’ll be asked a series of questions on what you’ve learnt. Your score will decrease for every incorrect answer, so do your best to come out on top and keep your score as close to 10,000 points as possible! Good luck!_

_When you’re ready, click into your starting habitat and work your way through the chain. Look out for the bonus animal game rounds, too!”_

# Habitat Introductory Text
_“Welcome to the Arctic Tundra! The Arctic is mined for natural gas. One of the uses for this natural gas is to generate electricity, which is wasted if electronics are left on standby.  The Arctic is estimated to hold the world's largest remaining untapped gas reserves. Click on the unlocked padlock to start your journey, and learn about the greenhouse gas footprint of leaving electronic devices on standby. Don’t forget to explore the table, too!”_

_“Welcome to the Rainforest! The rainforest is mined for the raw materials that make mobile phones. This involves the cutting down of trees to build the mines and to improve road networks. This destroys habitats. On top of this, when trees are cut down, the carbon they store is released into the atmosphere. Click on the unlocked padlock to start your journey, and learn about the greenhouse gas footprint of mobile phones. Don’t forget to explore the table, too!”_

_“Welcome to the British Countryside! 2.1 million cattle are used for beef production annually in the UK. In 2015, overall UK agriculture released an estimate of 49.1 million tonnes of greenhouse gas into the atmosphere. Click on the unlocked padlock to start your journey, and learn about the greenhouse gas footprint of beef. Don’t forget to explore the table, too!”_

_“Welcome to the Ocean! Oil is mined from the ocean floor. One of the uses for this oil is the production of plastic bottles. London alone drinks 2 million plastic bottles of water daily (and that’s just water!) Click on the unlocked padlock to start your journey, and learn about the greenhouse gas footprint of plastic bottles. Don’t forget to explore the table, too!”_

# Habitat Text

[If a locked padlock is clicked: Narrator text]<br>
_“Uh oh, looks like that window is locked. Click on the window with the open padlock.”_

# Countryside Chain (and facts where applicable)
1. Carbon is released as trees and plants are cut down to make space for cows and to grow their feed<br>
2. Carbon is released from pesticides that are put on cow feed to stop them being damaged by pests
    * FACT: Carbon is also released when electricity is generated to produce pesticides
3. Carbon and nitrous oxide are released from fertilisers that are used to help cow feed grow
    * FACT: Nitrous oxide is 300 times more harmful to the environment than carbon
4. Carbon is released when electricity pumps water from underground rivers, reservoirs, streams and canals to provide water for the cows to drink and to grow their feed in the fields
5. Carbon is released when farm vehicles and machinery are used on the farm and fields
6. Methane is released when grazing cows pass wind
    * FACT: Methane is 23 times more harmful to the environment than carbon
7. Carbon is released when animals are transported to the slaughter house
8. Carbon is released as electricity powers fridges, lights, computers, water and many more resources in the slaughter house
9. Carbon is released from the production of the materials used to package the beef
10. Carbon is released when beef is transported to the shops and restaurants it is sold in
    * FACT: Sometimes beef is flown over to the UK from a different country
11. Carbon is released as electricity powers fridges, lights, computers, heating, water and many more resources in the shops and restaurants
12. Carbon is released as customers travel to the shops and restaurants
13. Methane is released as beef and packaging decomposes in landfill

# Ocean Chain (and facts where applicable)
1. Carbon is released as drilling rigs are constructed, installed and run
2. Carbon is released as oil is transported via pipes/ships to treatment plants
3. Carbon is released as electricity is required to clean the oil
4. Carbon is released as oil is transported via pipes/ships/rail/tankers to manufacturers
5. Carbon is released when electricity is generated to form the oil into plastic bottles and lids
6. Carbon is released as empty bottles are transported to a bottling plant
7. Carbon is released when machinery fills bottles with drink
8. Carbon is released when bottles are packaged
9. Carbon is released as plastic bottles are transported to shops and restaurants
10. Carbon is released as electricity powers fridges, lights, computers, heating, water and many more resources in the shops and restaurants
11. Carbon is released as customers travel to the shops and restaurants
12. Methane is released as plastic bottle decomposes in landfill
    * FACT: Methane is 23 times more harmful to the environment than carbon

# Arctic Tundra Chain (and facts where applicable)
1. Carbon is released when natural gas drilling rigs are constructed, installed and run
2. Carbon is released as natural gas is transported via pipes/ships/tankers to treatment plants
3. Carbon is released as electricity is required to clean and dry the natural gas
4. Carbon is released when natural gas is odorised so people can smell it and be alerted to a gas leak
5. Carbon is released as natural gas is transported via pipes/ships/tankers to power stations in the UK
    * FACT: In the UK natural gas has almost run out, so it is imported from further away
6. Carbon is released when natural gas is burned in power stations to drive turbines, which then produces electricity
7. Carbon is released as electricity is needed for pylons/power lines to carry electricity
    * FACT: 10% of electricity wasted along metal pylons
8. 15kg of carbon wasted per year by leaving TVs on standby
    * FACT: 9-16% of the electricity consumed in homes is used to power devices left on standby

# Rainforest Chain (and facts where applicable)
1.	Carbon is released as oil drilling rigs and mines are constructed, installed and run to extract raw materials which mostly come from rainforests
    * FACT: Mining takes place in, and destroys rainforests
2.	Carbon is released as raw materials are transported to factories in China, Taiwan, Japan or Korea
3.	Carbon is released when electricity is generated to construct raw materials into usable phone parts
4.	Carbon is released when mobile phones are packaged
5.	Carbon is released as constructed mobile phones are transported to the phone shop
6.	Carbon is released as electricity powers lights, computers, heating, water and many more resources in the phone shop
7.	Carbon is released as customers travel to the phone shop
8.	Carbon is released when electricity is used every time the phone is charged
9.	Carbon is released as raw materials continue to be drilled/mined if phone is not recycled
    * FACT: 80% of the carbon footprint of a phone happened before it’s turned on for the first time

# Risks – Narrator Speech
Displayed throughout chain completion.

Countryside<br>
_"It's raining so much!"<br>
"Our summers are getting far too hot; lots of people are getting sick."<br>
"Sea levels have risen; our coasts are flooding! If this carries on, sea levels could rise by up to 1.9m.”<br>
“Sea levels rising by 1m would see most of Bangladesh, Vietnam, Norway and the Maldives underwater!”_

Ocean<br>
_"All my friends are leaving for cooler waters, even the fish are leaving, what will I eat?"<br>
“All the coral is losing its pretty colours. It’s stressed and is more susceptible for disease and death.”<br>
“The water is too acidic because of a chemical reaction from absorbing too much carbon.”<br>
“The crabs, clams and mussels struggling to produce and maintain their shells in these waters.”_

Arctic Tundra<br>
_“Permafrost is a frozen layer of soil. It's melting and all the drinking water is soaking into the soil."<br>
"The ice is melting away. At this rate the Arctic could be ice-free by 2030, or earlier”_

Rainforest<br>
_“It’s really hot here, I need to find some shade to cool down.”<br>
“I haven’t seen any rain here in days.”<br>
“Oh no, the trees are catching fire releasing more carbon into the atmosphere!”_

# Habitat Questions and Answers (shown after each chain is completed)

Countryside
1.	What gases are released from using fertilisers?
    <br>a.	CORRECT: Carbon and nitrous oxide
    <br>b.	Carbon, nitrous oxide and methane
2.	Which of the below are examples of where water is pumped from to provide water for the cows and their growing feed?
    <br>a.	CORRECT: Underground rivers, reservoirs, streams and canals
    <br>b.	Sinks, baths and lakes
3.	What gas is released when grazing cows pass wind?
    <br>a.	CORRECT: Methane
    <br>b.	Carbon
4.	What is needed to power the fridges, lights and computers inside the slaughter house?
    <br>a.	CORRECT: Electricity
    <br>b.	Carbon

Ocean
1.	Name two modes of transport to get oil to the treatment plants from the oil rigs?
    <br>a.	CORRECT: Pipes and ships
    <br>b.	Aeroplanes and cars
2.	Where do the empty bottles get transported to?
    <br>a.	CORRECT: A bottling plant
    <br>b.	Shops and restaurants
3.	What gas is released when machinery fills each bottle with drink?
    <br>a.	CORRECT: Carbon
    <br>b.	Nitrous oxide
4.	What gas is released when plastic bottles decompose in landfills?
    <br>a.	CORRECT: Methane
    <br>b.	Carbon

Arctic Tundra
1.	What's the missing word? "Carbon is released as _____ is required to clean and dry the natural gas"
    <br>a.	CORRECT: Electricity
    <br>b.	Carbon
2.	Why does natural gas need to be odorised?
    <br>a.	CORRECT: In case of a gas leak, people need to be able to smell it
    <br>b.	Less carbon is released if the gas smells
3.	Where does the natural gas get transported to?
    <br>a.	CORRECT: Power stations
    <br>b.	Schools and colleges
4.	How much carbon is wasted per year by leaving TVs on standby?
    <br>a.	CORRECT: 15kg
    <br>b.	2kg

Rainforest
1.	Where do most of the raw materials to build mobile phones come from?
    <br>a.	CORRECT: Rainforests
    <br>b.	Oceans
2.	Where are mobile phone raw materials transported to?
    <br>a.	CORRECT: China, Taiwan, Japan or Korea
    <br>b.	USA and the UK
3.	What's the missing word? " ___ is released as constructed mobile phones are transported to the phone shop"
    <br>a.	CORRECT: Carbon
    <br>b.	Electricity
4.	True or false. Carbon is released every time a mobile phone is charged.
    <br>a.	CORRECT: True
    <br>b.	False

# Help Window
_“All these greenhouse gases are destroying the [INSERT HABITAT NAME]. Can you help save my home?”_<br>

_“Can you help?”_<br>
_“Yes” / “No”_

# Pledge Windows
_“Choose your pledge"_<br>
_Select one of the pledges below that you will promise to try and do to help save the [INSERT HABITAT NAME].”_

# Pledges by habitat

Countryside
1.	I will try to skip eating beef (and better yet, meat!) for one day a week (you could follow @meatfreemonday)
2.	If I have access to a special food waste bin, I will throw beef (and any other food waste) in it
3.	When ordering food, I will pick an alternative meat (or better yet, a vegetarian option) instead of beef 

Ocean
1.	I will use a reusable bottle instead of buying single use plastic bottles
2.	I will recycle any plastic bottles I use
3.	If I want water when eating out, I will ask for tap water instead of getting it in a plastic bottle

Arctic Tundra
1.	I will switch electronics off of standby when I am not using them
2.	I will switch light switches off when I am not using them 
3.	I will unplug my mobile phone charger from the wall

Rainforest
1.	I will reconsider upgrading my phone every year/two years if it still works okay
2.	I will take care of my phone to make it last as long as possible
3.	I will recycle my phone instead of throwing it in landfill

# Thank You Window
_“Your chosen pledge”_ <br>
[DISPLAY CHOSEN PLEDGE]<br>
_“Thank you!”_

# Game End Window
_“Thank you for playing Eco Earth! We hope you’ve enjoyed learning about the greenhouse gas footprint, and more about how you can help save our planet._<br><br>

_Please return the iPad to your group leader.”_

</br>
<div><div id="assets">
<h1>Required Assets</h1>
<br />
  
Please download the required assets doc from [here.](https://github.com/RebootGames/ZSL-Eco-Earth/blob/master/Eco%20Earth%20Assets.docx)

