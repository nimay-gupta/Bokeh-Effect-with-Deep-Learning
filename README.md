# Bokeh Effect with Deep Learning

Bokeh is an important artistic effect used to highlight the main object of interest on the photo by blurring all out-of-focus areas. While DSLR and system camera lenses can render this effect naturally, mobile cameras are unable to produce shallow depth-of-field photos due to a very small aperture diameter of their optics. Unlike the current solutions simulating bokeh by applying Gaussian blur to image background, in this paper we propose to learn a realistic shallow focus technique directly from the photos produced by DSLR cameras.

For this, we present a large-scale bokeh dataset consisting of 5K shallow / wide depth-of-field image pairs captured using the Canon 7D DSLR with 50mm f/1.8 lenses. We use these images to train a deep learning model to reproduce a natural bokeh effect based on a single narrow-aperture image. The experimental results show that the proposed approach is able to render a plausible non-uniform bokeh even in case of complex input data with multiple objects. 

In this project, you will implement this method and generate qualitative results on aforementioned dataset, and take a step further in understanding neural networks. Finally, you will document your learnings and results in a report. 

Note that a good knowledge of *Deep Learning* is appreciated for this project.

![](https://github.com/nimay-gupta/Bokeh-Effect-with-Deep-Learning/blob/main/im.jpeg)


## Structure and Timeline

1. **Reading**:
You will read and present the paper. Note that the paper is a bit on the harder side to understand thoroughly. 

2. **Programming**:
You will code in Python using  PyTorch (preferable).
The majority of the time for implementation should be devoted to training and experimenting on the second phase.  

3. **Writing**:
You will submit a short report (around 5 pages, typeset in LaTeX) explaining what you did in the project. 
It is recommended to *not* leave this till the end, as writing helps crystallize concepts. A document can be maintained to track weekly/daily progress.

The project duration is 15 Dec - 15 Jan. 
This is not much time, so we'll structure the timeline in five-day periods (qweeks: quick week).

| Qweek(s) | Dates           | Plan                                  |
| -------- | --------------- | ------------------------------------- |
| 0-0.5    | 15 Dec - 18 Dec | Reading and Understanding the paper   |
| 0.5-1.5  | 18 Dec - 25 Dec | Implementing and Training the phase 1 |
| 1.5 - 3  | 25 Dec - 4 Jan  | Implementing the phase 2              |
| 4        | 4 Jan - 10 Jan  | Conducting various experiments        |
| 5        | 10 Jan - 15 Jan | Writing                               |
 

## References

[1] Rendering Natural Camera Bokeh Effect with Deep Learning, CVPR 2020

https://arxiv.org/abs/2006.05698

Special thanks to [Akkapaka Saikiran](https://github.com/akkapakasaikiran) (via [Niraj Mahajan](https://github.com/nirajmahajan)), for the document skeleton.
