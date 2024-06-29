# Importing Data to a Firestore Database || [GSP642](https://www.cloudskillsboost.google/focuses/489700?parent=course_template) ||

# # Like, comment, share & Don't forget to subscribe [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN) 👍😄🤝

* ### Go to `Firestore` from [here](https://console.cloud.google.com/firestore/databases?referrer=search&project=qwiklabs-gcp-03-e5778dff4206)
  
* ### Then follow the next steps from the video

* ### Run the following Commands in CloudShell
```
gcloud auth list
gcloud config list project

git clone https://github.com/rosera/pet-theory
cd pet-theory/lab01
npm install @google-cloud/firestore
npm install @google-cloud/logging

curl -LO raw.githubusercontent.com/Techcps/GSP-Short-Trick/master/Importing%20Data%20to%20a%20Firestore%20Database/importTestData.js

npm install faker@5.5.3

curl -LO raw.githubusercontent.com/Techcps/GSP-Short-Trick/master/Importing%20Data%20to%20a%20Firestore%20Database/createTestData.js

node createTestData 1000
node importTestData customers_1000.csv
npm install csv-parse
```

# Congratulations ..!! You completed the lab shortly..😃💯

# *Well done..!* 👏

# Thank you for visiting.... :) 🗯️

# [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN)
 
