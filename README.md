# week_3_assignment
Through the document detect the table and identify the table structure using hugging face libraries

1. Load and preprocess the image: Load the document image and preprocess it for TATR.
2. Table detection: Use table-transformer-detection to find table bounding boxes.
3. Extract table regions: Crop detected table regions.
4. Table structure recognition: Use table-transformer-structure-recognition to decompose tables into cells.
5. Save to CSV: Format each table as a DataFrame and save it to CSV within the image name.All the csv files collect to the one csv_out folder.
