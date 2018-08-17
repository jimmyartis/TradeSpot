# Sample Syntax for [Open-Close-Cross (OCC)](https://profitview.app/signal ) Indicator: 


**LONG**
```c=order t=open
c=position b=short t=market
delay=2
b=long l=10 q=50% t=market
```

**SHORT**
```c=order t=open
c=position b=long t=market
delay=2
b=short l=10 q=50% t=market
```

**SL and TP**
```c=order t=open
c=position b=short t=market
c=position b=long t=market
```

q= and l= needs to be adjusted to your needs

![GitHub Logo](https://i.imgur.com/EUTZ6VS.jpg)
