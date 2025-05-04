# ML
Tugas Machine Learning
Fuzzy C-Means Clustering
![image](https://github.com/user-attachments/assets/cc801767-551c-491e-85dc-a7ba2be419a8)

Evaluasi:
from sklearn.metrics import silhouette_score, davies_bouldin_score

# Misalnya: data_input = data yang dipakai untuk clustering
# labels = hasil np.argmax(u, axis=0)

silhouette = silhouette_score(data.T, cluster_membership)
davies = davies_bouldin_score(data.T, cluster_membership)

print(f"Silhouette Score: {silhouette:.3f}")
print(f"Davies-Bouldin Index: {davies:.3f}")

![image](https://github.com/user-attachments/assets/5d57126d-1eab-4537-ba87-60b7ba66ab09)
