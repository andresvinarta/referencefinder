# Reference Finder

This tool allows you to easily find references to GameObjects and their components within a scene in your Unity project.

## Features
- Find GameObjects that are referenced by other objects in the scene.
- Easily navigate to referenced GameObjects from the tool.

## How to use
1. **Install the Package**:
   - Add the Reference Finder package to your project by using the Package Manager and adding via the GitHub repository URL.

2. **Access the Tool**:
   - Open your Unity project with the package installed.
   - Navigate to the **GameObject** menu at the top of the Unity editor.
   - Under the **GameObject** menu, you will find the option **Find GameObject References**.
   - Click on **Find GameObject References** to open the tool window and start finding references to your GameObjects.

3. **The information is formatted as follows**:
    - GameObject with references' name 1
        - Component's name 1 -> Field's name (Type of field)
 
    - GameObject with references' name 2
        - Component's name 1 -> Field's name (Type of field)
        - Component's name 2 -> Field's name (Type of field)

If no references have been found, it will say so.
