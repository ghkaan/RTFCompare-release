# RTFCompare
RTFCompare - app which helps to compare new RTF outputs vs previous version to identify differences.

Python app compiled into Windows onefile-executable using Nuitka tool.

The main window allows you to select two folders containing RTF files: one with older versions and one with newer versions. You can run comparison, copy results to the clipboard, clear results area. The tool automatically pairs files by filename and analyzes each RTF document, extracting and comparing three sections: Header, Body, and Footer. Differences between versions are clearly displayed in a color-coded results table.

For detailed analysis, double-click or press Enter on any file pair to open a side-by-side comparison window. This window features three tabs (Header, Body, Footer) showing extracted text from both versions, with differences highlighted 
in orange for easy identification.

<img src="Pictures/main_1.png" width="640"> 

Side-by-side comparison:

<img src="Pictures/compare_1.png" width="640"> 

Reults copied to the clipboard or saved to txt file:

<img src="Pictures/clipboard_1.png" width="320"> 
