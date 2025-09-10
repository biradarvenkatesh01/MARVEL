# **TASK 1: 3D Printing**

**Objective:** To understand the working of a 3D printer, its components, about STL(Stereolithography) file and also about how we slice the and print the model from stl file .

---

### **Outcomes and Learnings:**

I learned the following things:

**1. The Working Principle (FDM):**
I learned that the most common type of 3D printing is Fused Deposition Modeling (FDM). In this type of printing plastic material is melted and put out through a nozzle, which moves along all three axes (X, Y, and Z axes) and this finally results in the formation of the 3d model.

**2. Key Components of an FDM Printer:**
* **Filament:** This is the raw material, typically a plastic thread. The most common filament for beginners is PLA (Polylactic Acid).
* **Extruder:** The "hot end" of the printer that pulls in the filament, melts it to a specific temperature (e.g., ~200°C for PLA), and pushes it out.
* **Nozzle:** The tip of the extruder where the molten plastic is deposited onto the printer bed.
* **Bed:** The platform where the object is printed. It is often heated (e.g., ~60°C for PLA) to ensure the first layer of the print sticks properly and prevents warping.

**3. The flow Foe 3d printing:**

* **STL (Stereolithography) Files:** An STL file is the standard 3D model format for 3D printing. It represents the surface geometry of a 3D object using a mesh of small triangles. It's essentially the blueprint of the object that will be printed.

* **Slicing and G-code:** A 3D printer cannot directly read an STL file. It requires a "slicer" software (like Ultimaker Cura or Creality Slicer) to convert the STL model into hundreds or thousands of thin horizontal layers. The slicer then generates a file with G-code, which contains the specific line-by-line instructions (like coordinates and extrusion commands) that the printer follows to build the object.

**4. Important Printer Settings:**
I learned about the key parameters that can be adjusted in the slicer software to control the quality, strength, and speed of the print:
* **Bed Temperature:** The temperature of the build plate, crucial for printing the first-layer .
* **Nozzle Temperature:** The temperature at which the filament is melted.
* **Infill Density:** The percentage of material used to fill the inside of the model. A lower infill (~10-20%) saves time and material, while a higher infill (100%) creates a solid, heavy, and strong object.
* **Layer Height:** The thickness of each layer. A smaller layer height (e.g., 0.12mm) results in a higher quality, more detailed surface but takes longer to print.
* **Supports:** Temporary structures that the slicer automatically generates to hold up overhanging parts of a model during printing. These are removed after the print is complete.

---
# **TASK 2: API**

**Objective:** To learn what an API is, how it works, and to build a user interface (a web app) that makes calls to an external API to fetch and display information.

---

### **Outcomes and Learnings:**

**1. Theoretical Understanding of APIs:**

I learned that an API (Application Programming Interface) acts as an intermediary or a messenger that allows two different software applications to communicate with each other.

A good analogy is a waiter in a restaurant. The customer (user) gives an order (request) to the waiter (API). The waiter takes this request to the kitchen (system), which processes it and prepares the food (response). The waiter then brings the food back to the customer. The customer doesn't need to know how the kitchen works; they only need to interact with the waiter.

Similarly, APIs provide a set of rules and tools that let one application use the services of another without needing to understand its internal complexity. A real-world example is how apps like Uber or Zomato use the Google Maps API to display maps within their own application.

**2. Practical Application: Pokedex Project**

I developed a simple Pokedex web application using the technologies listed below:

* **HTML:** For the basic structure of the webpage.
* **CSS:** For all the styling and user interface design.
* **JavaScript:** To handle user input, fetch data from the API, and dynamically update the webpage.

The project utilizes the free and public **PokeAPI** to fetch data about various Pokemon.

**How it works:**
* User enters the name of the pokemon and clicks on search.
* The JavaScript then sends a request to the PokeAPI with the entered name.
* If a matching Pokemon is found, the API sends back the data. The application then displays the Pokemon's name, image (sprite), and stats (HP, Attack, Defense, etc.) in a card format.
* If the Pokemon name is invalid or not found, an error message is displayed to the user.

---

### **Preview:**

