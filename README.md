# hello-world

class Mhs:
    '"Dasar kelas Mahasiswa"'
    jumlah_mhs = 0

    def __init__(self, nama, nim, program_studi, alamat, tgl_lahir):
        self.nama = nama
        self.nim = nim
        self.program_studi = program_studi
        self.alamat = alamat
        self.tgl_lahir = tgl_lahir
        Mhs.jumlah_mhs += 1

    def jumlah(self):
        print("Total Mahasiswa: ", Mhs.jumlah_mhs)

    def tampilkan_mhs(self):
        print("Nama: ", self.nama)
        print("Umur: ", self.nim)
        print("Program Studi: ", self.program_studi)
        print("Alamat: ", self.alamat)
        print("Tanggal Lahir: ", self.tgl_lahir)

mhs1 = Mhs("Nabila Shafia Indira", "M0119062", "Matematika", "Banjarnegara", "05 Januari 2002")
mhs2 = Mhs("Melinda Dinar Puji Anggraini", "M0119058", "Matematika", "Kudus", "12 Mei 2001")
mhs3 = Mhs("Nabila Nurul Aziza", "M0119061", "Matematika", "Ponorogo", "01 Januari 2000")
mhs4 = Mhs("Rifka Annisa Nurfitri", "M0119070", "Matematika", "Boyolali", "30 September 2001")
mhs5 = Mhs("Vania Atalie Pratista", "M0119092", "Matematika", "Purbalingga", "24 Desember 2000")

mhs1.tampilkan_mhs()
mhs2.tampilkan_mhs()
mhs3.tampilkan_mhs()
mhs4.tampilkan_mhs()
mhs5.tampilkan_mhs()
print("Total Mahasiswa: ", Mhs.jumlah_mhs)
