# M&A Predictive Analysis Project
## How to Use

- Clone Repo
- Download the zipped Data from https://drive.google.com/file/d/14HL3TcDUb9mNE1kqSvJGUmQZBTWTbPm8/view?usp=sharing
- Place it into data collection into a folder named NewData

Current repository directory should look like this

* data collection
	* M_A_News.csv
	* NewData
		* [Downloaded Unzipped Data]
* CLEAN_ClassificationNewData.ipynb
* CLEAN_Classification_isM_A.ipynb
* CLEAN_LDAonNews.ipynb
* README.md

From there:

* Run “CLEAN_LDAonNews.ipynb” first to generate “lda.sav” and “cv.sav” in the same folder.
* Make sure the above two models are existing in the “Final Package” folder.    
*  If you want to find the topics for M&A and general news, run “CLEAN_Classification_isM&A.ipynb”
* For the final classification for 1/3/6/12 month news article, run “CLEAN_ClassificationNewData.ipynb”. This code will generate a sub-folder called “ClassifyNews”. The generated feature table will saved in this folder. The results will print in the stdout console.
	
