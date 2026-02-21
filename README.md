# Oxford-AI-Engineering-Course

Code base for participants in the Oxford AI Engineering course, enabling both low-code and full-code tracks to clone, learn, extend and collaborate on different projects during and after the course.

## Repository structure

Each topic is in its own folder. You can work through them in order or jump to any topic—each folder is self-contained.

| Folder | Contents |
|--------|----------|
| **python_basics** | Variables, I/O, control flow, loops, functions, lists |
| **oop** | Classes, objects, inheritance, encapsulation |
| **ml_libraries** | Pandas, NumPy, Matplotlib, scikit-learn |
| **svm** | Support Vector Machines: classification and evaluation |
| **langchain** | LangChain, memory, tools, RAG, FastAPI + Streamlit (requires `.env` with `OPENAI_API_KEY`) |

**In every topic folder you’ll find:**

- **README.md** — How to run this topic (setup, run, deploy).
- **app.py** — Streamlit app (interactive UI for the topic).
- **tutorial_code.py** — Script version of the tutorial (run with `python`).
- **tutorial_code.ipynb** — Jupyter notebook version (where present).
- **requirements.txt** — Python dependencies for this topic.
- **setup_and_run.sh** / **setup_and_run.bat** — One-click setup and run (creates/uses `tutor_venv`, installs deps, launches the app).

A single virtual environment (`tutor_venv`) at the repo root is shared by all topics; the setup scripts create and use it automatically.
