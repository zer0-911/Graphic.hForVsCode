# Graphic.h For Vs Code
How to set up graphic.h in Visual Studio Code || Cara mensetting graphic.h di Visual Studio Code\

Download library and TDM-GCC in here\
https://drive.google.com/drive/folders/1avSe4Jh4Y7RkY0tFuqpp1AlI2ywoQ3BN?usp=sharing

# Installation
How to Install || Cara instalasi
1. Install TDM-GCC on gdrive, you can choose gcc version 32 or mix until it's finished || Install TDM-GCC yang ada di gdrive bisa pilih gcc yang versi 32 atau campuran sampai selesai.
2. Copy and paste 'graphics.h' and 'winbgim.h' into your tdm-gcc 32bit include folder (example: C:/TDM-GCC-32/include) || Salin dan tempel 'grafik.h' dan 'winbgim.h' ke dalam folder tdm-gcc 32bit include (contoh: C: / TDM-GCC-32 / include).
3. Create a .vscode file in your workspace or your folder and copy paste `c_cpp_properties.json`  || Buat file .vscode di workspace anda atau folder anda dan sopy paste `c_cpp_properties.json`
4. Don't forget to change a correct directories on `c_cpp_properties.json` depend on your tdm-gcc installation directories || Jangan lupa untuk mengubah direktori yang benar di `c_cpp_properties.json` tergantung pada direktori instalasi tdm-gcc anda.

# How to use
Compile and Linking your .cpp file with ||  Kompilasi dan tautkan file .cpp Anda dengan :     
  `g++ main.cpp -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32`

Above, change main.cpp according to the name of the file you created then save and compile / run by copying and pasting the above command with the file created into the terminal\
||
Diatas ini rubah main.cpp sesuai dengan nama file yang anda buat lalu simpan dan compile/run dengan cara copy dan paste perintah diatas dengan file yang dibuat ke terminal\


After running / compiling it, there will be a file called `a.exe` run outside of visual studio code if you don't have an extra extension to run the .exe format\
||
Setelah di run/compile maka akan ada file bernama `a.exe`jalankan diluar visual studio code jika anda tidak mempunyai ekstensi tambahan untuk menjalankan format .exe\

`a.exe`

Thankssss
