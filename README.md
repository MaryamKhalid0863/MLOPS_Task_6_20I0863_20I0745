# MLOPS_Task_6_20I0863_20I0745
# Remote Storage of Google Drive:
`https://drive.google.com/drive/folders/1hMnZM0eTz5cjiTbGeSzWZnKgMbY38eTn`

## 20I-0863

# Repository Creation and Dataset Initialization

## Description
This repository was created to collaborate on managing a dataset using Data Version Control (DVC). The dataset has been initialized and added to DVC for versioning and tracking changes. Follow the steps below to get started:

## Instructions for Creating the Repository
1. Clone the repository: `git clone <repository_URL>`
3. Navigate to the cloned repository directory: `cd <repository_name>`
4. Initialize DVC: `dvc init`

![1](https://github.com/MaryamKhalid0863/MLOPS_Task_6_20I0863_20I0745/assets/159745729/6b49a0e9-8532-483a-a105-174a8d16b83a)


5. Add the dataset to DVC: `dvc add <path_to_dataset>`
6. Link the repository to a remote storage location: `dvc remote add origin <remote_storage_URL>`

    ![2](https://github.com/MaryamKhalid0863/MLOPS_Task_6_20I0863_20I0745/assets/159745729/209d5a36-fb53-437f-ae6f-ade70b76500f)

7. Push the dataset to remote storage: `dvc push`
    
![3](https://github.com/MaryamKhalid0863/MLOPS_Task_6_20I0863_20I0745/assets/159745729/e83942d8-22c0-4eeb-a742-e4157147ae31)

8. Commit the changes: `git add .` and `git commit -m "Add dataset"`

   ![4](https://github.com/MaryamKhalid0863/MLOPS_Task_6_20I0863_20I0745/assets/159745729/29be4396-03b1-4905-b20f-85b221dbc19c)


# Repository Cloning and Dataset Retrieval

## Description
This repository is being collaboratively managed using Data Version Control (DVC). Follow the steps below to clone the repository and retrieve the dataset from the remote storage:

## Instructions for Pulling Changes
1. Clone the repository: `git clone <repository_URL>`
2. Navigate to the cloned repository directory: `cd <repository_name>`
3. Initialize DVC: `dvc init`
4. Link the repository to the same remote storage location: `dvc remote add origin <remote_storage_URL>`
5. Pull the dataset from remote storage: `dvc pull`

By following these steps, you'll be able to contribute to the project and retrieve the dataset for further analysis or development.
