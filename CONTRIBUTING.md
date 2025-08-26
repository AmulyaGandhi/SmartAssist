How to Contribute to Smart Assist

Fork the repository on GitLab.

Clone your fork to your local machine:

git clone https://gitlab.com/<your-username>/smart-assist.git
cd smart-assist


Create a new branch for your work:

git checkout main
git pull origin main
git checkout -b feature/my-feature


Make your changes and test the app locally:

streamlit run smart_assist_app.py


Commit your changes with clear messages:

feat: add quiz shuffle option
fix: handle API error gracefully
docs: update usage instructions


Push your branch to GitLab:

git push origin feature/my-feature


Open a Merge Request (MR) and describe your changes clearly.

✅ Contributions can include:

Fixing bugs

Adding new features

Improving the quiz generation

Enhancing UI/UX with Streamlit

Updating or improving documentation.