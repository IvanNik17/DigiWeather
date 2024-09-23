# DigiWeather
Synthetic rain, snow and fog Dataset Augmentation using the Unity game engine and data pre-processing

Github repository for the XR Salento 2024 paper. The code, paper link, and augmented dataset link will be added in the following months.

The augmented dataset Weathervenue can be found on this link: [Weathervenue on Kaggle](https://www.kaggle.com/datasets/ivannikolov/weathervenue-synthetic-weather-augmented-avenue).

You can find the paper here -  [Paper on Springer](https://link.springer.com/chapter/10.1007/978-3-031-71707-9_2) and you can cite it using this latex reference

@InProceedings{10.1007/978-3-031-71707-9_2,
author="Nikolov, Ivan",
editor="De Paolis, Lucio Tommaso
and Arpaia, Pasquale
and Sacco, Marco",
title="DigiWeather: Synthetic Rain, Snow and Fog Dataset Augmentation",
booktitle="Extended Reality",
year="2024",
publisher="Springer Nature Switzerland",
address="Cham",
pages="22--41",
abstract="Ensuring the resilience of deep learning algorithms to data changes, especially in outdoor scenarios with dynamic weather conditions, poses challenges due to limited training data captured in short periods. Weather variations like rain, snow, and fog can introduce concept drift, significantly impacting model accuracy. Expanding datasets with diverse temporal variations is often impractical due to time and cost constraints. Alternatively, we propose an easily deployable and scalable approach to augment weather changes, leveraging the Unity game engine for synthetic image generation. Our method swiftly produces large amounts of augmented videos and images, requires off-the-shelf models only for pre-processing, and allows flexible combinations of effects to simulate various weather conditions. We introduce Weathervenue, an augmented subset of the CUHK Avenue dataset, and employ it in testing four anomaly detection models and models for object detection, semantic segmentation, and depth estimation. Results demonstrate performance degradation ranging from 10{\%} to 35{\%} across all anomaly detectors and visibly worse results for other methods, underscoring the necessity of our solution for creating more challenging scenarios and training robust models. We also show that training on a combination of real and augmented data can boost performance on rain, snow, and fog testing data by up to 10{\%}, while only minimally affecting clear results. Link to the code and augmented dataset https://github.com/IvanNik17/DigiWeather.",
isbn="978-3-031-71707-9"
}
