# How to build and use neuromorphic device in SPICE simulation
A neuromorphic device is not a typical electronic device that can be found in SPICE components, so the neuromorphic device can be considered as a third-party model for SPICE. VTEAMr_t.sub is the memristor SPICE model, and the article can be found using the following link.[VTEAM model](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9354151) idealdiode is an ideal diode model.

## How to import the neuromorphic device model
- Open the VTEAMr_t.sub file, right-click the line containing the name of the subcircuit, and select Create Symbol.
![create the symbol](./Figures/create-the-symbol.png "create the symbol")
- Edit the symbol if needed and save.
![symbol](./Figures/symbol.png "the symbol like")
- Select the neuromorphic device (memristor) model and place it in the schematic.
![select and place](./Figures/select-and-place.png "select and place")
- Add the model search path (Please change the path based on where these model files are stored on your computer).
![path](./Figures/path.png "path")
![add the path](./Figures/add-the-path.png "add the path")
- Add the idealdiode link in the schematic (Please change the path based on where these model files are stored on your computer).
![add the instruction](./Figures/add-the-instruction.png "add the link")
![link](./Figures/link.png "the link")