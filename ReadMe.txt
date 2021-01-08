                                                      



                                                          -------BAGGAGE PROJECT README FILE---------------

THERE ARE TOTAL 5 METHOD:

1. METHOD 1  
   NAME              : crop_object_from_image(image)
   WHAT IT DOES      : cropping the object from threat image 
   DETAIL EXPLANATION: I have Loaded the image, converted it to grayscale, Gaussian blur, Otsu's threshold, then Obtained bounding 
                       rectangle and extracted ROI, then saved the ROI image.
   SAVED FILE NAME    : Image_crop.jpg
   
2. METHOD 2  
   NAME              : resize_image(image)
   WHAT IT DOES      : resizing the image 
   DETAIL EXPLANATION: I have Created an Image Object from an Image then made the new image half the width and half the height of 
                       the original image and saved the new resized image
   SAVED FILE NAME    : resized-image.jpg
   
3. METHOD 3  
   NAME              : rotate_image(image)
   WHAT IT DOES      : rotate the image to 45 degree
   DETAIL EXPLANATION: I have Created an Image Object from an Image then rotaed a image 45 deg counter clockwise and saved the image.
   SAVED FILE NAME    : rotate_image.jpg
   
4. METHOD 4  
   NAME              : converting_white_background_to_tranparent(image)
   WHAT IT DOES      : convert the object_image white background to transparent
   DETAIL EXPLANATION: firstly, I made the color little transparent (to have that real look when pasted with baggage) then if condition
                       saying discard the pixel which has color in the range of white and saved the image.
   SAVED FILE NAME    : white_tranparent.png
   
5. METHOD 5  
   NAME              : pasting_object_on_image(baggage_image, object_image)
   WHAT IT DOES      : pasting the object_image on baggage 
   DETAIL EXPLANATION: Firstly, I made a new image with certain boundary, before pasting both the image (baggage and object_image) on 
                      the new image, i have used a new method named Object_inside_Baggage(image) which will take image and return 
                      the image boundary starting and ending coordinates.This method will help in the setting a certain range for 
                      the object_image, so that it remain in that range , i.e., i want the object image to remain inside the baggage
                      and not to cross the boundar. if it cross its coordiate, a message will be printed saying to change the coordinate.
                      If successful, the image will be saved.
   SAVED FILE NAME    : output.png




-----------------------------------------------------------------------------===

The steps to follow.
        1. run METHOD 1 (put the original threat image name in it),  then image saved, use that recent image name to put in furher method.
        2. run METHOD 2 (put the image name which has been saved while running the method just before this) , image is saved. again use
           the recent image name for further process.
        3. run METHOD 3 (put the image name which has been saved while running the method just before this)
        4. run METHOD 4 (put the image name which has been saved while running the method just before this)
        5. run METHOD 5 (put the image name which has been saved while running the method just before this)
        6. the final image is saved named as "output.png"