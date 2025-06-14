#project python pertama 
nama_project ="WELCOME TEBAK GAMBAR GAME"

posisi_gambar = 3

print("===============================")
print(f"==={nama_project}===")
print("===============================")

nama_user = str(input("masukan nama kamu: "))
print(f'''WELCOME {nama_user} coba kamu perhatikan 
gambar dibawah ini
''')

print("'_',°-_-°,:)")

jawaban_user = int(input('''manakah gambar tersenyum di nomer 
[1,2,3]:? 
'''))

if posisi_gambar == 3:
   print("selamat jawaban kamu benar👍")
else:
   print("maaf jawaban kamu kurang tepat")
