# an_interesting_observation
an interesting observation

```
plot(pbinom((1:500)*0.495,1:500,prob=0.5),col=ifelse(1:500%%100==0,1,16))
lines(1:500,pnorm(-0/sqrt(1:500)))
lines(1:500,pnorm(-1/sqrt(1:500)))
lines(1:500,pnorm(-2/sqrt(1:500)))
lines(1:500,pnorm(-3/sqrt(1:500)))
lines(1:500,pnorm(-4/sqrt(1:500)))
lines(1:500,pnorm(-5/sqrt(1:500)))
```
