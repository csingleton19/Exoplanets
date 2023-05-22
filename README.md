# Exoplanets

## CoRoT-2b file

This is an example of one of the exoplanet transit detections I was ran. An exoplanet transit is when a planet passes in front of a star in the line of site from a telescope from Earth, which causes an observable and minute drop in brightness. This is a simple framework that takes the data, converts it to 'instrumental magnitude', which is to say how bright the target star is relative to other stars in the image (vs absolute, which is essentially a comparison across every star), and plots the data over time. It takes the average before + after the planet started transiting (aka the baseline), and the average while the transit is ocurring, and plots it and displays the difference between them. It also finishes a stastistial analysis of the data. If the data is determined to be stastically significant, a transit can be considered to be observationally valid - which it is in this case :)

## LR - Exoplanetary Mass prediction

This Linear Regression is a basic exploration into the relationship between the mass of an exoplanet with the radius of it. The data was pulled from a NASA archive, and was of the roughly ~5k known and confirmed exoplanets that have both a mass and radius measurement. It is a simple linear regression that was trained on all of the aforementioned data, gets the intercept and coefficient, and then has a simple function that generates the predicted mass based off of the radius
