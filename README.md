# No.3
print("Program penghitung rumus E=mc^2")
e = float(input("Energi Joule")
m = float(input("Masukkan massa gram"))
c = float(input("Kecepatan cahaya dalam ruang hampa"))
e = m*c**22
print("Penghitung rumus adalah" , e)

# No.4
# Membuat Program konversi suhu, dari Celcius, Reamur,dan Farenheit.
  # F = 9/5 * C + 32
  # R = 4/5 * C

# FARENHEIT
C = float(input("Masukkan Celcius "))
F = 9/5 * C + 32
print("Maka nilai Farenheitnya adalah ", F)

# REAMUR
R = 4/5 * C 
print("Maka nilai   Reamurnya  adalah ", R)


# No.5
# Membuat Program konversi detik ke hari, jam, menit, detik!
  # - Rumus : 1 hari = 86400 detik; 1 jam = 3600 detik dan 1 menit = 60 detik.

# MENGINPUT TOTAL DETIK
totdetik  = int(input("Masukkan Detik "))

# MELAKUKAN KONVERSI
hari      = totdetik //86400
sisadetik = totdetik - 86400*hari
jam       = sisadetik//3600
menit     = sisadetik//60
detik     = sisadetik//1

# HASIL KONVERSI
print ("%d hari %d jam %d menit %d detik "%(hari,jam,menit,detik))
