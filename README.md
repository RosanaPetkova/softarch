# How to deploy the fruit recognition ML model using Docker

1. Make sure you have Docker Desktop installed & Docker engine running

*You can download Docker Desktop app from [here](https://www.docker.com/products/docker-desktop/).*  
*Once app is installed, open it and make sure engine is running:*  
![image](https://user-images.githubusercontent.com/98345993/178155347-be1a82e5-6ab9-4e65-bc9b-d556f289a132.png)

3. Download 'SoftArch' folder as a .zip from the repository and extract it into a folder of your choice
4. Using the terminal, go to Softarch\Fruits folder
5. Type 'docker-compose up' in the terminal and execute the command
6. Open the link from the terminal in you browser, this will lead you to a Jupyter repository
7. Open 'Model.ipynb' and run the code in the cells
8. You can predict the label of images in the test_image folder by pasting their path into in filename, custom images can also be added to that folder prior to building the docker image 
