# ImageScramble: 
Can be used to create a scrambled counterpart of any image. It achieve the goal by randomly re-arrange location of the pixels. 

# SHINE_Pre_Processing_Tool
It was created to meet the requirements for using the legendary OG SHINE toolbox(http://www.mapageweb.umontreal.ca/gosselif/SHINE/), in which required the images to be ***grayscale images of the same size***. The present tool was tailered to meet both of the afromentioned requirements, along with the ability to scale(resize) and modify file type.  
   
   ## How to use the SHINE_Pre_Processing_Tool:
   0. run the script in any IDE you want
   1. tick the required options 
      - Convert to Grayscale: Tick this if you want to convert images into grayscale. (which is required for the OG SHINE toolbox)
      - Process Subfolders: Tick this if you want to process ALL images (in the nested subfolders) under the current directory.
   2. Source File Type: Specify what file type(s) should the tool look for.
   3. Desired File Type: Specify the file type for the output files.
   4. Resolution: Choose the resulution for the output images, just note that by choosing the non aspect ratio retaining options (e.g., 128*128), the images will be forced into the  specified resulution(beware of distortion). If you wish to retain the original aspect ratio, pick the "Retain Aspect Ratio" options. The tool will look for the longer side of the original image and scale it to the specified size. (e.g., a 64x10 original image will be scale to 128x20 if the "Retain Aspect Ratio Max Width 128px" was chosen)
   5. The last one is just a simple reminder! 
   6. press "Proceed!!"
   7. You will be promped to provide the directory of the ***source folders***. Navigate to the folder containing the image(s) to be processed.
   8. After confirming the input images, you will now need to select the ***output folder***, navigate to the desired directory.
   9. Done! 
