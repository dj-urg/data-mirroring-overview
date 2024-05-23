# Data Mirroring (in progress)

Welcome to Data Mirroring, an open-source initiative designed to help users reflect on their social media usage through the power of data visualization. By providing a "mirror" to your digital behaviors, this project aims to promote awareness, understanding, and thoughtful engagement with social media platforms.

## Overview

Data Mirroring is a methodology developed by Daniel Jurg, Sarah Vis, and Ike Picone at the University of Brussels. This GitHub repository presents a variety of applications developed for 'small-scale data donations'. The purpose is to transform Data Download Packages (DDP) provided by social media companies, specifically TikTok and Instagram, into more manageable formats that can be analyzed with spreadsheet software. Our project is specifically designed to work in conjunction with the 4CAT: Capture and Analysis Toolkit, where the actual analysis takes place. 4CAT is also an open-source application that can be cloned from GitHub and run locally or on a cloud server. For more information, visit the [4CAT GitHub repository](https://github.com/digitalmethodsinitiative/4cat).

## Applications

To perform our Data Mirroring methodology in conjunction with 4CAT, we have developed various applications that simplify the process. These applications can be pulled from their respective repositories:

- **[convert-tiktok-ddp](https://github.com/dj-urg/convert-tiktok-ddp):** Allows you to upload the full DDP you received from TikTok as a JSON file and extract a CSV file containing only the videos you 'browsed', 'liked', and 'favorited'.
- **convert-instagram-ddp:** Allows you to upload specific files from the Data Download Package (DDP) you received from Instagram as a JSON file and extract a CSV file.
- **merge-tiktok-data:** Allows you to merge the captured data from 4CAT with the CSV file from convert-tiktok-ddp.

## Getting Started

To get started with Data Mirroring, please follow these steps:

1. **Request Your Social Media Data:** Obtain your Data Download Package (DDP) from the social media platforms you use, such as TikTok and Instagram.
2. **Clone the Repositories:** Clone the repositories of the applications you need to use for converting and merging your data.
   ```sh
   git clone https://github.com/dj-urg/convert-tiktok-ddp
   git clone [URL for convert-instagram-ddp]
   git clone [URL for merge-tiktok-data]
3. **Install Dependencies:** Navigate to each cloned repository and install the necessary dependencies.
4. **Run the Applications:** Follow the instructions in each repository's README file to run the applications and process your data.

## Contributing
We welcome contributions from the community. If you have suggestions, bug reports, or improvements, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
