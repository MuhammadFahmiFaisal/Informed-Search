# Praktikum Algoritma Pencarian (Search Algorithms)

## 📌 Deskripsi
Repository ini berisi implementasi berbagai algoritma pencarian dalam **Python**, yaitu **Informed Search** yang terdiri dari **Greedy Best First Search**, **A* Search**, dan **A* Tree Graph Search**. Setiap algoritma digunakan untuk mencari jalur optimal dalam graf berbobot berdasarkan karakteristik heuristik dan biaya jalur.

## 📚 Penjelasan Algoritma

### 1️⃣ Greedy Best First Search (Greedy Search)
Greedy Search adalah algoritma pencarian yang hanya mempertimbangkan nilai heuristik untuk memilih simpul berikutnya. Algoritma ini memilih jalur yang tampaknya paling menjanjikan tanpa mempertimbangkan biaya dari simpul awal. Meskipun cepat, algoritma ini tidak menjamin solusi optimal karena bisa terjebak dalam jalur lokal terbaik.

### 2️⃣ A* Search 
A* Search adalah algoritma pencarian yang menggunakan kombinasi biaya jalur (g(n)) dan heuristik (h(n)) untuk menemukan jalur terpendek yang optimal. Algoritma ini menggunakan fungsi evaluasi f(n) = g(n) + h(n) untuk memastikan bahwa jalur yang dipilih tidak hanya menjanjikan secara heuristik, tetapi juga mempertimbangkan biaya sesungguhnya dari simpul awal.

### 3️⃣ A* Tree Graph Search
A* Tree Graph Search adalah varian dari A* yang menangani eksplorasi graf dengan lebih efisien. Algoritma ini mencegah eksplorasi ulang simpul yang telah dikunjungi dengan menggunakan struktur data seperti hash table atau set untuk menyimpan simpul yang sudah diproses. Dengan pendekatan ini, A* Tree Graph Search lebih optimal dalam mencari jalur terpendek dibandingkan A* Search standar.

## 📂 File dalam Repository
- `greedy_search.py` → Implementasi Greedy Best First Search
- `astar_search.py` → Implementasi A* Search
- `astar_tree_graph.py` → Implementasi A* Tree Graph Search

## 🚀 Cara Menjalankan Kode di Google Colab
1. **Clone repository ini ke Google Colab atau komputer lokal
2. **Jalankan kode dalam Google Colab dengan langkah berikut**:
   - Upload file Python ke Google Colab.
   - Tambahkan sel kode berikut untuk menjalankan algoritma:
     
     !python greedy_search.py  # Untuk menjalankan Greedy Best First Search
     !python astar_search.py   # Untuk menjalankan A* Search
     !python astar_tree_graph.py  # Untuk menjalankan A* Tree Graph Search
  
3. **Pastikan semua dependensi telah terinstal**
4. **Jalankan dan analisis hasilnya!**

