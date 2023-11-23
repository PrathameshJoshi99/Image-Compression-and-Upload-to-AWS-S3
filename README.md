# Image-Compression-and-Upload-to-AWS-S3

Overview
This Python script is designed to perform lossless image compression on JPEG and PNG files within a specified directory and subsequently upload the compressed images to an AWS S3 bucket. The compression is achieved using the Pillow library, while the AWS interactions are handled using the boto3 library.

Requirements
Python 3.x
Pillow library (pip install pillow)
Boto3 library (pip install boto3)
Usage
Clone the repository or download the script.
Install the required libraries using the provided requirements.txt file (pip install -r requirements.txt).
Replace the placeholder values in the script with your AWS credentials (aws_access_key, aws_secret_key), AWS S3 bucket name (bucket_name), and the path to the target directory (target_directory).
Run the script (python script_name.py).
Script Details
The script traverses through the specified directory and identifies image files with extensions .jpg, .jpeg, and .png.
It applies lossless compression to each image using the Pillow library.
Compressed images are saved in a directory structure mirrored from the original, appended with "_compressed."
The script uploads the compressed images to the specified AWS S3 bucket while retaining the original file structure.
Important Notes
Ensure that the required Python libraries (Pillow and boto3) are installed.
Replace placeholder values in the script with your actual AWS credentials and directory path.
The script optimizes images for S3 storage, maintaining original quality during compression.
License
This script is provided under the MIT License.

Author
Prathamesh Joshi

Feel free to contact joshiprathamesh01@gmail.com for any questions or issues.

Note: This readme assumes that you are familiar with setting up AWS credentials and have the necessary permissions for S3 operations.
