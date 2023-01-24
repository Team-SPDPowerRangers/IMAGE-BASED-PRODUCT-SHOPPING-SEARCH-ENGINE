# IMAGE-BASED-PRODUCT-SHOPPING-SEARCH-ENGINE


### OUR PROJECT IN BRIEF
	- The motto of this project is to develop and application easy to use for everyone and address people with dyslexia and make it easy for them to shop by searching based on image as an input and buy the required things.

	- This project is an Image Based Product Recognition and Classification Model used to detect similar product in a dataset given an input image. 

	- All features from images present in dataset are extracted and stored. When an image is given as input to search for similar images, its features are also extracted.

	- How similar two images are is measured by calculating difference between input image and each and every image present in dataset. The less the difference is, the more the similarity is. This way, the top 10 best similar images are returned.

	- Everythig has GUI incorporated, making it easy for everyone to use.


### MODULES USED
-> The following modules are used in our project:	
	- Tensorflow : to build CNN model
	- Keras		 : to build layers for CNN model
	- VGG16		 : for image classificaiton
	- PCA		 : for selecting top n features
	- Scipy		 : for distance calculation between two images
	- Numpy		 : to deal with arrays
	- OpenCV	 : to read and show images
	- Pandas	 : to work with dataframes


### CONTENTS DESCRIPTION
-> Please find the following files in the folder
	1. Folders named as follows:
		a. dataset - containing 183 images in total
		b. RealTimeTestImages - containing 7 test images captured in realtime
	2. Excel file named 'Images Dataset Product Description.xlsx'
	3. Text files named as follows:
		a. cartdetails.txt
		b. temp.txt
		c. query_imagepath.txt
		d. paths.txt
	4. Image file named 'shopping.png' used to show the login and search windows
	5. IPYNB file named 'GUI.ipynb' contating the code for this project


### IMPLEMENTATION
	- Please keep all files in the same manner
	- This is a jupyter notebook file. Please run the cell one by one in the order as follows.
		1. All cells under Image Classification
		2. LOGIN Window
		3. Search Window
		4. Product Display Window
		5. Load Window
		6. Cart window
	  Please close all the windows for the first time as it is inly getting initialized.
  	- Now, run the cell under Login Window to start implemtation
  		1. Enter credentials as specified and click 'LOGIN' button to proceed
  		2. Now click on 'LOAD PRODUCT' button to proceed
  			You will see a window pop-up to select any image present in your system
  			After selection you will see the selected image in the window.
		3. Once the product is loaded, click on 'SEARCH' button to start searching
		4. After a while you can see another window displaying all the images similar to the input image
		5. Click on desired image and you will see a pop-up to select the required quantity of that product and click 'OK' after specifying to add them into cart.
		6. Step-5 can be repeated as many time required
		7. After adding product to cart click the 'VIEW CART' button to take you to cart and see the slected products	
	- Files named paths.txt, temp.txt, will get re-written based on implementation


### RESULTS
	- As the products are added to cart, you can view them and make payment and buy them accordingly.
