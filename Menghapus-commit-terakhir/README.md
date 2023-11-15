# Menghapus Commit Terakhir Sebelum di Push ke Github

**Hal ini dapat digunakan jika mengalami error saat melakukan push **

    git reset --hard HEAD~1  # Menghapus commit terakhir

**Push**

    git push origin branch_name

**Force Push**

    git push -f origin branch_name  # Force push setelah menghapus commit