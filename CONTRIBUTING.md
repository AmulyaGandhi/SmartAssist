
````
# Contributing to Smart Assist

We’re excited that you want to contribute to **Smart Assist** 🎉  
Follow these steps to get started:

---

## How to Contribute

1. **Fork the repository** on GitLab.  
2. **Clone your fork** to your local machine:
   ```bash
   git clone https://gitlab.com/<your-username>/smart-assist.git
   cd smart-assist
````

3. **Create a new branch** for your work:

   ```bash
   git checkout main
   git pull origin main
   git checkout -b feature/my-feature
   ```
4. **Make your changes** and test the app locally:

   ```bash
   streamlit run smart_assist_app.py
   ```
5. **Commit your changes** with clear messages:

   ```
   feat: add quiz shuffle option
   fix: handle API error gracefully
   docs: update usage instructions
   ```
6. **Push your branch** to GitLab:

   ```bash
   git push origin feature/my-feature
   ```
7. **Open a Merge Request (MR)** and describe your changes clearly.

---

## Types of Contributions Welcome

* 🐞 Fixing bugs
* ✨ Adding new features
* 🎨 Enhancing UI/UX with Streamlit
* 🧠 Improving quiz generation logic
* 📖 Updating or improving documentation

---

## Guidelines

* Follow **PEP8** coding style.
* Use descriptive function and variable names.
* Keep UI-related code inside `smart_assist_app.py`.
* Add comments for non-trivial logic.

---

💡 Your contributions make **Smart Assist** better for students and teachers everywhere!


