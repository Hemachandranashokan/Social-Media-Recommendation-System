# Social Media Recommendation System

This project is a social media recommendation system that provides personalized post recommendations using a hybrid approach. It combines **content-based filtering** and **collaborative filtering**, leveraging semantic embeddings and user interaction data for accurate suggestions.

## Features
- **Content-Based Filtering**: Recommends posts based on content similarity using SentenceTransformers.
- **Collaborative Filtering**: Suggests posts by analyzing user-user interactions.
- **Hybrid Approach**: Integrates content and collaborative methods for improved accuracy.
- **Scalable Design**: Can be extended for large-scale applications with databases and real-time updates.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Navigate to the project folder:
  ```bash
cd your-repo-name
```
3. Install the required dependencies:
  ```bash
pip install -r requirements.txt
```
## Usage
1.Prepare the dataset of user interactions and post metadata (a sample dataset is included in the code)
2.Run the script to generate recommendations:
```bash
python recommendation_system.py
```
##Example Output
1.For a user who interacted with "AI in healthcare", the system might recommend:
i)"AI and data science are the future."
ii)"Deep learning advances in image recognition."
2.Future Enhancements:
i)Integrate a database for handling large datasets.
ii)Add real-time recommendations for live systems.
iii)Explore reinforcement learning to adapt recommendations dynamically.
  
