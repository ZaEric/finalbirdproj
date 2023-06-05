# Finalprojbirds

## Note:
This project was just the default kaggle bird species classification one. Everything was done on kaggle, I just downloaded the code over to github to basically use the readme for the 'website'. I was thinking of just summarizing everything in the kaggle notebook itself and share that, but I'm not sure if its possible to share the notebook by link and note have it be visible to everyone, so github it is.

## What I Used (Pre-existing work)
- Predict method from the tutorial on cse 455 website to evaluate on test set and create the actual csv submission file
- The get_bird_data (ImageFolder + DataLoader), though had to modify to split training into 80/20 sets

## Problem Setup
I first basically just used the example from the tutorial on the cse 455 website, transfer learning with birds. This was basically just me familiarizing myself with the pytorch syntax and using kaggle collab. Afterwards, I tried different models and techniques. I'm still kind of new to kaggle, and I wasn't able to find a way to run the model in the background without saving and making a new version, so my notebook just has a lot of versions (22 - most failed to some some error). Here's a general overview of what I did and the score I got:

## Try 1 - Resnet18 (tutorial)
Basically just the "Transfer Learning to Birds" from website. I was trying to work out how the given dataset is formatted, what the other files (labels, names, sample) were and if they were relevant to training the model, etc.
