# Generate Faces
## Generative Adversarial Networks
### Project 3:
**Taregt:**
Defining two adversarial networks, Generator and Discriminator, and training them until generating realistic human faces.

**Output:**
- The graph represents the way the discriminator is distinguishing between fake and real image so the generator updates itself to ensure better prediction.
![output](https://github.com/Yasmin-Hesham/Deep-Learning-Udacity-Nanodegree/blob/master/4-Generate%20Faces/sample_output/graph.PNG)
- The output generated faces after _20 epochs_. Some generated faces are mostly real, however others are still in progress.
![faces](https://github.com/Yasmin-Hesham/Deep-Learning-Udacity-Nanodegree/blob/master/4-Generate%20Faces/sample_output/generated_faces.PNG)

The output sample images declear the biasing of dataset towards white faces, maybe it should be more generalized to ensure all racial faces. Also, skin's color, mustache , hair and sex have an impact of face's generation.   
