# Steam-Game-Recommender-AI

This project was a final project for my Artificial Intelligence class in College. The project was complete in collaboration with Michael Treacy, another student at the University. We spent the semester researching and understanding AI models, applying them to the project to make a steam game recommendation system with only games and hours played per user as an input. For a detailed reading on the AI agents and how we went about building the system, the final report is included in the repository.

## README Directory

- [File Directory](##-File-Directory "Goto File-Directory")
- [Dependencies](##-Dependencies "Goto Dependencies")
  - [Installing NumPy](###-Installing-NumPy "Goto Installing NumPy")
  - [Installing Pandas](###-Installing-Pandas "Goto Installing Pandas")
- [How To Run the Code](##-How-To-Run-the-Code "Goto How To Run the Code")
- [Credit / Acknowledgements](##-Credit-/-Acknowledgements "Goto Credit-/-Acknowledgements")
- [References](##-References "Goto References")

## File Directory

Code AI Models:

- treacy_lamberson_model_1_code.ipynb
  - Contained within this file is all of the code for refined model, which was build roughly on the foundation of Model 2.
- treacy_lamberson_Model2.ipynb
  - Contained within this file is all of the code for the original model, which did not have a built in "rating" system based off of Mix-Max normalizaion.

Data:

- steam-200k.csv
  - Contains all the required data to work through the AI agents, all in the correct format. This data was obtained from Kaggle.

Final Report:

- treacy_lamberson_fp.pdf
  - This file contains the extensive report submitted for the project. This 9 page document details the specifics of the project, diving deep into the cleaning and rating systems used throughout the development of the project.

Presentation:

- presentation_link.pdf
  - A file made to house the presentation video when it was submitted to the professor.
- treacy_lamberson_presentation.pptx
  - The final presentation made for the class.

## Dependencies

In order to run the Jupyter Notebook files (.ipynb), you are going to need Python (2 or 3), and the following libraries:

- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)

### Installing NumPy

In order to install NumPy, we used the pip package manager that comes with Python. You can check if your machine has pip by typing:

```bash
python3 -m pip --version
```

or

```bash
pip -V
```

Once you have verified that you have pip installed, it can be used to install NumPy by typing the following command:

```bash
pip install numpy
```

You can find more information on installing NumPy [here](https://numpy.org/install/).

### Installing Pandas

In order to install Pandas, we used the pip package manager that comes with Python. You can check if your machine has pip by typing:

```bash
python3 -m pip --version
```

or

```bash
pip -V
```

Once you have verified that you have pip installed, it can be used to install Pandas by typing the following command:

```bash
pip install pandas
```

You can find more information on installing Pandas [here](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html).

## How To Run the Code

The project was completed using a Jupyter Notebook to run Python code in segments. We used Python3, with the NumPy and Pandas libraries to process the data. You can open the Jupyter Notebook files in Visual Studio Code (VSCode) and begin to run them using the following extenstion:

> Name: Jupyter
> Id: ms-toolsai.jupyter
> Description: Jupyter notebook support, interactive programming and computing that supports Intellisense, debugging and more.
> Publisher: Microsoft
> VS Marketplace Link: <https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter>

This will allow step through the notebook and fun the cells of the notebook file either all together or one by one. The results of the AI agent will generate within the file and give outputs to the screen.

## Credit / Acknowledgements

A special shoutout to our Professor, Jonathan Mwaura who was an excellent resource for guiding the project throughout the semester. Professor Mwaura provided excellent supervision and recommendations when refining and optimizing the project, teaching us more about the impact that AI can have.

The data used throughout the project was obtained from a Kaggle database, which can be found [here](https://www.kaggle.com/tamber/steam-video-games).

### References

[1] A. Biswas, K. S. Vineeth, A. Jain and Mohana, “Development of Product Recommendation Engine By Collaborative Filtering and Association Rule Mining Using Machine Learning Algorithms”, 2020 Fourth International Conference on Inventive Systems and Control (ICISC), Coimbatore, India, January 2020, pp. 272-277, doi: 10.1109/ICISC47916.2020.9171210.

[2] S. J. Russell and P. Norvig, Artificial Intelligence: A Modern Approach, 3rd ed. Upper Saddle River, NJ, USA: Prentice Hall, 2010.

[3] M. H. Mohamed, M. H. Khafagy, and M. H. Ibrahim, “Recommender Systems Challenges and Solutions Survey”, 2019 International Conference on Innovative Trends in Computer Engineering (ITCE), Innovative Trends in Computer Engineering (ITCE), 2019 International Conference, Aswan, Egypt, February 2019, pp. 149–155, doi: 10.1109/ITCE.2019.8646645.

[4] D. J. Dudhia, S. R. Dave, and S. Yagnik, “Self Attentive Product Recommender – A Hybrid Approach with Machine Learning and Neural Network”, 2020 International Conference for Emerging Technology (INCET) Emerging Technology (INCET), 2020 International Conference, Belgaum, India, June 2020, pp. 1–4, doi: 10.1109/INCET49848.2020.9154034.

[5] F. R. Rehman. “Min Max Normalization in data mining.” T4Tutorials. <https://t4tutorials.com/min-max-normalization-of-data-in-data-mining/> (accessed December 15, 2020).

[6] S. Marafi. “Collaborative Filtering with Python.” Salem Marafi. <http://www.salemmarafi.com/code/collaborative-filtering-with-python/#:~:text=Collaborative%20Filtering%20with%20Python%201%20Refresher%3A%20The%20Last.FM,collaborative%20Filtering.%20...%204%20Entire%20Code%205%20Referenence> (accessed December 15, 2020).

[7] Santhosh. “Recommendation Systems: Collaborative Filtering just with numpy and pandas, A-Z.” Medium. <https://medium.com/@sam.mail2me/recommendation-systems-collaborative-filtering-just-with-numpy-and-pandas-a-z-fa9868a95da2> (accessed December 15, 2020).

[8] Kaggle User, “steam_game_recommender.” Kaggle. <https://www.kaggle.com/jwyang91/steam-game-recommender> (accessed December 15, 2020).

[9] Tamber, “Steam Video Games Version 3.” (2016). Distributed by Steam. <https://www.kaggle.com/tamber/steam-video-games> (accessed December 15, 2020).

[10] PACKT Publishing, Birmingham, England. Building recommendation systems with Python (2019). Accessed: December 15, 2020. [Online] Available: <http://search.ebscohost.com.umasslowell.idm.oclc.org/login.aspx?direct=true&db=edsasp&AN>= edsasp.ASP4740624.marc&site=eds-live

[11] Wikipedia. “Collaborative filtering.” Wikipedia. <https://en.wikipedia.org/wiki/Collaborative_filtering> (accessed December 15, 2020)
