# Título do Paper

(Título do paper), (explicar um pouco)

---
## Repository Structure
 
```
├── data/
│   ├── Data_Brazilian_politicians.xlsx    # Tabular dataset
│   └── Data_Brazilian_politicians.csv     # Tabular dataset
│   └── image/
│       ├── tiktok.7z
│       │   ├── lula/
│       │   └── bolsonaro/
│       ├── instagram.7z
│       │   ├── lula/
│       │   └── bolsonaro/
│       └── facebook.7z
│           ├── lula/
│           └── bolsonaro/
└── README.md
```
---
## File Formats

Both files contain the same data.  
The dataset was published in two formats:
- **CSV**
- **XLSX**

### Images
The images are located in the `image/` folder, organized by social media and candidate.  
Each folder contains subfolders that contain images of Lula ('./lula') and Bolsonaro ('./bolsonaro').  
All images have an ID in their name (example: `17921054648487667.jpg`), which you can identify by analyzing the table, more specifically the ID column.  
Each `.7z` file contains images collected from the respective social media during the 2022 Brazilian presidential campaign:
- 'tiktok.7z': contains images of candidates Lula and Bolsonaro on the TikTok social network.
- 'instagram.7z': contains images of candidates Lula and Bolsonaro on the Instagram social network.
- 'facebook.7z': contains images of candidates Lula and Bolsonaro on the Facebook social network.    
----
> Algumas limitações:

---
Outro tópico, caso queira
