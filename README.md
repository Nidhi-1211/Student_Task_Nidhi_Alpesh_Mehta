# Student_Task_Nidhi_Alpesh_Mehta

**Git repository** 

**Task 1**

Step 1: Clone the repository in the destination of your choice, using the following command:

git clone https://github.com/Nidhi-1211/Nyris_student_task.git

Step 2: Please read the **README.md** file before starting 

**Downloading the dataset** 

Please download the Image dataset from https://drive.google.com/file/d/1hbzc_P1FuxMkcabkgn9ZKinBwW683j45/view before starting. 

Save the dataset in the same folder as the git repository is saved 

Step 1: Open the folder where dataset is saved. Create two new folders and name them as "train" and "test" respectively.

Step 2: From the image folder copy first 100 folders to the train folder and rest 100 folders to the test folder respectively.

Step 3 : Open the Juypter notebook and copy the path of folder where the dataset is saved as an input to "dataset_path".

Step 4: Run each cell in the Juypter notebook.

**Task 2**

- The first cell will import all the neccessary packages to finish all the tasks.
- Ensure that you have entered the "dataset_path" in the first cell.
- In the next cell a dataframe is created where all necessary information is stored.
- EDA is done on the dataset where you can view the image and also locate the birds in the images along with the classname. 
- Also the average height and width of the images in the dataset can be seen in the box plot which gives an idea about the size of the images in the dataset.
- Two CSV files are created, the test_data.csv and train_data.csv which has the information about the train and test subdataset.

**Task 3**

- Further the train and test dataset are loaded 
- A pretrained model is chosen " ResNet 50" to extract the features
- The extracted features are saved as numpy files as "test_features.npy" and "train_features.npy" 

**Task 4**

- Information of metrics used to evaluate the Image Retrieval models.
