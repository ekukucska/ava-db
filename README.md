# ava-db

This repository contains JSON files for the MongoDB database used in my capstone project (**"Medical Sensor Data Visualization Using the MERN Stack and Plotly.js."**) developed as part of my Bachelor's degree in Computer Science at Universitatea „Tibiscus” - Timișoara.

These files can be imported directly into MongoDB to recreate the database structure.

---

## Contents

Each JSON file corresponds to a specific MongoDB collection:

- `anomalies.json`
- `events.json`
- `patches.json`
- `studies.json`
- `subjects.json`
- `users.json`

---

## How to Import the Data

To import the collections into a local MongoDB instance:

1. Make sure MongoDB is installed and running on your system.
2. Open a terminal and navigate to the folder containing the JSON files.
3. Run the following command for each file:

```bash
mongoimport --db ava-db --collection <collection-name> --file <filename>.json --jsonArray
```
