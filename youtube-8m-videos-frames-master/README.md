# Youtube-8m Videos and Frames Generator
This repository contains scripts for downloading videos corresponding to a particular or a few categories of [youtube-8m dataset](https://research.google.com/youtube8m/index.html).

reference: https://github.com/gsssrao/youtube-8m-videos-frames

#### Download video-ids  

```
bash downloadcategoryids.sh <number-of-videos> <category-name>
```

This downloads `<number-of-videos>` youtube-ids corresponding to the `category-name` under the folder `category-ids`. If you would like to download all the videos specify `<number-of-videos>` as `0`.

***Example usage***

```
bash downloadcategoryids.sh 0 The Walt Disney Company
```

Be really careful and don't include any extra spaces after the category name. 

Correct category name: "The Walt Disney Company"

Incorrect category name: "The Walt Disney Company " or " The Walt Disney Company" etc.

