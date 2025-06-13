# Node.js File Manager 📁

A simple file management tool created using **Node.js core modules** (`fs`, `path`, `http`) for the **Celebal Summer Internship 2025**.

## 💡 Features

- 📄 Create a file with content
- 🔍 Read content from a file
- ❌ Delete a file

## 📂 Folder Structure

file-manager/
├── index.js # Main server code with file logic
├── package.json # Project metadata and scripts
└── README.md # Project overview and usage


## ▶️ How to Run

1. Make sure Node.js is installed.
2. Run the project:

npm start
3.Open browser or Postman:

Create file:

http://localhost:3000/create?name=test.txt&content=HelloNode
Read file:

http://localhost:3000/read?name=test.txt
Delete file:

http://localhost:3000/delete?name=test.txt

## Files
Files are stored in the files/ folder created automatically.

This project uses only built-in Node.js modules, no external libraries.

---

## ✅ Next Step: GitHub Upload (Optional but Recommended)

1. Go to [https://github.com/new](https://github.com/new)
2. Create a repo named `node-file-manager` 
3. Then run these commands in your project folder:

```bash
git init
git add .
git commit -m "Node.js File Manager"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main