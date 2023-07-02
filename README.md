# Dies-wafers-scratch-detection
Predict whether a given die belongs to scratch or not using segmentation.

The data includes information about individual dies from a number of wafers.

The table data includes the following columns:

- `WaferName`: The name of the wafer from which the die came.
- `DieX`: The horizontal position of the die on the wafer.
- `DieY`: The vertical position of the die on the wafer.
- `IsGoodDie`: A binary column indicating whether the die is good or not.
- `IsScratchDie`: A binary column indicating whether the die belongs to a scratch or not.

The goal is to use the training data to build a model that can predict, given a certain wafer map, the dies on the map that are parts of a scratch (whether they are bad, 'Scratch' or good, 'Ink').

![image](https://github.com/Yossi5004/Dies-wafers-scratch-detection/assets/113097631/8b0cc359-300e-4a7d-9f06-2b9c308fd324)


![image](https://github.com/Yossi5004/Dies-wafers-scratch-detection/assets/113097631/bfa84cbc-b3c1-4f73-9afc-06e67917180d)
