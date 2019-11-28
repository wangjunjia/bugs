# ios css overflow hidden dont work

## thinks 

```
https://gist.github.com/ayamflow/b602ab436ac9f05660d9c15190f4fd7b
```

## fuck

way1

```
-webkit-mask-image: -webkit-radial-gradient(white, black);
-webkit-backface-visibility: hidden;
-moz-backface-visibility: hidden;
```

way2 

```
will-change: transform;
```