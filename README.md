# NM-DOc-Genie-Project

Doc-Genie
Professional Python Function Docstring Generator with AST Analysis


📌 Overview

Doc-Genie is an intelligent Python documentation tool that automatically generates professional docstrings using Abstract Syntax Tree (AST) analysis.

Instead of writing documentation manually, developers can paste their Python functions into the system and instantly receive structured, industry-standard docstrings.

The platform analyzes function signatures, parameters, return types, and internal logic to produce accurate and meaningful documentation. It supports multiple documentation styles and provides export options for production use.


🎯 Key Features

AST-Based Code Analysis Uses Python’s AST module to deeply analyze function structure and behavior.

Automatic Docstring Generation Generates clear and structured docstrings for Python functions.

Multiple Documentation Styles

Google Style

NumPy Style

Intelligent Logic Detection Understands loops, conditionals, return statements, and core logic patterns.

Professional Interface Built using Gradio for an interactive and user-friendly experience.



Export Options

PDF format

TXT format

Production-Ready Output Generates clean documentation suitable for real-world projects.

🏗️ System Architecture

<img width="1536" height="1024" alt="ChatGPT Image Mar 3, 2026, 12_34_05 PM" src="https://github.com/user-attachments/assets/4b5127a5-da8a-475d-95a1-20e3f1d6db32" />

User inputs Python function

AST Parser analyzes function structure

Logic Analyzer detects behavior patterns

Docstring Generator formats output (Google / NumPy style)

Export Module generates downloadable documentation


🛠️ Technologies Used

Python

AST (Abstract Syntax Tree)

Gradio

Report generation libraries (for PDF export)



💡 How It Works

The system parses Python code using AST.

It extracts parameters, default values, annotations, and return statements.

Logic detection identifies function purpose based on structure.

A structured docstring is generated in the selected style.

Users can copy or export the generated documentation.



🚀 Advantages

Saves developer time

Ensures documentation consistency

Reduces human error

Improves code readability

Supports professional standards



📂 Use Cases

Academic projects

Open-source repositories

Enterprise Python applications

Code review and documentation improvement



🔮 Future Enhancements

Class and module-level docstring generation

GitHub integration

API documentation export

AI-powered summary refinement


📌 Conclusion

Doc-Genie simplifies Python documentation by combining AST analysis with intelligent docstring generation. 

It provides a structured, consistent, and production-ready solution through a clean Gradio interface, making documentation faster, easier, and more reliable for developers.
