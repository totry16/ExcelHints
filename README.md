# ExcelHints
In Windows 10 and Office 365, 

Take control over the data set and keep it intact!

## Shortcuts
The power of the keyboard, try it out!

✔ Win +
numbers 1 to 9 starting programs
e.g. 1. File explorer, 2 browser (Vivaldi), 3 mail, 4 obsidian 5 word 6 zotero, 7 excel 8 rstudio 9 dictionary.

✔ In File explorer: Right click filename &rarr; "your folder"

✔ Windows:

| Win + |                 | Win + |               |
| ----- | --------------- | ----- | ------------- |
| tab   | recent apps     | a     | action center |
| t     | taskbar         | k     | connect       |
| arrow | move app window | v     | clips         |
| i     | setting         | m     | hide windows  |
| u     | screen setting  | l     | log on        |
| x     | windows tools   |       |               |
| r     | run             |       |               |


✔ Excel:

|     |           |     |         |
| --- | --------- | --- | ------- |
| F2  | edit cell | F12 | Save as | 


| Ctr + |            | Ctr +    |                 |
| ----- | ---------- | -------- | --------------- |
| c     | copy       | F1       | ribbon on/off   |
| x     | cut        | F2       | edit cell       |
| v     | paste      | F4       |  close               |
| z     | rewind     | 1-5      | formatting      |
| a     | select all | +        | insert (beware) |
| w     | close      | -        | delete (beware) |
| q     | exit       | Home/End | first/last cell | 




## Pesky behavior (beware)
**Defense:** Throughout the project, check the dataset's number of entries, 1. total 2. pure numbers 3. character items -though they may look like an ordinary number.

✔ Preformatting.
- Dates: E.g. number "1.1" &rarr; "1.jan" &rarr; "1.jan.21" &rarr; "44197" (datenumber)
- Characters: "1" &rarr; with a hidden character "'1" &rarr; which will not be included in the calculation. Usually due to imported columns of numbers, but the entry was interpreted as a character.
 
✔  Distorted cell relationship, no warning:

![Cupy-cut](figExcel/Pasted%20image%2020220102111416.png)

✔ Using tables, and function is set to autocopy.