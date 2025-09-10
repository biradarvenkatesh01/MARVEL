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
![pullrequest](https://github.com/biradarvenkatesh01/MARVEL/blob/main/Level%2000/codechange.png?raw=true)