![preview](https://github.com/biradarvenkatesh01/MARVEL/blob/main/Level%2000/pokedexpreview.png?raw=true)


* **GitHub Repository Link:** [https://github.com/biradarvenkatesh01/Simple_APIs_02](https://github.com/biradarvenkatesh01/Simple_APIs_02)

# **TASK 3: Working with GitHub**

**Objective:** To familiarize myself with GitHub integrated workflows such as forking, cloning, committing changes, and creating pull requests.

---

### **Outcomes and Learnings:**

1.  Forking the Repository
2.  Cloning and Making Changes 
3.  Committing and Pushing
4.  Creating a Pull Request

Through this task, I learend about the fork-and-pull workflow .

* **My Forked Repository:** [https://github.com/biradarvenkatesh01/git-task](https://github.com/biradarvenkatesh01/git-task)

**Changes made by me in main.py :**
![Code changes](https://github.com/biradarvenkatesh01/MARVEL/blob/main/Level%2000/codechange.png?raw=true)


**My pull request :**
![pullrequest](https://github.com/biradarvenkatesh01/MARVEL/blob/main/Level%2000/pullrequest.png?raw=true)

# **TASK 4: Command Line on Ubuntu**

**Objective:** To get familiar with the command line on Ubuntu by completing a series of subtasks involving file and directory manipulation.

---

### **Outcomes and Learnings:**

This task provided hands-on experience with the Ubuntu terminal. I learned how to use essential commands for navigating the file system and managing files and directories directly from the command line.

**Commands that I used:**

1.  **Creating a Directory:** I learned to use the `mkdir` command to create a new folder.
2.  **Changing Directory:** I used the `cd` command to navigate into the newly created folder.
3.  **Creating an Empty File:** I used the `touch` command to create a blank file without opening a text editor.
4.  **Listing Contents:** The `ls` command was used to list all the files and folders within the current directory.
5.  **Bulk Directory Creation:** I learned an efficient way to create a large number of numbered folders at once using brace expansion (`{}`).
6.  **Concatenating Files:** I used the `cat` command to combine the content of two separate text files and display the result directly in the terminal.

---
![Ubuntu Command Line Task](https://github.com/biradarvenkatesh01/MARVEL/blob/main/Level%2000/ss1.jpg?raw=true)

![Concatenation Screenshot](https://github.com/biradarvenkatesh01/MARVEL/blob/main/Level%2000/ss2.jpg?raw=true)

# **TASK 5: Build Your Own Brain - Linear Regression from Scratch**

**Objective:** To dive into the core of machine learning by implementing a Linear Regression model from scratch using Python. The performance of this custom-built model was then compared against the highly optimized implementation from the `scikit-learn` library, using the California Housing dataset for evaluation.

---

### **Outcomes and Learnings:**

This task provided a deep, foundational understanding of how machine learning models are built and trained. The process was divided into two main parts: building the model manually and then using a pre-existing library.

**1. Building Linear Regression from Scratch:**

The core of this part was to manually code a model based on the simple linear equation `y = mx + c`.

* **Data Preprocessing:** Before training, a crucial step was to prepare the data. The features in the California Housing dataset had different scales (e.g., square footage in thousands vs. number of rooms). To prevent the model from getting confused, I **normalized** the data, scaling all feature values to a common range between 0 and 1. This is essential for the proper functioning of Gradient Descent.

* **Gradient Descent:** This is used for finding out the values for `m-weight` and `c-bias` this works by starting with random values for `m` and `c` and iteratively adjusting them to minimize the model's error (the difference between predicted and actual house prices).

**2. Using Scikit-learn's Implementation:**

For the second part, I used the `LinearRegression` model from the `scikit-learn` library. we trained and plotted the pridiction graph.

**3. Comparison and Conclusion:**

Both the "scratch" model and the `scikit-learn` model were trained on the same dataset.

* **Performance Metrics:** To objectively compare them, I calculated three key metrics:
    * **MSE (Mean Squared Error):** Measures the average squared difference between the estimated values and the actual value. 
    * **MAE (Mean Absolute Error):** Measures the average absolute difference between the predicted and actual values.
    * **R² Score (Coefficient of Determination):** Indicates how much of the variance in the dependent variable (price) is predictable from the independent variables (features).
* **Conclusion:** While the "scratch" model performed reasonably well, the `scikit-learn` model was more accurate and significantly easier to implement.
---

* **Comparison Graph:** 
    ![Comparison Graph](https://github.com/biradarvenkatesh01/MARVEL/blob/main/Level%2000/task05.png?raw=true)

    * **GitHub Link:** [Linear_Regression_From_Scratch_.ipynb](https://github.com/biradarvenkatesh01/MARVEL/blob/main/Level%2000/Linear_Regression_From_Scratch_.ipynb)


     # **TASK 6: The Matrix Puzzle — Decode with NumPy & Reveal the Image**

**Objective:** To get hands-on with NumPy and Matplotlib by solving a visual puzzle. The mission was to decode a scrambled matrix from a `.npy` file and reveal a hidden image using various NumPy operations.

---

### **Outcomes and Learnings:**

This task was a fun and practical way to learn about the power of NumPy for matrix manipulation. By following the given clues, I successfully decoded the hidden image.

**The decoding process involved the following steps:**

1.  **Load the Data (`np.load`)**: First, I loaded the scrambled data from the given file into a NumPy array.

2.  **Reshape the Matrix (`.reshape`)**: Following the clue "Try reshaping the encoded array into a square," I calculated the side length and reshaped the 1D array into a 2D square matrix.

3.  **Transpose the Matrix (`.T`)**: The next clue, "The structure may be upright, but the data might be sideways," suggested changing the orientation. I used the transpose (`.T`) operation to swap the rows and columns of the matrix.

4.  **Flip the Matrix (`np.flipud`)**: The final clue, "Sometimes the end is actually the beginning," led me to flip the matrix vertically. I used the `np.flipud()` (flip up-down) function, which reversed the order of rows, bringing the bottom rows to the top.

5.  **Visualize the Image (`plt.imshow`)**: Once the matrix was correctly decoded, I used Matplotlib's `plt.imshow()` function to render the array as an image, revealing the hidden picture.

This task provided a solid understanding of how to manipulate multi-dimensional arrays in NumPy and visualize them using Matplotlib.

---

* **The Decoded Image:**
    ![Decoded Image](https://github.com/biradarvenkatesh01/MARVEL/blob/main/task06.png?raw=true)

* **Code Link:**
    [Link to my Code](https://github.com/biradarvenkatesh01/MARVEL/blob/main/Level%2000/Matrix%20Puzzle.ipynb)

    # **TASK 7: Create a Portfolio Webpage**

**Objective:** To create a responsive personal portfolio website to showcase my skills, projects, and interests. The project had to be hosted and the source code pushed to a GitHub repository.

---

### **Outcomes and Learnings:**

I built a simple portfolio webpage using just html , css, and js , no specific frameworks were used for it . the webpage is pretty simple and responsive . it displays about my projects.

---

![Portfolio Webpage Screenshot](https://your-screenshot-url.png)
![Portfolio Webpage Screenshot](https://your-screenshot-url.png)

* **GitHub Repository Link:**
    [https://github.com/your-username/your-repo](https://github.com/your-username/your-repo)