#RansomX adalah ransomware open source yang dibuat dengan Python, dirancang untuk menemukan dan mengenkripsi data pengguna. Alih-alih server nyata, kunci enkripsi akan dikirim melalui email ke kotak surat Anda.


#Program Structure :

Program ini diatur dalam tiga bagian utama: Temukan File: temukan file dengan ekstensi dan simpan jalur ke path.txt Enkripsi File: mengenkripsi file di path.txt, menghasilkan digit id, mengirim kunci dan id Dekripsi: minta uang, tunggu kuncinya, dan dekripsi file jika kuncinya benar


#How to run :

You need to have python3 installed and configured

Download the repository via git or zip
Install requirements: pip install -r requirements.txt
Before running it, you need to modify a few thing:

Add your email information: enter image description here

I recommend running it in a testing directory, otherwise all of your file will be encrypted: enter image description here

Run it: python RansomX.py


#Testing :

This Program have been test on:

Windows 10
Mac OS Catalina 10.15.6 (19G73)
