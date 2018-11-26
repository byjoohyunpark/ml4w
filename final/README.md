# Unknown Forest (Alpha version of Thesis)
An immersive sound environment of virtual forest trained and created with ML-generated sounds.


## Inspiration 
* [tensorflow-wavenet 500 msec 88K train steps speaker p280](https://soundcloud.com/user-731806733/tensorflow-wavenet-500-msec-88k-train-steps)
* [Wavenet examples](https://deepmind.com/blog/wavenet-generative-model-raw-audio/)
* [Mazurka (After Chopin) by David Cope (1994?)](https://soundcloud.com/machinelearningmusic/mazurka-after-chopin-by-david-cope?fbclid=IwAR0dQc2bq28wYbV2GjkcXpLHdqLRO4O7CgxwbcrP3G3O6O4oU1AAHx4vI20)


## Idea
Using audio generation technique, make new format of sounds based on sound of forest on Earth. 
```Sounds of real forest -> sounds of virtual forest ```
Create web environment to deliver these sounds in visual(?) or immersive context. 


## Tech Stack
* Magenta (NSynth)
* Wavenet
* Web VR


## Question
* Collecting and organizing training dataset. -> The most critical part. 
``` 
size of whole dataset
size of each data
elegant way to evenly reflect different sounds
``` 
* How to catch the cracking noise of output?
* How to deal with expensive training process.
* Would the output acceptable or listenable?
* Overfitting problem.
* Training steps?
