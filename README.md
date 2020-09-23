<div align="center">

## ASCII Generator


</div>

### Description

Generates ASCII Value for every known character to a textbox. Good for developement using character...and stuff.

NOTE: PEOPLE WHO DOWNLOAD AND RAN THE ZIPPED VERSION OF THIS CODE MAY HAVE A VIRUS ON THEIR SYSTEM CALLED WIN95.CIH. YOU CAN LOOK IT UP AT NORMAN.COM. IF YOU ARE ONE OF THESE PEOPLE PLEASE DELETE THE FILE AND RUN A SYSTEM CHECK WITH A VIRUS SCANNER. SORRY FOR THE INCONVENIENCE.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Jared Collums](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/jared-collums.md)
**Level**          |Intermediate
**User Rating**    |5.0 (5 globes from 1 user)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0, VB Script
**Category**       |[VB function enhancement](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/vb-function-enhancement__1-25.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/jared-collums-ascii-generator__1-5906/archive/master.zip)





### Source Code

```
Function ASCIItoList(ListBox As Object)
Dim Character As Long
For Character& = 33 To 223
ListBox.AddItem Chr(Character&)
Next Character&
End Function
Private Sub Form_Load()
ASCIItoList List1
End Sub
Private Sub List1_Click()
Text1.Text = "Chr(" & List1.ListIndex + 33 & ")"
End Sub
```

