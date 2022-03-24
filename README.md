# Work makes you happy to some extent, if two much could penalize you happiness score

Fitting different lineal, quadratic and cubic models, and more degrees in R.

<p class="aligncenter">
    <img src="different models.png" alt="centered image" />
</p>

So the lineal model explaining happyness on the basis on working hr is:

*happiness= 44.83 - 0.13hours*

and the cuadratic model explaining happyness on the basis on working hr is:

*happiness = 30.88 + 0.52hours - 0.0038hours^2*

and so on for the others

```
ggplot(more.data,aes(working_hr,hap.score))+
  geom_point(size=5,shape=1,col="blue")+
  theme_bw(base_size = 18)
```
<p class="aligncenter">
    <img src="new figure smooth.png" alt="centered image" />
</p>
