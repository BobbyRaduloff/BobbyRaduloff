## Hi there 👋
My name is Boris Radulov, a 21 year old software engineer from Sofia, Bulgaria. I graduated CS from the University of Leeds in 2023 and am currently working on a bunch of different things.
You can reach me at [boris.raduloff@gmail.com](mailto:boris.raduloff@gmail.com).

## Open Source Portfolio
Here, you can find a sample of some of the open-source work I've done.

### [BRDFs](https://gitlab.com/BorisRadulov/final_year_project): Comparative Analysis of Theoretical and Empirical BRDFs in Offline Raytracing
Ray tracing has become the industry standard for photo-realistic rendering. There’s two main questions that must be considered when implementing ray-tracing. Firstly, how exactly rays are calculated and bounced off surfaces. This determines the rendering of shadows and the contributions of lights to the scene. Secondly, how colors are calculated at the intersections of rays and triangles in the surface. This paper tackles both of these questions through the visual and performance analysis of bidirectional reflectance distribution functions (BRDFs). Analysis is performed on multiple BRDFs of varying complexity and a recommendation to use microfacet models is given because of their relatively small impact on performance as compared to the noticeable increase of visual fidelity

Here's a render from it:
![78F3B30E-AC9D-4D4A-9156-E5A814CE50B3](https://github.com/BobbyRaduloff/BobbyRaduloff/assets/17109226/a257bc4e-4c2b-4f4e-948e-e142cc1b084a)

The full paper can be found here: [https://drive.google.com/file/d/1vq5Atux6nN8xdhyHF7pHj1xgKeJbyHZt/view?usp=sharing](https://drive.google.com/file/d/1vq5Atux6nN8xdhyHF7pHj1xgKeJbyHZt/view?usp=sharing).

### [js_rtc](https://github.com/BobbyRaduloff/js_rtc): JavaScript RayTracing engine that renders to a canvas in NextJS
Initially started to answer a final year project research question, the following code realistically renders metalic and diffuse spheres in plain JavaScript, a task which sounds insane but is actually quite doable. It was done in an attempt to measure how far modern browsers have come in terms of performance and to dispell some of the myths regarding client-side javascript.

Here's a render from it:
![js_rtc](https://user-images.githubusercontent.com/17109226/224798346-a2d66907-beab-48db-a866-6b6070fe29eb.png)
