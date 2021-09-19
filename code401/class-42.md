# Location

1. Create location services client in onCreate method

`fusedLocationClient = LocationServices.getFusedLocationProviderClient(this);`

2. Get the last known location

```
fusedLocationClient.getLastLocation()
        .addOnSuccessListener(this, new OnSuccessListener<Location>() {
            @Override
            public void onSuccess(Location location) {
                // Got last known location. In some rare situations this can be null.
                if (location != null) {
                    // Logic to handle location object
                }
            }
        });
```
3. getLastLocation()
4. getCurrentLocation()


Reference :
* [Location](https://developer.android.com/training/location/retrieve-current)