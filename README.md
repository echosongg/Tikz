# <aiplans>: A TikZ-Based Library for Drawing POCL Plans

<aiplans> is a specialized LaTeX package designed to assist scientists, students, and professionals in creating high-quality graphical representations, particularly Partial Order Causal Link (POCL) plans. Built on the robust TikZ framework, this library simplifies the process of generating complex, precise diagrams that are essential for academic and scientific communication. Our package is especially useful in fields such as artificial intelligence and automated planned, where visualizing causal relationships and dependencies is fundamental.

## Content

- [Project Structure](#project-structure)
- [License](#license)
- [Future Improvements Plan](#future-improvements-plan)
- [Contact Information](#contact-information)
- [Team Members](#team-members)

## Project Structure

Aiplans/

├── **README.md**

├── **README.pdf**

├── **Aiplans-Introdution-source-code.zip**

├── **Aiplans-Introdution.pdf**

├── **tikzlibraryaiplans.code.tex**

└── **License.txt**


### Explanation

- **README**: This file provides an overview of the project, including installation instructions, system requirements, and other essential information.
- **Aiplans-Introdution-source-code.zip**: Introduction file Latex source code.
- **Aiplans-Introdution.pdf**: Detailed instructions on how to use the TikZ library included in this package. It covers the steps needed to generate diagrams using LaTeX.
- **tikzlibraryaiplans.code.tex**: The core of the project, this file contains the TikZ library specifically designed for generating AI plan diagrams. This package is crucial for the functionality provided by this project.
- **License.txt**: The license file outlines the terms under which the package can be used, modified, and distributed.


## License

This material is subject to the [LaTeX Project Public License 1.3c](https://ctan.org/license/lppl1.3).

## Future Improvements Plan

As we continue to improve and expand the `<aiplans>` package, the following developments are planned for the upcoming future:

### In Scope

1. **Extension Features for v1.0**:
   - **Vertical Diagram Support**: We aim to enhance the package by introducing the ability to create vertical diagrams, which will provide more flexibility in visualizing POCL plans.
   - **Dynamic Precondition/Effect Lengths**: After the package update, the lengths of the lines will be automatically adjusted based on the actual length of the text labels. In other words, if the label's text content is longer, the corresponding line will also be lengthened; if the label's text content is shorter, the line will be shortened accordingly. This dynamic adjustment allows the diagram to more flexibly adapt to various content requirements, resulting in a final diagram that is more visually appealing and clear.

2. **Code Translator**:
   - **PDDL/HDDL Code Translation**: We are developing a code translator that can accurately convert PDDL (Planning Domain Definition Language) and HDDL (Hierarchical Domain Definition Language) code into the schema format used by our `<aiplans>` library. This feature will streamline the process of diagram creation from existing codebases or at least allow to specify the tikz code in another syntax that might be more familiar to some.

## Contact Information

If you have any questions, feedback, or suggestions regarding this project, please feel free to reach out to us. We are always happy to assist and appreciate your input.

**Email:** [u7166251@anu.edu.au](mailto:u7166251@anu.edu.au) (Yikai Ge)  
For reporting bugs or requesting features.

We strive to respond to all inquiries as quickly as possible.

## Team Members

This project is developed by a team of students from the Australian National University (ANU), guided by our client. He provided us with the initial idea and relevant references, playing a crucial role in shaping the direction of our research.

### Client
- **Pascal Bercher**

### Maintainers
- **Yikai Ge**
- **Chen Wang**
- **Cheng Zhou**
- **Lujia Li**
- **Yinyin Chen**
- **Xinni Song**

We have worked closely with our client to ensure that the project meets their requirements and delivers high-quality results.
