🔹 1. WSL & Linux Environment
wsl --install
wsl --install ubuntu-24.04
wsl --version
sudo apt update && sudo apt upgrade -y


Practice Linux:

ls
pwd
cd ~
mkdir module01
cd module01
touch file.txt
cat file.txt
whoami

🔹 2. Linux File & Text Operations
echo "Hello Development Tools" > dev.txt
cat dev.txt
grep "Development" dev.txt
ls -l

🔹 3. Install Development Tools
sudo apt install git python3 python3-pip -y
git --version
python3 --version

🔹 4. Git Practice
mkdir git-practice
cd git-practice
git init
echo "Module 01 Practice" > readme.md
git add .
git commit -m "Initial Commit"

🔹 5. GitHub Connection
ssh-keygen -t rsa -b 4096 -C "your@email.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
cat ~/.ssh/id_rsa.pub


(Add key to GitHub)

Test:

ssh -T git@github.com

🔹 6. Python Practice

Create file:

nano app.py


Code:

print("Module 01 Development Environment Ready 🚀")


Run:

python3 app.py

🔹 7. Push to GitHub
git remote add origin <repo_url>
git branch -M main
git push -u origin main
