<h1 align="center">Chào bạn, mình là Tiến Minh! 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=24A1FF&center=true&vCenter=true&width=600&lines=AI+Engineer;Computer+Vision;NLP+%26+RAG+Systems;Machine+Learning" alt="Typing SVG" />
</p>

---

### 🚀 Giới thiệu bản thân
Mình là **Tiến Minh**, sinh viên năm 3 chuyên ngành **Công nghệ thông tin** tại **Đại học Thủy Lợi**. Định hướng của mình là trở thành một **Kỹ sư AI (AI Engineer)**, với niềm đam mê mãnh liệt trong việc nghiên cứu và phát triển các hệ thống truy xuất thông tin (Information Retrieval), Deep Metric Learning, và Computer Vision.

* 🔭 **Đang tập trung:** Tối ưu hóa các pipeline RAG (Hybrid Search, Cross-Encoder) và nghiên cứu các kiến trúc mô hình thị giác máy tính chuyên sâu.
* 🌱 **Mục tiêu:** Ứng tuyển vị trí **AI Engineer** để có cơ hội giải quyết các bài toán thực tế, xây dựng luồng dữ liệu (data pipelines) tối ưu và đưa mô hình AI triển khai lên môi trường production.
* 💬 **Hỏi mình về:** PyTorch, RAG Systems, Vector Databases, Deep Learning architectures.
* ⚡ **Sở thích:** Đá bóng ngoài trời và giải quyết các bài toán tối ưu thuật toán.

---

### 🛠 Kỹ năng & Công cụ

#### 🧠 AI / Machine Learning / Data Science
<p align="left">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
</p>

#### 💻 Backend & Vector Databases
<p align="left">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Qdrant-FF9800?style=for-the-badge&logo=qdrant&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" />
</p>

#### 🌐 Ngôn ngữ lập trình & DevOps
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>

---

### 💡 Dự án Tiêu biểu

#### 📚 Academic Regulations RAG Chatbot (M_chatbot)
* **Công nghệ:** FastAPI, Qdrant, Supabase, PostgreSQL, Cross-Encoder, LLMs.
* **Mô tả:** Hệ thống Question-Answering truy xuất quy chế đào tạo đại học, tích hợp khả năng tự động lọc ngữ cảnh theo năm học.
* **Điểm nhấn kỹ thuật:** 
  * Áp dụng **Hybrid Retrieval** (Vector Search + BM25) kết hợp thuật toán Reciprocal Rank Fusion và **Cross-Encoder reranker** nhằm tối đa hóa độ chính xác truy xuất.
  * Thiết kế luồng đồng bộ hóa dữ liệu tự động giữa Supabase và **Qdrant** vector database.
  * Hỗ trợ real-time streaming (SSE) và tối ưu quản lý lịch sử hội thoại với `asyncpg` trên PostgreSQL.

#### 👁️ Content-Based Image Retrieval with Deep Metric Learning
* **Công nghệ:** PyTorch, ResNet50, Graphormer, Deep Metric Learning.
* **Mô tả:** Nghiên cứu và đề xuất kiến trúc lai "ResNet-GT" nhằm giải quyết vấn đề khoảng cách ngữ nghĩa (semantic gap) trong phân loại ảnh mịn (Fine-grained Image Classification).
* **Điểm nhấn kỹ thuật:**
  * Nhúng khoảng cách đường đi ngắn nhất trên đồ thị K-NN vào cơ chế Multi-Head Self-Attention.
  * Đạt hiệu năng **Zero-shot retrieval** cực cao (Recall@1 = 84.22%) trên tập dữ liệu CUB 200-2011, vượt trội hoàn toàn so với các mô hình ViT tiêu chuẩn.

#### 👤 Facial Expression Recognition Web Application
* **Công nghệ:** Python, Scikit-learn, OpenCV, Streamlit.
* **Mô tả:** Xây dựng pipeline phân loại cảm xúc khuôn mặt end-to-end, triển khai dưới dạng Web App tương tác.
* **Điểm nhấn kỹ thuật:** 
  * Tự triển khai thuật toán trích xuất đặc trưng **HOG (Histogram of Oriented Gradients)** kết hợp với các mô hình Machine Learning truyền thống (Random Forest, KNN). 
  * Tối ưu hóa siêu tham số (Hyperparameter Tuning) bằng GridSearchCV; ứng dụng nhận diện và crop khuôn mặt real-time qua webcam.

#### 📈 Financial Data Mining & Time-Series Prediction
* **Công nghệ:** Python, Pandas, Scikit-learn (Linear Regression).
* **Mô tả:** Phát triển công cụ cào dữ liệu tài chính tự động và dự báo xu hướng giá vàng lịch sử.
* **Điểm nhấn kỹ thuật:** 
  * Áp dụng kỹ thuật Feature Engineering chuyên sâu (rolling averages, lag indicators).
  * Ứng dụng các thuật toán hồi quy tuyến tính để phân tích và dự báo biến động giá.

---

### 📊 Thống kê GitHub
<p align="center">
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=minhlt6&layout=compact&theme=transparent&hide_border=true&title_color=24A1FF&text_color=a6a6a6" alt="Top Languages" width="48%" />
  <img src="https://github-stats-extended.vercel.app/api?username=minhlt6&show_icons=true&theme=transparent&hide_border=true&title_color=24A1FF&text_color=a6a6a6&icon_color=24A1FF&hide_rank=true" alt="GitHub Stats" width="48%" />
</p>
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=minhlt6&theme=transparent&hide_border=true&color=24A1FF&line=24A1FF&point=ffffff" alt="Activity Graph" width="100%" />
</p>

---

### 📫 Kết nối với mình
<p align="left">
  <a href="mailto:mle409640@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/l%C3%AA-ti%E1%BA%BFn-minh-2aaa8a416/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>

<p align="center"><i>"Code is like humor. When you have to explain it, it’s bad."</i></p>
