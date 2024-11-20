import numpy as np
import matplotlib.pyplot as plt

vo = 60  # kecepatan awal sebesar 60 m/s
a = -2.25  # perlambatan konstan -2.25 m/s**2

# Definisi fungsi GLBB x(t)
def x(t):
    return vo*t + 0.5*a*t**2

# mendefinisikan rentan data waktu (t)
t = np.arange(0, 22, 1)

# menghitung nilai y untuk setiap nilai t
y = x(t)

# menghitung gerafik f(x) dan g(x)
plt.plot(t, y, marker='o', color='b', linestyle='-', label="gerafik GLBB")

# menambahkan label, judul, dan grid
plt.xlabel("waktu(t)")
plt.ylabel("posisi(m)")
plt.title("Gerafik GLBB")
plt.legend()
plt.grid(True)
plt.show()
