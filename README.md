# photogrammetry_1

## Question-1
Explain Sentinel-2 dataset. Which bands do you get when you download the dataset? What are bands' 
characteristics ( both geometric and radiometric)?

## Answer-1
Our bands are aerosol detection, red, blue, green, vegetation classification, near infrared, water vapour,
cirrus, snow / ice / cloud discrimination. The 13 spectral bands of Sentinel-2 range from Visible (VNIR) 
and Near Infrared (NIR) to Shortwave Infrared (SWIR): 4 x 10 meters Tapes: three classic RGB tape ((Blue 
(~ 493nm), Green (560nm) and Red (~ 665nm))) and Near Infrared (~ 833nm) tape; 6 x 20 meters Bands: 
4 narrow Bands (~ 704nm, ~ 740nm, ~ 783nm and ~ 865nm) in VNIR vegetation red edge spectral area 2 
wide SWIR bands (~ 1610nm and ~ 2190nm) snow / ice / cloud detection or vegetation moisture stress 
assessment; 3 x 60 meters Tapes mostly for cloud scanning and atmospheric correction (~ 443nm for 
aerosols and ~ 945nm for water vapor) and focused on cirrus detection (~ 1374nm).
Radiometric resolution is the instrument's capacity to distinguish between light intensity or reflection 
differences.The greater the radiometric resolution, the more accurate the perceived image.

## Question-2
Open and read all bands of your Sentinel-2 dataset. Choose an area from the dataset and find the area in 
all bands. Do you see any differences? Does the appearance of the area change from band to band? 
Explain.

## Answer-2
The difference between the two images increased pixel values, so the colors became more apparent. 
brightness also increased.

## Question-3
Why do we need different bands other than RGB? Which band combinations help us detect clouds in an 
image?
## Answer-3
We need to distinguish objects of different wavelengths that visible light cannot distinguish. For 
example, we need different bands to distinguish rain cloud and chlorophyll in plants. So we use bands 
other than RGB. To detect clouds: 2 wide SWIR bands (~ 1610nm and ~ 2190nm) snow / ice / cloud 
detection or vegetation moisture stress assessment, 3 x 60 meters Tapes mostly for cloud scanning and 
atmospheric correction (~ 443nm for aerosols and ~ 945nm for water vapor ).

