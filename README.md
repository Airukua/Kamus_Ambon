
# Melayu (Ambon) Word Dictionary

Ambon is an island located in the central part of the Maluku Islands in Indonesia. The island is renowned for its natural beauty and diversity, featuring lush green hills, white sandy beaches, and clear blue waters. However, Ambon's history also carries deep and complex layers.

The island has a long history that includes periods of colonization by various colonial powers. In the 16th century, the Portuguese were the first Europeans to arrive and established forts as trading posts for highly valuable spices. Eventually, they were replaced by the Dutch, who took control of Ambon in the 17th century after intense battles and treaties with the Portuguese. For centuries, the island became a key center for the spice trade, especially for cloves and nutmeg, which were highly sought after by European traders.

During the Dutch colonial period, Ambon experienced various periods of tension and rebellion by the indigenous population resisting colonial oppression and exploitation. One notable resistance was the Pattimura War in the early 19th century, led by Kapitan Pattimura. Although efforts to gain independence from Dutch colonial rule were not immediately successful, this spirit of resistance became a significant part of Ambon’s cultural heritage.

Ambon's rich and diverse history reflects the island's journey from the colonial era to Indonesia’s independence, and it carries a deeper meaning regarding the cultural identity and bravery of its people in facing historical challenges.

This Ambonese dictionary combines words from the **Kamus Bahasa Ambon** published in 1998 by D. Takaria and C. Pieter, with terms taken from the **Ambonese Malay Bible**.

---

### Accessing the Dictionary via Google Colab

#### ✅ Option 1: Download the dictionary file directly

```python
# Direct URL to the raw .txt file
file_url = "https://raw.githubusercontent.com/Airukua/Kamus_Ambon/master/kamus_alk_ambon.txt"

# Desired path to save the file
file_path = "kamus_alk_ambon.txt"

# Download the file using urllib
import urllib.request
urllib.request.urlretrieve(file_url, file_path)

print(f"File '{file_path}' has been downloaded.")
```

#### ✅ Option 2: Clone the entire repository (if you want all files)

```python
# Clone the full GitHub repository
!git clone https://github.com/Airukua/Kamus_Ambon.git
```

Then, access the file with:

```python
import pandas as pd

# Load the file from the cloned repository
df = pd.read_csv("Kamus_Ambon/kamus_alk_ambon.txt", header=None, encoding='iso-8859-1')
```

