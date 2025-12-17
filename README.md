# EmoReq UML Profile

This repository contains the files related to my Master’s thesis project:

My thesis is titled:

> **An Approach for Modeling and Analyzing Emotional Requirements**

The thesis was completed as part of the **Master’s programme in Software Engineering at the University of Tartu**.  
The main goal of the thesis is to support software designers in **capturing and analyzing emotional requirements** (e.g., how users should feel when interacting with a system) alongside traditional requirements such as **functional requirements** and **quality requirements**.

---
## 📌 Project Overview

Software systems are traditionally designed and analyzed using functional and quality requirements. However, **emotional requirements**, such as users’ feelings, motivations, and emotional expectations are often not explicitly modeled, even though they strongly influence user experience and system acceptance.

This thesis addresses this gap by proposing **EmoReq**, a **UML Profile** that enables designers to model emotional requirements in a structured and systematic way. The profile extends UML with dedicated stereotypes and relationships for representing emotional concepts and their connections to other system elements.

In addition, the project defines **OCL constraints** that allow automated validation of models, helping designers detect modeling errors and inconsistencies early in the design process. The approach is implemented and demonstrated using **Eclipse Papyrus** through an example scenario, showing how emotional requirements can be integrated into standard UML-based system models.

---
## 📁 Repository Structure

This repository is organized as an **Eclipse Papyrus project** and contains the following files:

### 🔹 UML Profile Files
- **`EmoReq_profile.profile.uml`**  
  Defines the **EmoReq UML Profile**, including stereotypes, tagged values, relationships, and OCL constraints used to model and validate emotional requirements.

- **`EmoReq_profile.profile.notation`**  
  Stores diagram layout and visual information for the EmoReq profile (how diagrams are displayed in Papyrus).

- **`EmoReq_profile.profile.di`**  
  The Papyrus **diagram interchange file** that links the profile model with its diagrams. This is the main entry file for opening the profile in Papyrus.

### 🔹 Example Model Files
- **`model.uml`**  
  An example UML model based on an **Online Learning Platform** scenario, demonstrating how the EmoReq profile can be applied in a practical context.

- **`model.notation`**  
  Contains the visual layout and diagram information for the Online Learning Platform example model.

- **`model.di`**  
  The Papyrus diagram interchange file for the Online Learning Platform example. This file should be opened to view and edit the example diagrams in Papyrus.

### 🔹 Eclipse Project File
- **`.project`**  
  Eclipse project configuration file required to import and recognize the project correctly within the Eclipse workspace.

---
## 🚀 How to Use the EmoReq UML Profile (Step-by-Step)

### 1️⃣ Download the repository to your local machine

You can obtain the project in one of the following ways:

#### Option A: Clone using Git

git clone https://github.com/EldanizAkbar/EmorReq-UML-Profile.git

#### Option B: Download as ZIP

Download the repository as a ZIP file from GitHub and extract it to a local directory.

### 2️⃣ Install the required tools
Make sure you have:
- **Java (JDK 11 or later recommended)**
- **Eclipse IDE**
- **Eclipse Papyrus** (UML + OCL support)

### 3️⃣ Import the project into Eclipse

1. Open **Eclipse**
2. Go to **File → Open File…**
3. Navigate to the project folder
4. Select **`EmoReq_profile.profile.di`**
5. Click **Open**

The EmoReq UML Profile will open in Papyrus.  
Here you can view the **defined stereotypes**, **relationships**, and the **OCL constraints** used for model validation.

### 4️⃣ Open the Online Learning Platform example model

1. In **Eclipse**, go to **File → Open File…**
2. Navigate to the project folder
3. Select **`model.di`**
4. Click **Open**

The example model based on an **Online Learning Platform** scenario will open in Papyrus.

Before running validation, make sure the model is based on the **EmoReq UML Profile**:
1. Click on an empty area of the model
2. Open the **Properties** view
3. Go to the **Profile** section
4. Verify that **`EmoReq_profile`** is listed, including its **location** and **version**

To validate the example model using the profile:
1. Right-click anywhere inside the opened model
2. Select **Validate**
3. Choose **Validate Model**

The validation results will be displayed in the **Model Validation** view.

### 5️⃣ Apply the EmoReq UML Profile to your own model

To create your own model using the EmoReq UML Profile, follow these steps:

#### Create a new Papyrus model
1. In **Eclipse**, go to **File → New → Papyrus Model**
2. Select **UML** and click **Next**
3. Choose a project where **EmoReq_profile** is located
4. Give your model a name
5. Click **Finish**

#### Create model elements
1. In the **Palette** view, go to **Nodes**
2. Select **Class**
3. Click in the diagram to create a new element
4. Assign a name to the element

To apply an EmoReq stereotype:
1. Select the created element
2. Open the **Properties** view
3. Go to the **Profile** section
4. Click **+ (Add)** and select the appropriate EmoReq stereotype
5. Fill in the tagged values if required

#### Create relationships between elements
1. In the **Palette**, go to **Edges**
2. Select **Dependency**
3. Draw the dependency from one model element to another

To apply a stereotype to the relationship:
1. Select the created dependency
2. Open the **Properties** view
3. Go to the **Profile** section
4. Click **+ (Add)** and select the appropriate relationship stereotype

Repeat these steps for other elements and relationships as needed.

#### Validate your model
After completing your model:
1. Right-click anywhere in the diagram or on the model in *Project Explorer*
2. Select **Validate**
3. Choose **Validate Model**

The validation results will be shown in the **Model Validation** view.

---
## 🔍 Scope and Limitations

This project focuses on **conceptual modeling and validation** of emotional requirements using UML and OCL.  
It does **not** include software implementation, runtime analysis, or empirical user studies.

The EmoReq UML Profile is intended to support **early design and requirements analysis**, not system execution or simulation.

## 👥 Intended Audience

This project is intended for:
- Researchers and students in **Requirements Engineering**
- UML and **model-driven engineering** practitioners
- Designers interested in **emotional and user-centered requirements**
- Users working with **Eclipse Papyrus and OCL**

## ⚠️ Notes and Known Issues

- Always open models using the **`.di`** file, not the `.uml` file
- Ensure the **EmoReq_profile** is applied before validation
- Validation results depend on Papyrus OCL configuration
- Diagram layout may vary depending on Eclipse/Papyrus version

## 👤 Author

**Eldaniz Akbarzade**  
Master’s Student – Software Engineering  
University of Tartu

## 📄 License

This repository contains materials related to my Master’s thesis:

> *An Approach for Modeling and Analyzing Emotional Requirements*

The thesis and its associated artifacts are made publicly available under the  
**Creative Commons Attribution–NonCommercial–NoDerivatives 4.0 International (CC BY-NC-ND 4.0)** license.

This means:
- The work may be **shared and redistributed** for **non-commercial and academic purposes**
- **No derivative works** or modifications are permitted
- **Commercial use is not allowed**

The author retains full copyright.  
A non-exclusive licence has been granted to the **University of Tartu** to reproduce and make the thesis publicly available through its digital archives, in accordance with university regulations.


  
