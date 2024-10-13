The data has the following structure:

* Records are stored for each user who made purchases, every day.
* Each date has its own folder, and inside that folder, there are subfolders for each user.
* Within each user's folder, there is a file called data.csv, where the data is stored.

The structure looks like this:

└── data
   ├── 2020-12-30
   │  ├── FirstName_LastName1
   │  │   └── data.csv
   │  ├── FirstName_LastName2
   │  │   └── data.csv
   │  └── FirstName_LastName3
   │      └── data.csv
   └── 2020-12-31
      ├── FirstName_LastName1
      │   └── data.csv
      └── FirstName_LastName5
          └── data.csv
