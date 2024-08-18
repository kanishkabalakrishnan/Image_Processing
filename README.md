                                               IMAGE PROCESSING

Image processing is a method to perform operations on an image to enhance it or extract useful information. This repository showcases various image processing techniques implemented in Python, ranging from basic filtering to advanced segmentation and tracking.
Image Sharpening:
    Sharpening is a technique used to enhance the edges and fine details in an image. It increases the contrast along edges, making the image appear clearer and crisper.
Resize the image
   img_resized=cv2.resize(img,None,fx=0.25,fy=0.25)
   fig,ax=plt.subplots(figsize=(10,8))
   ax.imshow(img_resized)
   plt.show()
Why Do We Resize Images?
Reduce Computational Load:
        Speed: Working with smaller images is faster for processing, analysis, or displaying, especially in applications like machine learning, where multiple images 
               are processed in quick succession.
        Memory: Large images consume more memory, and resizing them helps reduce the memory footprint.
