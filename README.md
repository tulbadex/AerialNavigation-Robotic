

# PythonRobotics
Python codes for robotics algorithm.

1. Install virtual environment

   ```terminal
   python -m venv env 
   ```

2. Activate virtual environment on window

   ```terminal
   env\Scripts\activate
   ```

3. Install the required libraries.

- using conda :

  ```terminal
  conda env create -f requirements/environment.yml
  ```
 
- using pip :

  ```terminal
  pip install -r requirements/requirements.txt
  ```


2. Execute python script in AeriaNavigation. such as
```terminal
python AerialNavigation/drone_3d_trajectory_following/drone_3d_trajectory_following.py
```