<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# FL-Combat-Predictor

Simple ML-model that predicts the outcome of a combat in the table top RPG Forbidden Lands.Final project for the Building AI course

## Summary

Predicts the outcome of a combat in Forbidden Lands based on parameters such as the total strength of the party, how many sessions the campaign has been going, amount of useful artifacts within the party etc. Will be trained on data from my own campaign but also has the option to provide


## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

Combat in Forbidden Lands can be very deadly. Knowing at the start of a combat whether to fight or flee can be useful if you want the party to live. It can also be useful for deciding whether to delve into a dangerous situation or not. You could argue that letting the players know what the model predicts ruins the excitement of the game, knowing the probable encounter of the game. But it could also elevate the fun; Imagine the model predicting that the players will either die or flee, but they decide to stay and fight anyways - knowing that they are probably gonna die. That could really add some dramatic value to the scene. A quick disclaimer though: I am probably not gonna use it that way, just trying to come up with excuses as to why it could be useful.

## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

The model can be used during a Forbidden Lands session, or in between sessions. Since there is a lot of overlap between people that play RPGs and people that know how to code, I choose to assume that at least one person at the table have some experience with programming. Therefor I wont create a GUI and instead the model takes user input through the console

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
