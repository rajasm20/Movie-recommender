 1.The main idea to select the 5 recommended movies is based on cosine similarity. The movie name is a text field which is expressed as a vector.
 A vector is a single dimensional NumPy array. Cosine similarity is a measure of similarity, often used to measure document similarity in text analysis. We use the below   formula to compute the cosine similarity.

  Similarity = (A.B) / (||A||.||B||) 
  where A and B are vectors:
  A.B is dot product of A and B: It is computed as sum of element-wise product of A and B.
  ||A|| is L2 norm of A: It is computed as square root of the sum of squares of elements of the vector A.

2. Download tmdb_5000 credits and movies dataset from kaggle.
3. Copy it to virtual environment and carry out execution to generate movie_list and similarity pickle files.
4. Create a python virtual environment , install streamlit and use the command "streamlit run frontencode.py" to open localhost.
5. Copy .pkl files to python virtual environment.
