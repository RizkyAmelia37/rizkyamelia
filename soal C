import numpy as np
import matplotlib.pyplot as plt

vo = 0   # kecepatan awal sebesar 0 m/s
a = 2    # percepatan konstan 2m/s**2

# Definisi fungsi GLBB x(t)
def x(t):
    return vo*t + 0.5*a*t**2

# mendefinisikan rentan data waktu (t)
t = np.arange(0, 100, 1)

# menghitung nilai y untuk setiap nilai t
y = x(t)

# menghitung grafik f(x) dan g(x)
plt.plot(t, y, marker='o', color='b', linestyle='-', label="grafik GLBB")

# menambahkan label, judul, dan grid
plt.xlabel("posisi(m)")
plt.ylabel("waktu(t)")
plt.title("Grafik GLBB")
plt.legend()
plt.grid(True)
plt.show()
