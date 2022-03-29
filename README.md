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
```
cat -Path C:\Users\Fran\Documents\Ejercicio3SI\TestFile.txt | gm
```
![image](https://user-images.githubusercontent.com/91600940/160676451-21772139-d604-45a1-8343-6b87ba05247b.png)

## 6. Overwrite all data within the text file that you createdin task 3.
```
Set-Content -Path C:\Users\Fran\Documents\Ejercicio3SI\TestFile.txt -Value "Boooooo"
```
![image](https://user-images.githubusercontent.com/91600940/160676852-0b9063b8-6f17-4560-a917-0ed5ac2d9d36.png)

## 7. Format the data returned by a cmdlet into a list.
Get-Service | Format-List
```
Get-Service | Format-List
```
![image](https://user-images.githubusercontent.com/91600940/160677336-51e07466-c1fe-428d-891b-4997abe65ac7.png)

## 8. Format the data returned by a cmdlet into a list.
Pipe “Get-Command” into “Out-GridView”
```
Get-Command | Out-GridView
```
![image](https://user-images.githubusercontent.com/91600940/160677549-c7dcb2b5-64c5-4b9b-95c4-43e5ad8bc729.png)

## 9. Pipe the 5 cmdlets you discovered in task 1 into “Out-GridView”.
```
Get-Service | Out-GridView
```
![image](https://user-images.githubusercontent.com/91600940/160678333-a6c3f3d2-66f6-4631-9b0a-2b834c6a5388.png)
```
Get-Help | Out-GridView
```
![image](https://user-images.githubusercontent.com/91600940/160678496-81cd0aca-0f0a-4237-bed8-2edf03d0098c.png)

```
Get-Alias | Out-GridView
```
![image](https://user-images.githubusercontent.com/91600940/160679028-9b5f6865-c975-4e45-9981-2d1620b0f2ce.png)

```
Get-ControlPanelItem | Out-GridView
```
![image](https://user-images.githubusercontent.com/91600940/160679177-42d92ccf-d1f0-4134-b812-d647cfd7cf8b.png)

```
Get-FormatData | Out-GridView
```
![image](https://user-images.githubusercontent.com/91600940/160679810-e8192dbd-f229-4a83-b1a9-39bc4a289d0a.png)


## 10. Find the official PowerShell documentation library from Microsoft.

[Link a la documentación de microsoft](https://docs.microsoft.com/en-us/powershell/)

