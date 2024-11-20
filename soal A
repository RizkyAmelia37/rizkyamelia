import numpy as np
import matplotlib.pyplot as plt

v = 20  # kecepatan konstan sebesar 20 m/s

# Definisi fungsi GLB x(t)
def x(t):
    return v*t

# mendefinisikan rentan data waktu (t)
t = np.arange(0, 300, 1)  # 5 menit = 300 detik

# menghitung nilai y untuk setiap nilai t
y = x(t)

# menghitung grafik
plt.plot(t, y, marker='o', color='b', linestyle='-', label="grafik GLB")

# menambahkan label, judul, dan grid
plt.xlabel("waktu(t)")
plt.ylabel("posisi(m)")
plt.title("Grafik GLB")
plt.legend()
plt.grid(True)
plt.show()
