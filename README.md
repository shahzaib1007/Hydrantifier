# Tool Name: Hydrantifier
By: Shahzaib Khan (@shahzaib1007) and Sydney Carr (@sydneycarr)

# Objective: 
Asset management is an integral part of the utility industry, and GIS has become an important tool for managing large spatial databases. Accurately migrating historic records for existing infrastructure into the GIS environment, however, requires time, money, and resources. In practice, engineering departments may not have the capacity to prioritize and realize this objective on a large scale.
Object detection and deep learning present an opportunity to develop robust geospatial databases with significantly fewer resources. Within the scope of this project, our objective is to develop a model that will identify and locate fire hydrants on Google Street View to produce a geospatial database in the GIS environment. For the purpose of feasibility, we are targeting a single water utility asset, but future work could extend to include many different assets across many different industries.

# Case Study
Washington Water Service (WWS) is a private water utility company with 220 water systems serving 40,000 customers across western Washington. The newly acquired Southwood Water System located in Graham, Washington lacks detailed documentation for infrastructure installed in the field and specifically lacks location data for existing fire hydrants. We will apply our model to the extent of the Southwood Water System and attempt to produce a geospatial database for the fire hydrants within the given study area.

# Data & References
We will download and annotate imagery from Google Earth and Google Street View to build our
dataset. Engineers at WWS will share location information for the Southwood Water System.
There are various algorithms to perform object detection, we will be using the algorithms
described here for our ease. We will discuss the same with Prof. Cynthia
https://machinelearningmastery.com/object-recognition-with-deep-learning/
https://analyticsindiamag.com/top-8-algorithms-for-object-detection/
Downloading and annotating Google Street View imagery:
https://www.createwithswift.com/creating-annotated-data-sets-with-ibm-cloud-annotations/
Open source references for object detection:
amusi/awesome-object-detection: Awesome Object Detection based on handong1587 github:
https://handong1587.github.io/deep_learning/2015/10/09/object-detection.html

# Model Hypothesis
Downloading imagery and annotating the dataset will likely be the most limiting factor when
developing our model. Given the scope of the project, our priority will be to learn and
understand the concepts behind object detection versus building a larger dataset, and we
therefore might lose overall model accuracy. But our general hypothesis is that our model will be
able to identify a large percentage of fire hydrants within the proposed study location.
