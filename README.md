# creative computing using game grid systems 

Being introduced to Arduino in class was quite confusing since I didn't really understand anything, @nosiuol and I managed to get TWO(!!!) LEDs to light up, but doing it on tinkerCAD was a pain. 

![Photo on 22-11-2021 at 16 47](https://user-images.githubusercontent.com/95000041/143487927-795fe451-d92a-494d-9a7b-1a8fa5a6f194.jpg)

![IMG_9075](https://user-images.githubusercontent.com/95000041/143488120-71d353b3-9032-41c4-bd09-70d1ab976b88.jpg)



I realised that the breadboard reminded me of a grid, which got me thinking about grid-based games. I think incorporating creative computing concepts into games would be an effective way of familiarising people without overloading them? It removes the novel and overwhelming aspect of it, while not discounting the actual technical aspect. 

Computing skills could be compared to using game mechanics, which people are able to acquire within the context of the game. We dont grow up knowing how to use the different runes in zelda, or different cheat codes on gta, its a skill you acquire by playing the game. I guess creative computing is kinda like that, the numbers just freak me out, which is why games might be a milder way to introduce people to it. 

The redstone crafting mechanics in minecraft reminded me of the arduino circuits we played around with, especially since minecraft uses a grid system too. The open world aspect of minecraft makes it a better option than platformer (but still tile-based) games like celeste and hollow knight. (while these are great games, there is less customisation and you have to follow a linear story-line, which is why the free roam aspect of minecraft makes it a better contender for "creative" computing) 

![arduino tinkercad](https://user-images.githubusercontent.com/95000041/143492339-8610c5c0-6db6-4d1f-aa63-588d4a040aed.png)


I tried experimenting on tinkerCAD and got an LED to light up! :] I didn't really know how to take it forward though, so i decided to recreate it on minecraft using their redstone circuit mechanics. It was alot easier using "materials" i was familiar with, while still trying to recreate the arduino circuits we learnt about in class. I feel like an instructional guide using minecraft terminology would be quite funny in helping someone learn about creative computing, kind of like side-quests in a game. 

First, i made the breadboard

<img width="1349" alt="breadboard mine" src="https://user-images.githubusercontent.com/95000041/143492534-28c0d19d-87a1-40a9-bb23-65b3e55d8907.png">

I made sure to kill any one who tried to obscure my vision

<img width="485" alt="murder!!" src="https://user-images.githubusercontent.com/95000041/143492671-bc9f3a39-b225-4d13-b748-60b12fbd9e7d.png">


I then made the arduino circuit

<img width="1171" alt="arduino mine" src="https://user-images.githubusercontent.com/95000041/143492576-0af51f06-8475-4033-9fb7-8684a664d265.png">

Redstone dust was used as the "wire" and Redstone Lamps were used as the "LEDs". Getting the LED to light up was a bit different since in minecraft redstone dust runs out of power every 15 blocks, which meant i had to incorporate a redstone repeater every 15 blocks to keep the signals at full strength. From my understanding, it acts similarly to the resistors on an arduino board. on the Arduino board there are different values for the resistors, on minecraft the redstone repeaters have 3 different values, which i feel is a good simplified way of presenting it. 

<img width="1340" alt="redstone wiiiire" src="https://user-images.githubusercontent.com/95000041/143493373-389f9225-c9d9-44c9-bccf-ae465057cc26.png">

I connected the 5v socket wire to the "+" on the breadboard. I connected another "wire" from the "GND" port on the Arduino to the "-" on the breadboard. That ensured that the energy was connected to the breadboard on which the LED would be placed. 

I then created an "LED" light using redstone lamps. On minecraft I really only needed to power the redstone lamps with some redstone, but I tried to stay true to the visuals of the circuit on tinkercad, which is why i replicated connecting the LED cathode and anode to a resistor and wire respectively.

<img width="1358" alt="redstone LED" src="https://user-images.githubusercontent.com/95000041/143494299-a41fb735-a83d-4a24-9c98-9ccc98cac18e.png">

This is what it ended up looking like, and this is what the circuit as a whole looked like, :^D

<img width="875" alt="Screenshot 2021-11-25 at 19 47 18" src="https://user-images.githubusercontent.com/95000041/143494366-bb43c5e5-a266-44a4-9f54-ee78cc688d45.png">

While the mechanics on minecraft were way more simplified, i feel like it did help me understand the tinkerCAD circuit better, since i understood the basics. So although it wasn't completely true to life, i feel that it is a fair enough introduction. I wonder what other minecraft mechanisms are representative of real life physical computing examples without us knowing. 

I'd be interested in seeing how CC can be introduced into games naturally, especially in less open-world games. I feel like it would be cool to see a version of animal crossing where it was less casual and more focused on the specifics of crafting, rather than it being a one-click and done thing. 

