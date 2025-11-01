## Flask Learning

1) how to create a virtual environment
   - `py -m venv env`
   - `source env/bin/activate` (Linux/Mac)
   - `env\Scripts\activate` (Windows)

2) what is virtual environment
   - A virtual environment is an isolated Python environment that allows you to manage dependencies for different projects separately.

3) why do we need virtual environment
   - To avoid conflicts between dependencies of different projects and to maintain a clean workspace.
   - eg: Project A requires Flask 1.1.2 while Project B requires Flask 2.0.1. Using virtual environments allows both projects to coexist without dependency issues.
