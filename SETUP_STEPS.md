# Data Manipulation Challenge – Setup in Cursor

Use this **exact path** for your project:
**`/Users/temiloluwaolubakinde/2026FEBCLASSWALKTHROUGH`**

Your existing venv is: **`.venv`** (inside that folder).

---

## Step 1: Open the project in Cursor

- **File → Open Folder** (or **File → Open…**)
- Choose: **`/Users/temiloluwaolubakinde/2026FEBCLASSWALKTHROUGH`**  
  (This opens the parent folder so both `starwars_mental_models` and `dataManipulationChallenge` are visible.)
- Or open only the challenge: **`/Users/temiloluwaolubakinde/2026FEBCLASSWALKTHROUGH/dataManipulationChallenge`**

---

## Step 2: Select the Python interpreter (use your existing venv)

1. Press **Cmd+Shift+P** (Mac) or **Ctrl+Shift+P** (Windows).
2. Type: **Python: Select Interpreter**
3. Press **Enter**.
4. In the list, choose the interpreter that shows:
   - **`./.venv/bin/python`** (Python 3.9.x), or
   - **`2026FEBCLASSWALKTHROUGH (.venv)`**
5. If you don’t see it, click **“Enter interpreter path…”** and paste:
   - **Mac/Linux:**  
     `/Users/temiloluwaolubakinde/2026FEBCLASSWALKTHROUGH/.venv/bin/python`
   - **Windows:**  
     `C:\...\2026FEBCLASSWALKTHROUGH\.venv\Scripts\python.exe` (adjust drive/path to match your machine).

Cursor will now use this venv for running code and Jupyter.

---

## Step 3: Activate the venv in the terminal

1. Open the terminal in Cursor: **Ctrl+`** (backtick) or **View → Terminal**.
2. Go to the folder that contains `.venv`:
   ```bash
   cd /Users/temiloluwaolubakinde/2026FEBCLASSWALKTHROUGH
   ```
   **Tip:** You can type `cd ` and then drag the **2026FEBCLASSWALKTHROUGH** folder from the file explorer into the terminal to paste the path.
3. Activate the venv:
   - **Mac/Linux:**
     ```bash
     source .venv/bin/activate
     ```
   - **Windows (Command Prompt):**
     ```bash
     .venv\Scripts\activate
     ```
   - **Windows (PowerShell):**
     ```bash
     .venv\Scripts\Activate.ps1
     ```
4. You should see **`(.venv)`** at the start of the terminal prompt.

---

## Step 4: Install packages (if needed)

With the venv still activated, run:

```bash
pip install pandas numpy matplotlib seaborn
```

Your venv already has `pandas` and `jupyter` from the Star Wars project; this adds anything the challenge needs.

---

## Step 5: Work on the challenge

- Open **`dataManipulationChallenge/index.qmd`** in Cursor.
- Use **Run Cell** / **Shift+Enter** to run code (Cursor will use the interpreter you selected in Step 2).
- To preview with Quarto, use an **activated** terminal (Step 3) and run:
  ```bash
  quarto preview index.qmd
  ```

Done. You’re using the same venv for both the Star Wars walkthrough and the Data Manipulation Challenge.
