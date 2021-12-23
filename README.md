# Reversing SmartHalo 2 App

As the company behind SmartHalo went bankrupt, this is an attempt to reversing their application and getting it to run again. I hate having a brick on my bike.

## Findings:

* The App is not obfuscated, so reversing it with jadx is super easy
* API URL is in `bike.smarthalo.app.BuildConfig` (leads to `https://api.smarthalo.bike/` which does not exist anymore)