# How to deploy the fruit recognition ML model using Docker

1. Make sure you have Docker Desktop installed & Docker engine running
2. Download 'SoftArch' folder as a .zip from the repository and extract it
3. Model is too large to upload to github, so download it from [here](https://mega.nz/file/p90z2L5Y#IuhAeOSg0a1M39eJDgIiZ7OGkLUm8FC_Y5rameWkD7A) and paste it into SoftArch/Fruits folder
4. Using the terminal, go to Softarch/Fruits folder
5. Type 'docker-compose up' in the terminal and execute the command
6. Open the link from the terminal in you browser, this will lead you to a Jupyter repository
7. Open 'Model.ipynb' and run the code in the cells
8. You can predict the label of images in the test_image folder by pasting their path into in filename, custom images can also be added to that folder prior to building the docker image 
