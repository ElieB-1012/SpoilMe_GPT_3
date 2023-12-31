# SpoilMe

As part of my project, I developed artificial intelligence that aims to predict the likely ending of a movie in a human-like manner. My goal was to create a model that could provide answers in the form of a sentence, imitating the way I think and speak.

To achieve this goal, I used the GPT-3 artificial intelligence model, a trendy technology, and adapted it to my needs using a fine-tuning technique. I fed this model a database of over 1000 sets containing movie synopses and key plot elements, which are not revealed in the synopsis itself (spoilers). This approach allowed me to adapt and develop logic specific to my purpose. After training my model and running tests on 300 new abstracts, I found a success rate of 12%. This means that in 12% of cases, my AI was able to predict an actual key event in the movie's plot. This project opens up interesting perspectives by allowing a machine to respond and provide answers similar to those of a human in the field of predicting the end of a movie. Although my current success rate can be improved, it demonstrates the capabilities of the GPT-3 model to understand data and generate relevant answers. I continue to work on this project, exploring potential improvements to increase the accuracy of my predictions. My goal is to develop even better artificial intelligence to analyze synopses and offer captivating answers, thus igniting the excitement of movie lovers who want to discover the exciting plots behind each synopsis.

## App Picture

<p align="center">
  <img src="SpoilMe app.png" width="400" height="400">
</p>

## Creation of Dataset

Despite conducting an extensive search for a suitable dataset, I was unable to find one that met my project's needs. This prompted me to make the decision to create my own dataset. During my search, I came across a website called 'MoviePooper,' which offers spoilers for a wide range of movies. Since the data on this website was not available through an API, I opted to perform data scraping using Octoparse to extract the required information. To enrich my dataset further, I merged it with a second dataset that I found on Kaggle, containing synopses for 1700 movies.

## Worklow

<p align="center">
  <img src="Workflow.png" width="800" height="400">
</p>

## Workflow to create the model

<p align="center">
  <img src="Workflow_model.png" width="400" height="400">
</p>



