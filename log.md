# 100 Days Of Code - Log

### Day 1: January 6, Friday

[//]: # (This is also a comment.)

**Today's Progress**: Joined codingame to try and get better at solving difficult puzzle type problems and improve algorithm aproach to different situations , took out a relatively difficult challenge https://www.codingame.com/training/medium/there-is-no-spoon-episode-1  , took me 4hours , learned 2D arrays .

**Thoughts:** Struggled with multi-dimensional arrays implementing to the specific challenge at hand but eventually got there :)

**Link to work:** [There is no spoon](https://www.codingame.com/training/medium/there-is-no-spoon-episode-1)


### Day 2: January 7th, Saturday 

**Today's Progress**: Done the Ceaser cipher FCC challenge, made a [pen](http://codepen.io/skhamoud/full/ZLGwbe) out of it.

**Thoughts** : One of'em days, I just couldn't find my head, Challenge took ALOT of time :( . Trying to implement functional programming concepts everywhere might be the reason.

**Link(s) to work**
[codepen](http://codepen.io/skhamoud/full/ZLGwbe)


### Day 3: January 8th, Sunday

**Today's Progress**: Couple FCC algorithm challenges, started going through exercism.io for algorithms training and joined a team making an app.

**Thoughts:**  started picking up React (again) and webpack :) , you can get very distracted , didn't remember it's a sunday .

**Link to work:** [FCC- record collection](https://www.freecodecamp.com/challenges/record-collection)


### Day 4: January 22rd

**Today's Progress**: Did 2 fcc challenges & completed the search by city feature in my weather app.

**Thoughts**  totally screwd up the 100 days of code challenge, it's day 4 ? but I skipped 10 days , was actually coding and learning React full time but never really got something to show for it and just forgot somedays but anyway will get back to counting now.

**Link(s) to work**
[FreeCodeCamp](https://www.freecodecamp.com/challenges/wherefore-art-thou#?solution=%2F*jshint%20esversion%3A6%20*%2F%0Afunction%20whatIsInAName(collection%2C%20source)%20%7B%0A%20%20var%20sourceProps%20%3D%20Object.keys(source)%3B%0A%20%20%2F%2F%20function%20checks%20if%20object%20has%20this%20prop%20and%20value%0A%20%20function%20hasPropsAndVals(obj)%20%7B%0A%20%20%20%20let%20_hasProps%20%3D%20true%3B%0A%20%20%20%20sourceProps.map(prop%20%3D%3E%20%7B%0A%20%20%20%20%20%20if(!obj.hasOwnProperty(prop)%20%7C%7C%20obj%5Bprop%5D!%3D%3Dsource%5Bprop%5D)%20%7B%0A%20%20%20%20%20%20%20%20_hasProps%20%3D%20false%3B%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%7D)%3B%0A%20%20%20%20return%20_hasProps%3B%0A%20%20%7D%0A%20%20var%20arr%20%3D%20collection.filter(hasPropsAndVals)%3B%0A%20%20return%20arr%3B%0A%7D)


### Day 5: January 26th

**Today's Progress**: Did 2 fcc challenges & worked on weather app.

**Thoughts**  picked up some react concepts and learned about firebase and it's basics

**Link(s) to work**
[FreeCodeCamp](https://www.freecodecamp.com/challenges/pig-latin#?solution=function%20isVowel(letter)%7B%0A%20%20%20%20var%20vowels%20%3D%20%5B%22a%22%2C%22e%22%2C%22i%22%2C%22o%22%2C%22u%22%2C%22y%22%5D%3B%0A%20%20%20%20var%20_isVowel%20%3D%20false%3B%0A%20%20%20%20for(let%20i%3D0%3Bi%3Cvowels.length%3B%20i%2B%2B)%20%7B%0A%20%20%20%20%20%20if(letter%3D%3D%3Dvowels%5Bi%5D)%7B%0A%20%20%20%20%20%20%20%20_isVowel%3Dtrue%3B%0A%20%20%20%20%20%20%20%20break%3B%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%7D%0A%20%20%20%20return%20_isVowel%3B%0A%7D%0Afunction%20translatePigLatin(str)%20%7B%0A%20%20var%20result%20%3D%20str%3B%0A%20%20if%20(isVowel(str.charAt(0)))%20result%2B%3D%22way%22%3B%0A%20%20else%7B%0A%20%20%20%20var%20firstVowelIndex%20%3D%20str.split(%22%22).findIndex(function%20getFirstVowel(letter)%7B%0A%20%20%20%20%20%20return%20isVowel(letter)%3B%0A%20%20%20%20%7D)%3B%0A%20%20%20%20var%20lastPart%20%3D%20%20str.substr(firstVowelIndex)%3B%0A%20%20%20%20var%20consCluster%20%3D%20%5B...str%5D.splice(0%2CfirstVowelIndex).join(%27%27)%3B%0A%20%20%20%20result%20%3D%20lastPart%2BconsCluster%2B%22ay%22%3B%0A%20%20%7D%0A%20%20%20return%20result%3B%0A%7D%0A%2F%2FTODO%3A%20refractor%20with%20Regex%0AtranslatePigLatin(%22consonant%22)%3B%0A)


### Day 6: January 28th

**Today's Progress**: Did some of the learnyounode assignments while playing with node from Nodeschool. 

**Thoughts:**  started picking up some node and backend also firebase seems awesome and very helpful  .

**Link to work:** None really :(


### Day 7: January 30th

**Today's Progress**: worked on local weather app, started styling . 

**Thoughts:**  problems with create-react-app implementing sass into project , but ejected CRA to be able to use sass  .

**Link to work:** [codepen](http://codepen.io/skhamoud/full/pRayBm/)


### Day 8: February 1st

**Today's Progress**: progress on local weather app, more styling . 

**Thoughts:**  I code a lot more than an hour often but just keep getting distracted with stuff and docs and vids etc..., I also just miss days on the log although I did the challenge but can't remember what I did when I try to update the log.

**Link to work:** [codepen](http://codepen.io/skhamoud/full/pRayBm/)


### Day 9: February 5th

**Today's Progress**: got on page with IdeaZone project , went through code base , started working on (adding examples, and tutorials features) features. 

**Thoughts:**  Like what the team did with the app, Firebase still new to me, so a bit confusing.
 I like evans style of code. will pull request soon. 
 though I'll be offline for 2 weeks, I'll try and do as much as possible in side project automarket without the distractions of emails, notifications etc...  :-)

**Link to work:** [ideazone](https://github.com/skhamoud/IdeaZone)
