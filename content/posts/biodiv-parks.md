---
title: "Species Endangerment in American National Parks"
date: 2022-05-03T11:30:03+00:00
# weight: 1
# aliases: ["/first"]
tags: ["project", "class", "python","data-science","data-vis","nps","pandas","matplotlib", "kaggle"]
author: "Daniel Park"
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "Identify patterns in Species Endangerment through all American National Parks"
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: true
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/DanPark13/danpark13.github.io/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---

## Our Ecosystem Now

Biodiversity is the variety of life on Earth at the genetic, species, and ecosystem levels. However, we humans have started exponentially dominating the Earth over the last century, overtaking the planet and causing biodiversity loss through climate change, pollution, habitat destruction, and unsustainable resource use.

However, there is good news. Even though we have used our power to destroy the planet, we also have the power to ensure the integrity of the ecological systems. By understanding the threats to biodiversity, we can effectively plan out our conservation efforts to properly restore our planet's biodiversity through environmental policies on the local and national scales.

## What are our Threats?

But before we can plan out our conservation efforts, we must identify what might cause a species to be under threat. Does location play a major factor? How about the type of species they are? To answer these questions, the National Park Service provides a database containing all the documented plant and animal species within fifty-three national parks in America. Given that the data includes information about each species' locations and conservation statuses identified in the national parks, we can find essential information that may lead to a possibly endangered species.

Let's look at the general biodiversity of our national parks. As seen in **Figure 1**, we see a diverse range of species through all our national parks, with vascular plants, insects, and birds the most dominant species in the parks. We can also see the number of species in each national park, with the most extraordinary biodiversity in the Great Smoky Mountains and Redwood National Parks.

{{< figure src="/images/projects/biodiversity/fig-1.png" caption="**Figure 1**: Species Categories throughout all the national parks" >}}

## Identifying our Species

Even though these two parks have the most diversity, that does not directly translate into the most potentially threatened species. As seen in **Figure 2**, while Redwood National Park does have the second most species potentially endangered at about 180 species, that pales in comparison to the whopping 240 species in concern in Death Valley National Park, both parks of which are located in California. Even with the most diverse national park, we don’t see many species under concern at only about 130 species.

{{< figure src="/images/projects/biodiversity/fig-2.png" caption="**Figure 2**: Conservation Statuses of Species for each National Park" >}}

Outside of park location, the type of animal may also be an area of concern. From **Figure 3**, we can see that vascular plants dominate most species identified in the parks, most likely due to their lack of mobility. However, even with that vast number, as seen in **Figure 4**, while they come in second of total species under a conservation status, we see that birds heavily dominate with over 2500 species at least potentially threatened or endangered species.

{{< figure src="/images/projects/biodiversity/fig-3.png" caption="**Figure 3**: Number of Species for each Category in all the National Parks" >}}

{{< figure src="/images/projects/biodiversity/fig-4.png" caption="**Figure 4**: Conservation Statuses Identified by Species Categories" >}}

## What can we do?

In the United States, it can be jarring to see how many endangered species there are in our supposed protected national parks. However, using our knowledge of the parks' biodiversity, we can reverse our activities and make conscious efforts to learn more about them. And to see species in either Death Valley or Redwood National Parks and birds to be more likely in danger lets us try to piece the causation of these factors into play.

Whether those factors are independent of each other is unknown. However, understanding that these factors exist should help us understand what and where we can focus our efforts in terms of conservation. 

# Sources

- Service, National Park. “Biodiversity in National Parks.” Kaggle, 20 Jan. 2017, https://www.kaggle.com/datasets/nationalparkservice/park-biodiversity. 
- “What Is Biodiversity? Why Is It Important?: AMNH.” American Museum of Natural History, https://www.amnh.org/research/center-for-biodiversity-conservation/what-is-biodiversity.
- “The U.S. Biodiversity Crisis.” National Wildlife Federation, https://www.nwf.org/Magazines/National-Wildlife/2017/Feb-March/Conservation/Biodiversity.
- “Biodiversity.” National Geographic Society, https://www.nationalgeographic.org/encyclopedia/biodiversity/. 


<br>

View the Google Collab Notebook used to research and visualize the data [here](https://colab.research.google.com/drive/1tK9XAwfoGBkYmaM1Ia9wZR0Rhizp0wvM?usp=sharing).

<br>