# workflow
Nama : Yuliana Dewi

NIM : E41200315

Repository ini ditujukan untuk memenuhi tugas dari matakuliah Literasi Digital

# Clone Reepository Workflow
Pertama saya membuat sebuah repository dengan nama Workflow pada github. Setelah itu, saya melakukan clonning repository menggunakan gitbash dengan perintah: ```git clone https://github.com/yulianadewi18/workflow.git``` Dilanjutkan dengan masuk pada direktori workflow dengan perintah: ```cd workflow```

Selanjutnya saya menambahkan sebuah file dengan nama minmax.html . Selanjutnya saya akan memindahkan file minmax.html yang berada pada working area menuju staging area dengan perintah: ```git add``` . untuk memindahkan lebih dari satu (semua) file. Setelah berhasil, commit file tersebut dengan perintah: ```git commit -m "Menambahkan file minmax.html"``` , Dilanjutkan dengan perintah: ```git push```

Kemudian saya menambahkan file baru dengan nama alerts.html, carausel.html dan card.html menggunakan perintah: ```git add .``` Setelah berhasil, commit file tersebut dengan perintah: ```git commit -m "Menambahkan file alerts, carausel dan card.html"``` , Dilanjutkan dengan perintah: ```git push```

Menambahkan sebuah folder js dengan perintah: ```git add js```. Setelah berhasil, commit folder dengan perintah: ```git commit -m "Menambahkan folder js"``` , Dilanjutkan dengan perintah: ```git push```

# Membuat branch dan melakukan merge
Saya akan menambahkan sebuah branch(cabang) dengan nama tampilan menggunakan perintah: ```git checkout -b tampilan``` .Kini head pada repo ini berpindah dari main menuju tampilan dan dapat dilihat pada tulisan berwarna biru disebelah kanan. Selanjutnya saya membuat sebuah folder yang bernama css pada branch tampilan. Lalu ketikkan perintah: ```git add``` . dilanjutkan dengan perintah: ```git commit -m "Menambahkan folder css"``` dilanjutkan dengan perintah: ```git push --set-upstream origin tampilan```

Menambahkan folder lagi yaitu img dengan perintah: ```git add img```, ```git commit -m "Menambahkan img"``` dilanjutkan ```git push```

Selanjutnya saya ingin menggabungkan folder css yang ada pada branch tampilan menuju branch main. Pertama berpindah terlebih dahulu ke branch main dengan perintah: ```git checkout main``` dilanjutkan dengan menggabungkan folder css dengan perintah: ```git merge tampilan``` ,dan ```git push``` maka penggabungan branch berhasil.

# Membuat release branch dan hotfix branch
Untuk membuat release branch cukup dengan perintah: ```git checkout -b release/v1.0.0``` dan dilanjutkan dengan perintah: ```git add .``` ,kemudian ```git commit -m "release v1.0.0"``` ,dan push dengan perintah: ```git push -u origin release/v1.0.0``` Untuk membuat hotfix branch sama dengan release branch yaitu menggunakan perintah: ```git checkout -b hotfix/nama```, ```git add .``` dan ```git commit -m "hotfix/nama"```, ```git push -u origin hotfix/nama```
