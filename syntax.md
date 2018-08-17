# Sample Syntax for [Open-Close-Cross (OCC)](https://profitview.app/signal ) Indicator: 


**LONG**
```
c=order t=open
c=position b=short t=market
delay=2
b=long l=10 q=50% t=market

q= and l= needs to be adjusted to your needs
```

**SHORT**
```
c=order t=open
c=position b=long t=market
delay=2
b=short l=10 q=50% t=market

q= and l= needs to be adjusted to your needs
```

**SL and TP** (two separate alerts)
```
c=order t=open
c=position b=short t=market
c=position b=long t=market
```

Syntax | Sample
------------ | -------------
Long | ![GitHub Logo](https://i.imgur.com/O68yVkc.png)
