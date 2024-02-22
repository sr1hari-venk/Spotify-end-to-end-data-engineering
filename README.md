# Spotify End-to-End Data Engineering

### Description:

Implemented complete Data Pipeline Data Engineering Project using Spotify:
- Integrated with Spotify API and extracting Data.
- Deployed code on AWS Lambda for Data Extraction.
- Added trigger to run the extraction automatically.
- Wrote transformation function.
- Built automated trigger on transformation function.
- Stored files on S3 properly.
- Built Analytics Tables on data files using Glue and Athena.

### Architecture Diagram:
![Architecture Diagram](https://github.com/sr1hari-venk/Spotify-end-to-end-data-engineering/blob/main/Architecture%20Diagram.jpg)

### About API:
The API is from Spotify, which contains the top 50 streaming songs as of today. The dataset contains information on artist name, album name, song name, ranking number, available countries, album release date, etc.

### AWS Servives Used:
1. S3 (Simple Storage Service)
2. AWS Lambda
3. CloudWatch
4. Glue Crawler
5. Data Catalog
6. Amazon Athena

### Python Packages Used:
1. Spotipy
2. Pandas
3. DateTime

### Project Execution Flow:
Extract Data from API -> Lambda Trigger (Once a day) -> Run Extract Code -> Store Raw Data -> Trigger Transform Function -> Transform Data & Load -> Query data on Athena

##### Guided project by [Darshil Parmar](https://github.com/darshilparmar).

##### This was a capstone project part of the '[Python for Data Engineering](https://learn.datawithdarshil.com/courses/Python-for-Data-Engineering-63dbd4e2e4b04e40a25e4445)' course on DataVidya.
