This project is a POC for reverse image search for fashion (specifically TShirts) on ONDC items. 

- Scraped tshirts data from an ONDC website.
- Used Resnet 50 for feature extraction and conducted reverse image search using cosine similarity.
- Fine-tuned YoloV8 for cropping Tshirts to provide more focused image to Resnet model for feature extraction.
- Created triplets of 2 same and 1 different tshirt for training using Triplet loss.
- Trained a model (transfer learning) using Resnet 50 and Triplet Loss for extracting features from Tshirt images and grouping similar tshirts together.
