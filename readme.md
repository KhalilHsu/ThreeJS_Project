[Video Demo](https://youtu.be/PDl18kSeVag)

***

### Inspiration

The inspiration for this project came from an extremely disappointing London bus ride experience.

Google maps and tfl official website gave different pick-up locations and routes, and my accumulated waiting time exceeded 1 hour. On the way, I also encountered a situation where the driver got off work halfway and could not wait for the next bus after stopping.

So I wanted to **create a scene to satirize London's bad bus experience.**

***

### Library

I used **Three.js** as my main library, and I also used **TweenMax** and **threex **to create some animation effects and display images. I made a lot of attempts throughout the production process of the project, which can be seen in the second half of my code and in a function called oldtest().

***

### How

At the beginning, I used cube and TweenMax to create a loading page.

When you finish loading, You will see a spinning box in the center of the scene, click it! Also, 4 mysterious boxes will appear at the bottom of the scene. **When you click on each box, you will see an automatically generated animation for showing the tips I learnt from London bus.** 

Then go to the scene page, The sky is the classic cloudy color, because I added OrbitControls, so you can **move freely to find some easter eggs.**
The river and road are built with cylinders, and the river surface has the **effect of water waves.**
London Bus is created with a box Geometry. It is worth noting that I made the effect of a **rounded rectangle.**
The postbox is completed in groups of 6 parts, with two postboxes on both sides of the scene.
Also, because the background is a bit empty, I added some **randomly generated boxgeometry.**

Under the premise of consolidating the classroom knowledge of the whole project, I have learned a lot through the Internet, which will be marked below. **Of course the most important thing is that I still use my own code structure.**

***

### Need to improve

The biggest regret is that it is relatively ordinary in terms of aesthetics, and the choice of light and color has not reached a satisfactory state.

The loading page also has the risk of camera movement after being dragged by the mouse.

There is also room for improvement in the completion of the model, and you can learn blender later.

Repeatable clickability of the box.

Add sound feedback.

***

### Resources

> Src for TweenMax:
>
> https://greensock.com/docs/
> https://cdnjs.com/libraries/gsap/2.1.3

> Src for Three.js:
>
> https://github.com/mrdoob/three.js
> https://threejs.org/docs/index.html#manual/en/introduction/Creating-a-scene

> Src for threex.domevents:
>
> https://github.com/jeromeetienne/threex.domevents

> Website Tutorials:
>
> https://tympanus.net/codrops/2016/04/26/the-aviator-animating-basic-3d-scene-threejs/

> Video Tutorials:
>
> https://www.youtube.com/watch?v=YKzyhcyAijo&list=PLRtjMdoYXLf6mvjCmrltvsD0j12ZQDMfE
>
> https://www.youtube.com/watch?v=8jP4xpga6yY
>
> https://www.youtube.com/watch?v=6oFvqLfRnsU&t=1912s

***

#### One more thing

You can run via editor easily, But if you want run directly using browsers, make sure you `--allow-file-access-from-files` for your browsers .

[Example for MacOS Chrome](https://gist.github.com/borella/11285316)