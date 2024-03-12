
# Image Extraction Tool

This Python script extracts a specified number of images from a source directory and copies them to a destination directory. The results, including the names of extracted images and those not found, are saved to a CSV file for further analysis.


## Usage/Examples

#### Clone the Repository:
```python

git clone https://github.com/your-username/your-repository.git
cd your-repository

```


## Installation

Install Dependencies:

```bash
  pip install pandas
```
    
## Running Tests

Modify the script's source directory, destination directory, and CSV file paths if needed. Then run the script:

```bash
  python extract_images.py
```


## Features
   #### Source Directory:
-    Update source_directory variable to the path of your source directory containing the images.

   #### Destination Directory:
   - Update destination_directory variable to the path where you want to save the extracted images.

   #### CSV File Path:
   - Update csv_path variable to the path of your CSV file containing image names to extract.

   #### Number of Images:
   - Update number_of_images_to_extract variable to the desired number of images to extract.


## Contributing

If you'd like to contribute to this project, please follow these steps:

   - Fork the repository.
   - Create a new branch: git checkout -b feature/your-feature.
   - Commit your changes: git commit -m 'Add some feature'.
   - Push to the branch: git push origin feature/your-feature.
   - Submit a pull request.


## License

[MIT](https://choosealicense.com/licenses/mit/)

