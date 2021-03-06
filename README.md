# What is the purpose of this notebook and project?
As an application of the use of the pandas library, the notebook basically shows some data manipulation and cleaning of an open dataset using [```pandas```](https://github.com/pandas-dev/pandas). There is also a ```.py``` script as a reference for validating the code on the **PEP8** good practices of programming. To do so, you will need to have ```pylint``` and ```pandas``` installed:

    $pip install pylint
    $pip install pandas

For running the PEP8 tests:

    $pylint guided_project_script.py

# About the dataset
The [dataset](https://data.world/data-society/used-cars-data) stores informations of used cars from *eBay Kleinanzeigen*, a classifieds section of the German *eBay website*.

Its columns are:
* ```dateCrawled``` - When this ad was first crawled. All field-values are.
* ```taken``` from this date.
* ```name``` - Name of the car.
* ```seller``` - Whether the seller is private or a dealer.
* ```offerType``` - The type of listing
* ```price``` - The price on the ad to sell the car.
* ```abtest``` - Whether the listing is included in an A/B test.
* ```vehicleType``` - The vehicle Type.
* ```yearOfRegistration``` - The year in which the car was first registered.
* ```gearbox``` - The transmission type.
* ```powerPS``` - The power of the car in PS.
* ```model``` - The car model name.
* ```kilometer``` - How many kilometers the car has driven.
* ```monthOfRegistration``` - The month in which the car was first registered.
* ```fuelType``` - What type of fuel the car uses.
* ```brand``` - The brand of the car.
* ```notRepairedDamage``` - If the car has a damage which is not yet repaired.
* ```dateCreated``` - The date on which the eBay listing was created.
* ```nrOfPictures``` - The number of pictures in the ad.
* ```postalCode``` - The postal code for the location of the vehicle.
* ```lastSeenOnline``` - When the crawler saw this ad last online.