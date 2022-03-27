# Ejercicio-3-SI

Ejercicio de clase 3. Primitive Datatype tasks

## 1. Use “Get-Help” to find out more information about 5 cmdlets.
```
Get-Help New-Item
```
![image](https://user-images.githubusercontent.com/91600940/160278202-de3ab26f-4815-420c-a04f-72028d793483.png)

```
Get-Help Add-Content
```
![image](https://user-images.githubusercontent.com/91600940/160278273-f4edaa1a-fdf4-4c66-975b-e410e20932fb.png)

```
Get-Help Get-Content
```
![image](https://user-images.githubusercontent.com/91600940/160278327-3bdb8569-95a2-4a6f-84bd-fd2d9668a80b.png)

```
Get-Help Set-Content
```
![image](https://user-images.githubusercontent.com/91600940/160278419-450ef241-345f-452e-9b61-8676cd3c4836.png)


```
Get-Help Get-Service
```
![image](https://user-images.githubusercontent.com/91600940/160278452-17436a18-c8d6-4d6d-90f8-9ddd713337ac.png)



## 2. Use “Get-Help” with the “–Example” parameter for the 5 cmdlets you discovered more about in task 1.
```
Get-Help New-Item -Examples
```
![image](https://user-images.githubusercontent.com/91600940/160278787-20e3eda0-e553-4efe-a85a-6048cc56699d.png)

```
Get-Help Add-Content -Examples
```
![image](https://user-images.githubusercontent.com/91600940/160278958-dd91e3a1-c033-4b52-8e26-cd82af1982dc.png)


```
Get-Help Get-Content -Examples
```
![image](https://user-images.githubusercontent.com/91600940/160279030-8a920ee1-f8c7-4ff3-aa82-0fc2390607d3.png)


```
Get-Help Set-Content -Examples
```
![image](https://user-images.githubusercontent.com/91600940/160279056-84199e5e-db4f-4d14-8b58-70d3bbe68d38.png)


```
Get-Help Get-Service -Examples
```
![image](https://user-images.githubusercontent.com/91600940/160279083-9de85129-8ff0-4f04-a989-f67dfff9f753.png)


## 3. Create a new text file named “TestFile.txt” under C:\Maximo\PowerShell\Workshop1\%USERNAME%

```
ni -Path C:\Users\Fran\Documents -Name Ejercicio3SI -ItemType Directory
ni -Path C:\Users\Fran\Documents\Ejercicio3SI\ -Name TestFile.txt -ItemType File
```

## 4. Populate the text file you created in task 3 with allthree datatypes we’ve covered: “Boolean”, “Strig” and “Int”
```
ac -Path C:\Users\Fran\Documents\Ejercicio3SI\TestFile.txt -Value True
ac -Path C:\Users\Fran\Documents\Ejercicio3SI\TestFile.txt -Value "Prueba"
ac -Path C:\Users\Fran\Documents\Ejercicio3SI\TestFile.txt -Value 42
```
![image](https://user-images.githubusercontent.com/91600940/160285208-f1c3e005-5b9f-4203-b772-9bdc49ad0219.png)

## 5. Read from the text file and use “Get-Member” to find the datatype returned

