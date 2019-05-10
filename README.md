# AgricultureNet (Segmentation Model )

AGricultureNet is A Highly Customised Segmentation Model that takes in Input data From The LandSat8(MultiSpectral Data(7 Channels)) And Outputs a Segmentation Mask of 256 Crop Categories

## Modifications Made In The Standard Model
Used AN Upward Path With Skip Connections Along With Spatial Excitation 
![Results](Images/Modifications.png)

## Results

The Model Achieved Training Accuracy Over 85% and Validation Accuracy Over 80%.Here Are the Results and the Ground Truth of the Validatio Set 
### Original Ground Truth
![Results](Images/Generated_Mask.png)

### Generated Mask
![Results](Images/Original_Mask.png)

The Segmentation MAsks for Various Crop Categories Are Rendered using CDL Values 
