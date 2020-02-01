# CLID (Corneal Lesions Image Dataset)

The CLID dataset currently contains 30 images of the cornea’s surface, ac- quired during medical procedures with different lighting conditions and equip- ment, and including different types and levels of corneal lesions, thus increasing the variability of the data. The images were captured using a Topcon Sle corneal topographer, with 10 × magnification, in diffused lighting.  The photos were obtained using an iPhone 5s smartphone connected to the Topcon Sle corneal topographer. After image capture, an experienced ophthalmologist, with a Ph.D. in applied sciences to surgery and ophthalmology, marked the area corresponding to the lesion in 140 the anterior eye segment in red, and the total area under analysis in blue, using a touch stylus pen. The specialist chose the red and blue colors of the marking because of the contrast with the background.e 

# How To Use

Each image folder has two image files. One file representind the original image named "N_orig" (where N is the number of the image), and another file named N (where N is the number of the image). The files the "_orig" sufix represent the original image, while the other file is the image marked by the ophthalmologist. 


    ```
    /Dataset
    --/1
    --/--/1
    --/--/1_orig
    --/2
    --/--/2
    --/--/2_orig

    etc...

    ```
