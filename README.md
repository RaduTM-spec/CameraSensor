# CameraSensor
CameraSensor is a tool used in UnityEngine to extract captures from a Camera. It can be used as a sensor for ML Agents.

![preview](https://user-images.githubusercontent.com/67599940/210148761-db254b70-6b49-425a-b1c1-d499f3652f4a.png)

The script has 3 public methods:
1. **Capture()** -> returns a Texture2D
2. **FlatCapture()** -> returns a float[] with the values of a Texture2D capture (depending on the height, width and image type, the array length may vary)
3. **TakeShot()** -> saves a PNG capture in Assets folder (__Take a shot__ button does the same thing)
