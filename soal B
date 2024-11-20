import numpy as np
import matplotlib.pyplot as plt

vo = 0    # kecepatan awal sebesar 0 m/s
a = 9.8   # percepatan gravitasi 9.8 m/s**2

# Definisi fungsi GLBB x(t)
def x(t):
    return vo*t + 0.5*a*t**2

# mendefinisikan rentan data waktu (t)
t = np.arange(0, 120, 1)  # waktu 2 menit = 120 detik

# menghitung nilai y untuk setiap nilai t
y = x(t)

# menghitung gerafik f(x) dan g(x)
plt.plot(t, y, marker='o', color='b', linestyle='-', label="gerafik GLBB")

# menambahkan label, judul, dan grid
plt.xlabel("posisi(m)")
plt.ylabel("waktu(t)")
plt.title("Gerafik GLBB")
plt.legend()
plt.grid(True)
plt.show()
