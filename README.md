
git init
cat > README.md << 'EOF'
# Hi, I'm Nazia 👋

**CSE student @ ULAB** · Web programming labs & front-end practice

## 🚀 Projects
- [club-membership](https://github.com/contactnaziafarzana-code/Club-membership) – club member registration demo  
- [student-info-form](https://github.com/contactnaziafarzana-code/student-info-form) – accessible student form

## 💻 Tech
HTML • CSS • JavaScript • Git & GitHub

## 🌱 Currently
- Practicing accessible form design
- Cleaning, organizing repos

## 📫 Contact
- Email: contactnaziafarzana@gmail.com  

## 📊 Stats (optional)
![Top Langs](https://img.shields.io/badge/keep-learning-brightgreen)
EOF
git add README.md
git commit -m "feat: add profile README"
git branch -M main
git remote add origin https://github.com/contactnaziafarzana-code/contactnaziafarzana-code.git
git push -u origin main
