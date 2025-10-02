# Fair_Machine_learning_project

The perpous of this project is to peform fairness analysis and model analysis on META's FACET data set for computer vision. The over all goal is to expose any bias that my have occured during the data collection process and or during model creation.

## Running .ipynb files

It is highley recommended that you run the .ipynb files inside of google colab in order to save yourself the headache of running the project files manually.

To do that follow these steps: 
1. Open the desired `.ipynb` file on GitHub.

2. Click the "Open in Colab" button if available, or copy the GitHub URL of the notebook.

3. Go to [Google Colab](https://colab.research.google.com/).

4. Click on "File" > "Open notebook", then select the "GitHub" tab and paste the notebook URL, or upload the notebook file directly.

5. To ensure the project runs, you need to have the `annotations.csv` data file available in your Colab environment. You can do this by:
    - Uploading the file manually: In Colab, click the folder icon on the left sidebar, then click the upload button and select `annotations.csv` from your local machine.
    - Or, if the file is hosted online (e.g., in your GitHub repo), use the following code in a Colab cell to download it:
      ```python
      !wget https://raw.githubusercontent.com/your-username/your-repo/main/path/to/annotations.csv
      ```
    - Make sure the path to `annotations.csv` in your notebook matches its location in the Colab environment.

6. Once the data is uploaded, you can run the notebook cells as usual.
