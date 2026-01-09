# RTFCompare
RTFCompare is an application that helps compare new RTF outputs with previous versions to identify differences.

It is a Python app compiled into single-file Windows 10\11 executable using Nuitka tool. No installation required, just copy to any comvenient location and run.

The main window allows you to select two folders containing RTF files: one with older versions and one with newer versions. You can run the comparison, copy results to the clipboard, or clear the results area. The tool automatically pairs files by filename and analyzes each RTF document, extracting and comparing three sections: Header, Body, and Footer. Differences between versions are clearly displayed in a color-coded results table. Users can also use the main menu or hotkeys to select folders, save results to TXT or CSV files, run comparisons, and more.

There are two checkboxes available:
* **In-text titles and footnotes** – treats text appearing before or after the table structure on each page as titles and footnotes.
* **Indent columns** – adjusts the width of all columns in the identified table structure for better visual appearance in the side-by-side viewer.

Results can be sorted in ascending or descending order by any column.

For detailed analysis, double-click (or press **Enter**) on any file pair to open a side-by-side comparison window. This window features three tabs (Header, Body, Footer) showing extracted text from both versions, with differences highlighted in orange for easy identification. On startup, the window automatically opens the first tab that contains differences, if any.

<img src="Pictures/main_1.png" width="640"> 

Side-by-side comparison:

<img src="Pictures/compare_1.png" width="640"> 

Results copied to the clipboard or saved to TXT or CSV file:

<img src="Pictures/clipboard_1.png" width="320"> <img src="Pictures/csv_1.png" width="320"> 
