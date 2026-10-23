# Creative Ideas for Everyday Objects

A beginner-friendly Google Colab project that asks the OpenAI API for one unusual, creative, and practical use for an everyday object.

## Repository structure

- `creative_ideas.ipynb` — the main Colab notebook. It installs the OpenAI SDK if needed, securely asks for an API key, prompts for an object, and prints one idea.
- `README.md` — project description and setup instructions.
- `.gitignore` — excludes common local secret files such as `.env` files from Git.
- `hello_colab.ipynb` — an additional introductory example notebook.

## Open and run from GitHub in Google Colab

1. Clone the repository to your computer:

   ```bash
   git clone https://github.com/OWNER/REPOSITORY.git
   cd REPOSITORY
   ```

   Replace `OWNER/REPOSITORY` with the GitHub account or organization and repository name. You can also open the project on GitHub without cloning first.
2. Go to [Google Colab](https://colab.research.google.com/) and select the **GitHub** tab in the notebook picker.
3. Paste the GitHub repository URL (or `OWNER/REPOSITORY`), find `creative_ideas.ipynb`, and open it. If you cloned the repository, you can instead upload the local notebook using **File → Upload notebook**.
4. Run the cells from top to bottom, or choose **Runtime → Run all**.
5. When prompted, enter your OpenAI API key and then an everyday object. The notebook prints one suggested use.

An OpenAI API key is required at runtime. The notebook asks for it with `getpass`, which hides the key as you type. Keep the key secret: never put it in notebook code, outputs, or files committed to Git; never push it to a GitHub repository; and do not share it. If you accidentally expose a key, revoke it and create a new one. Clear the Colab runtime when you finish, especially on a shared computer.
