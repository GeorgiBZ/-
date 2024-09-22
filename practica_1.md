# Practica 1
## Задача 1
```
cat /etc/passwd | tr ":" " " |  awk '{ print $1 }' | sort | xargs
```
## Задача 2
```
cat /etc/protocols | grep '^[^#]' | sort -r -nk2 | awk '{ print $2" "$1 }' | head -5
```
## Задача 3
```
s='+-'
x=${#1}
for ((i=0; i<x; i++))
do
        s=$s'-'
done
s=$s'-+'
echo $s
echo '| '$1' |'
echo $s
```
## Задача 4

## Задача 5
```
chmod $2 $1
cp $1 /usr/local/bin
```
## Задача 6
```
cat $1 | head -1 | grep '^[#]'
```

## Задача 7

## Задача 8

## Задача 9

## Задача 10





