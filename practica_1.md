# Practica 1
## Задача 1
```
cat /etc/passwd | tr ":" " " |  awk '{ print $1 }' | sort | xargs
```
![image](https://github.com/user-attachments/assets/226b5309-2f7a-43e7-b5d4-9c21198fc295)

## Задача 2
```
cat /etc/protocols | grep '^[^#]' | sort -r -nk2 | awk '{ print $2" "$1 }' | head -5
```
![image](https://github.com/user-attachments/assets/71d70847-5f8e-4447-abf5-e2ab4304f2cf)
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
![image](https://github.com/user-attachments/assets/3402b6b0-1e66-4678-841e-e38bb80293d1)



## Задача 4

## Задача 5
```
chmod $2 $1
cp $1 /usr/local/bin
```
![image](https://github.com/user-attachments/assets/189c908f-1cec-4887-9bf8-c33ef456479a)



## Задача 6
```
cat $1 | head -1 | grep '^[#]'
```
![image](https://github.com/user-attachments/assets/1c2ff65f-26b9-4b00-ad93-baaf9bda21d8)

## Задача 7

## Задача 8

## Задача 9

## Задача 10





