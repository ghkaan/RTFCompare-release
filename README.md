# RTFCompare
RTFCompare - app which helps to compare new RTF outputs vs previous version to identify differences.

Python app compiled into Windows onefile-executable using Nuitka tool.

The main window allows you to select two folders containing RTF files: one with older versions and one with newer versions. You can run comparison, copy results to the clipboard, clear results area. The tool automatically pairs files by filename and analyzes each RTF document, extracting and comparing three sections: Header, Body, and Footer. Differences between versions are clearly displayed in a color-coded results table. User can also use main menu or hotkeys to select folders, save results to txt or csv file, run comparison etc.

There are two checkboxes: Intext titles and footontes - this one can be used to treat text entered before or after the table structure on each page as titles and footnotes, Indent columns - to adjust width of all columns in identified table structure for better visual appearance in side-by-side viewer.

Results can be sorted in ascending or descending order by any column.

For detailed analysis, double-click or press Enter on any file pair to open a side-by-side comparison window. This window features three tabs (Header, Body, Footer) showing extracted text from both versions, with differences highlighted 
in orange for easy identification. On start the window will automatically show the first tab with differences if there are any.

<img src="Pictures/main_1.png" width="640"> 

Side-by-side comparison:

<img src="Pictures/compare_1.png" width="640"> 

Reults copied to the clipboard or saved to txt file:

<img src="Pictures/clipboard_1.png" width="480"> 
