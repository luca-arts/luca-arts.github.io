## text to vector ~~to text~~ to image

![](https://www.kaotec.org/slides/img/encoder.svg)

---

# training data

- lot's of data
    - [laion-5b dataset](https://laion.ai/blog/laion-5b/)
        - 5.85 billion image-text pairs.
    - [train the entire model?](https://huggingface.co/CompVis/stable-diffusion-v1-4)
        - a hard drive of 240TB 
        - 32 x 8 x A100 GPUs
        - cost: approx $ 600,000
        - carbon cost: 11,250 kg CO2 
            - = ± 2.5 cars driving 15,000 km/year

note: 
    if you rent a special PC with massive specs it will still take over a week to just download the data
----

## training on data

the latent space, a gut-feeling approach:

model ==> encoding (a vector/coordinate):

![](https://i.imgur.com/hwXtnoL.png)

[src](https://towardsdatascience.com/understanding-latent-space-in-machine-learning-de5a7c687d8d)


----

### latent space: cats and dogs

note:
    dichtheid op landkaart = vectoren die dicht liggen bij elkaar ==> afbeeldingen die veel gelijkenis vertonen
    enter LEXICA.art ==> zoeken naar LAIKA in space

----

### latent space: cats and dogs


![](https://i.imgur.com/jnAMuuL.jpg)

----

### latent space: cats and dogs

    
![](https://i.imgur.com/I2Cqb7G.png)

note: 
    our AI encoder gave us a sequence of numbers, so we can position the dog on the landmap
    
----

### latent space: cats and dogs


----

### latent space: cats and dogs


![](https://i.imgur.com/uQlL1lF.png)


----

### latent space: cats and dogs


![](https://i.imgur.com/S18N9YN.png)


----

### latent space: cats and dogs


![](https://i.imgur.com/GazZgvX.png)


----

### latent space: cats and dogs


![](https://i.imgur.com/5BAUgfd.png)

----

### latent space: cats and dogs


![](https://i.imgur.com/ryLfZ1N.png)

----

### latent space: cats and dogs

![](https://i.imgur.com/TMhF40S.jpg)

----

### latent space: cats and dogs

![](https://i.imgur.com/2Qe5FQ6.png)

----

### latent space: cats and dogs

![](https://i.imgur.com/LAmfpMl.png)

----

### latent space: IN BETWEEN cats and dogs

![](https://i.imgur.com/YVl6Mme.png)

---

## Different diffusion AI models

DALL-E2
MidJourney
Stable Diffusion
...
