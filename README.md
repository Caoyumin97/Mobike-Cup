# Mobike-Cup
Mobike Cup data analysis and model development (for practice)

## First Attempt

Regard GeoHashed coordinates as string features:

* procedure: `geohashed_loc(string)`-->`set up vocabulary`-->`one-hot vector`-->`AutoEncoder embedding`

* Accuracy: less than 5%

## Second Attempt

Decode GeoHashed coordinates as raw numerical features.