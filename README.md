## course.fast.ai

This is where you'll find the notebooks, slides, and spreadsheets for the 2022 edition of Practical Deep Learning for Coders. See [course.fast.ai](https://course.fast.ai) for the lessons.

## What's here

- Repo root: notebooks
- `clean` folder: notebooks without prose or outputs
- `xl`: Excel spreadsheets
- `slides`: Jeremy's slide decks
- `tools`: Ignore (tools for creating this repo)
- `getting-started-with-codespaces`: A document to help run the notebooks in a GitHub Codespace


## Getting started
1. Create, activate environment:
```cd .devcontainer/venv/```
```python3 -m venv pdlc```
```source venv/pdlc/bin/activate```

2. Install dependencies
```cd ..r```
```cat requirements.txt | xargs -n 1 -P 5 pip install```

3. install ipykernel and link it to venv:
```python -m ipykernel install --user --name=pdlc```