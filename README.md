# Stack Overflow survey breakdown

This repository presents the Jupyter notebook behind this blog post: https://pimvschayik-69902.medium.com/quick-insight-on-stack-overflow-data-7c89f5644a67. This post is based on survey data from Stack Overflow: https://insights.stackoverflow.com/survey.

# Development

## Requirements:
- Python3

## Getting started
1. Clone project from GitHub: `git clone https://github.com/Schayik/u-data-science-blog-post.git`
2. Download data: https://drive.google.com/file/d/1dfGerWeWkcyQ9GX9x20rdSGj7WtEpzBB/view
3. Unzip file and add folder to workspace
4. Create virtual environment: `python -m venv .venv`
5. Activate virtual environment: `.venv/Scripts/activate`
6. Install dependencies: `pip install notebook pandas matplotlib sklearn`
7. Open Jupyter Notebook: `jupyter notebook`
8. A page in your browser will open: http://localhost:8888/tree
9. Open **data-review.ipynb**

**Note**: I had some troubles with the notebook kernel showing this error: *FileNotFoundError: [WinError 2] The system cannot find the file specified*. I managed to fix it using `python -m ipykernel install --user` from this issue post answer: https://github.com/jupyter/notebook/issues/4079#issuecomment-429651480

## Next time setup
1. Activate virtual environment: `.venv/Scripts/activate`
2. Open Jupyter Notebook: `jupyter notebook`
