hosted link of the project:  https://singhpratibha98.github.io/animations-repo/

![html-1](https://github.com/singhpratibha98/animations-repo/assets/129493126/1145e660-1b2a-464b-b4bd-be1509468801)
![css-1](https://github.com/singhpratibha98/animations-repo/assets/129493126/04d3631f-3341-415e-ae48-5224619f8a07)
![css-2](https://github.com/singhpratibha98/animations-repo/assets/129493126/a983f904-13a0-4ccd-a978-464869e8a293)
![UI](https://github.com/singhpratibha98/animations-repo/assets/129493126/56f9e7d0-2fe0-4577-a1ef-10d192bc8019)

Here i have made this animation project using html and css by applying animation lets have a look:
1) first we make the div class name as container in which we have 3 images of wrist watch .we attach the image using the img tag.
2) In css we first make the universal selector, and in body section we make display as flex, for making or images in center we use justify-content:center, align-itms:center,and our body color is black jo give background-color property as black.
3) then we move to container in which we give container to be in flex, and flex-direction as row bcz our images are arranges in row wise.
4) and for making gap between the images we give css as justify-content:space-between.
5) then we move to image , in image we first set there height:450px, width:400px, .
6) Here in image we apply the animation property in which we first see that our image box has box-shadow so give  box-shadow:8px grey ;, then we see that while pointing our cursor to image our image box will move in y-direction it just flip .so fo that we apply transform property as transform:prospective(800px) rotateY(20deg).
7) and while we set the timing of transition for 0.5s.
8) we also notice that while clicking on one image other two image get blur and that pointed image opecity increases . so for that we apply css as ..first we give property to (.container:hover img) it simplify that after hover to one image other image opecity will be decreases so we set the opecity:0.3.
9) then we set to (.container img:hover) it means when we hover on image there opecity:1 and transform:prospective(800px) rotateY(20deg).
10) soo by this way i have comlpletd my animation project.
