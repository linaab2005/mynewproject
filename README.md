
<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Project Title

AI-based plant identifier

## Summary

The idea is to create an AI app that can identify plants by analyzing pictures taken by the user. The app will help the people who love nature and gardening with gathering information about the plants in their surroundings faster.  


## Background

Many people who spend their time in nature are curious of what plants they are surrounded by. With the help of this AI app a single picture can answer questions about which plant it is and how to take care of it if wanting to plant it, which improves the knowledge biological diversity. This would also prevent people from interacting with dangerous or toxic plants which decreases the number of poisonings caused by plants. This idea inspires me for the reason that I myself am a nature lover and on my walks it often happens that I see plants which I don't know anything about and I would have to search manually to find information about the plant. 

## How is it used?

The app can be used when taking a walk or when finding a plant that is unknown to oneself. It would usually be used by gardeners, nature lovers or even students who are writing a project or doing research involving plants. The app is used by taking a picture of a plant with the mobile camera, which allowes the AI to analyze the picture and compare it to a database with plant species. When that is done the app will give information about the plant such as its name, maintenance and other useful facts. 

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Plant](https://www.freepik.com/free-vector/plant-pot-cartoon_28881307.htm#fromView=keyword&page=1&position=0&uuid=b9a583f0-bd8d-4487-a4f7-5ffb1ac49471&new_detail=true)
![Plant](https://www.freepik.com/premium-vector/green-plant-red-pot-3d-icon-houseplant-potted-plant-flower-home-garden-3d-vector-illustration-white-background-gardening-nature-decoration-botany-concept_42332064.htm#fromView=keyword&page=1&position=25&uuid=45446277-cd53-4263-89cc-7c731b7edba4&new_detail=true)


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
[USDA](https://plants.usda.gov/)
[Plants Database](https://garden.org/plants/)
[WFO Plant list](https://wfoplantlist.org/))

## Challenges

A challenge with this app is that similiar plants may be difficult to distinguish or that incorrect identifications can arise. This could be avoided, but it would need huge amounts of training data of pictures of plants from different angles, in different lightning and stages of growth. To gather this much data is challenging. 

## What next?

A function that would help this idea to improve is to add crowdsourcing, which allows the users to contribute with their own pictures and enlarge the database. This way, the app can use the information from other users in the future which decreases the risk of incorrect identifications. 


## Acknowledgments
[Pl@ntNet](https://identify.plantnet.org/sv) / [Plant.id](https://plant.id/) 
