# Cheat Sheet

## Socat
```
socat TCP-LISTEN:<PORT>,fork EXEC:'timeout <TIME_LIMIT> <command>'
```

## Secure Option
trun off canary
```
-fno-stack-protector
```

turn off NX
```
-z execstack
```