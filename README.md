# waterServiceCalulator
This is an excel spreadsheet calculator for sizing water service and water pipes. 

1. Use the drop-down lists in B3:B22 to change number of plumbing fixtures in the system.
2. The sum of water fixture units in D23 is converted to GPM using a modified Hunters’ curve and returned to D25
3. Rows 25 to 31 are for additional demands. The emergency station number of units are only editable.
4. Enter main line size in cell E33			
5. Enter water meter size in cell E34			
6. Enter longest enveloped run in cell E35
7. Enter building height here in cell D37
8. The residual pressure is uneditable and automatically returned from selection of flush valve, emergency fixture or minimum allowed by code.
6. Enter water meter pressure drop in cell E39
7. Enter the loss through the reduced pressure backflow preventor. It’s always around 10 to 15 psi	
7. Your answer is in cell E45.
This tells you how to get our main and branch line sizes. Yes, it is a little weird to start off with entering the main line size to get a parameter you use to select a min line size, but this is an iterative process. This number marks a vertical line on the pipe friction loss chart about the axis labeled "friction loss psi per 100 ft", and all values to the left of this line are invalid. You can also use this to create a fixture unit vs pipe size table to size branch lines, the county of LA also requires you to put this on the plans too.

See additional charts and pipe friction loss calculator in other sheets in this workbook.
Cells with CPC references and other select cells are left editable for general use of the calculator, i.e., UPC, ASPE, etc.
