Nama: Ihsan Nafis Hidayat
NIM : 23090082
Kelas : 2B
nama= input("Masukkan Nama Lengkap Anda: ")
jenis_kelamin = int(input("Masukkan Jenis Kelamin anda (1. Laki-laki/2. Perempuan): "))
tinggi_badan = int(input("Masukkan tinggi badan anda (cm): "))

if jenis_kelamin == 1 and tinggi_badan >= 170:
    print("Selamat",nama,"kamu Lolos Seleksi tinggi badan")
elif jenis_kelamin == 1 and tinggi_badan <= 170:
    print("Mohon maaf",nama,"kamu tidak memenuhi persyaratan tinggi badan")
elif jenis_kelamin == 2 and tinggi_badan >= 160:
    print("Selamat",nama,"kamu Lolos Seleksi tinggi badan")
elif jenis_kelamin == 2 and tinggi_badan <= 160:
    print("Mohon maaf",nama,"kamu tidak memenuhi persyaratan tinggi badan")
else:
    print("Mohon masukkan jenis kelamin dengan benar\n")
    print("Masukkan 1 untuk laki-laki dan 2 untuk perempuan")
