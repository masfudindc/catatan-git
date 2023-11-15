# Mengatasi masalah push file berukuran besar dengan Git Large File Storage (Git LFS)

## Langkah 1: instalasi Git LFS

    Mengunduh Git LFS dari https://git-lfs.github.com/ dan mengikuti petunjuk instalasinya

## Langkah 2: inisialisasi Git LFS di Repositori

    git lfs install


## Langkah 3: menandai jenis file
**Menandai jika file besar bertipe zip**

    git lfs track "*.zip"

## Langkah 4:  tambahkan dan commit perubahan
    git add .
    git commit -m "Menggunakan Git LFS untuk file besar"

## Langkah 5: lakukan push

**Push**

    git push origin branch_name

**Force push**

    git push -f origin main