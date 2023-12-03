# airbus-ship-detection

The goal of this challange is to detect and mask ships from satellite images. There are both trainig and test data available with masks on the ships encoded with a run-lenght encoding style, as we will se later. The main difficult is due to the fact that the dataset is very big and unbalanced in a sense of presence of ships in the images.

### Prerequisites
* Python 3 (3.10 preferable)
* pip, venv modules available On the fresh systems these things might be absent

### Environment setup
First of all, you will need to initialize your own .env file, create python virtual environment and install necessary packages:

```
python -m venv venv
.\venv\Scripts\activate
```

To train locally, on your own host machine, it's required to download kaggle competition dataset first. It's suggested to store it in the dataset folder. 