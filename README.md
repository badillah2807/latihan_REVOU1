# latihan_REVOU1
kalau ada masalah, masukkan kode ini
git init
git remote add https://github.com/badillah2807/latihan_REVOU1.git (untuk menghubungkan VS Code dengan github)
jika muncul tulisan dibawah ini:
*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

  masukkan kode ini:
  git config user.name "badillah"
  git config user.email"namatoken@github.com"
git add *
git commit -m "first commit"
git push -u origin main

…or create a new repository on the command line

echo "# testing-1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/badillah2807/testing-1.git
git push -u origin main

…or push an existing repository from the command line

git remote add origin https://github.com/badillah2807/testing-1.git
git branch -M main
git push -u origin main