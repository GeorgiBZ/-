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
![image](https://github.com/user-attachments/assets/7cffc2fd-34a3-4d20-84f5-a9bffe22ead1)


## Задача 4

## Задача 5
```
chmod $2 $1
cp $1 /usr/local/bin
```
![image](https://github.com/user-attachments/assets/d6359f28-ed85-46c7-8e49-0ebe9d47830f)


## Задача 6
```
cat $1 | head -1 | grep '^[#]'
```
![image](https://github.com/user-attachments/assets/25bc60eb-05e0-4876-b1f5-faf2ccdace14)

## Задача 7

## Задача 8

## Задача 9

## Задача 10





