# Визначення текстових файлів з правильними закінченнями рядків
*.html text eol=lf
*.css text eol=lf
*.js text eol=lf

# Обробка зображень як бінарних файлів
*.png binary
*.jpg binary
*.jpeg binary
*.gif binary
*.svg binary

# Автоматичне визначення текстових файлів
* text=auto
git add .
git commit -m "Deploy to GitHub Pages"
git push origin main
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/Sviat20101/WebStudio.git
git push -u origin main
