# USK-NORMAL-SKIN-DATASET

The skin is one of the parts that protects the human body, besides that it is the heaviest and widest part of 
the body up to 15% of the human body weight with an area of 1.50 to 1.75m2.The classification used for skin 
image recognition is to distinguish between normal skin images and diseased skin images in the Basal Cell Carcinoma 
class using the ISIC 2018 dataset on the website https://challenge.isic-archive.com/data/#2018. It's just that 
due to the unavailability of normal skin datasets (healthy skin) as a comparison, the dataset was created by taking 
skin objects directly on volunteers. After conducting the research, the test results obtained were that the model 
built was able to distinguish between normal skin classes and Basal Cell Carcinoma (sick skin) well, where the accuracy 
of the CLAHE image results was superior compared to using the original image. Native image yield for architecture 
VGG-16 is 98.3%, ResNet-34 is 97.5%, EfficientNet-B0 is 98.2% and EfficientNet-B7 is 99.7%. Whereas in the CLAHE image, 
a higher accuracy value is obtained, namely for the VGG-16 architecture of 100%, ResNet-34 of 99.5%, EfficientNet-B0 
of 100% and EfficientNet-B7 of 100%.

We also introduce a novel dataset called USK-NORMAL SKIN which comes from taking data from willing volunteers aged 
21-60 years on the face, back of the hands and forearms. Our goal is to address the unavailability of publications 
regarding normal skin datasets or healthy skin classes. This image data will be collected manually by taking pictures 
through a digital camera and collecting 170 images from 50 people, 25 male and 25 female. This dataset can be used for 
two tasks, namely classification and detection for normal skin classes that may be tested with diseased skin classes.

![kulit](https://user-images.githubusercontent.com/72331775/230313040-b868a884-952c-4ac9-a616-fddf641fbed8.jpg)

https://comvis.mystrikingly.com/
