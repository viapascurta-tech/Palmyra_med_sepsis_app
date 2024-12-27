![PyPI - Version](https://img.shields.io/badge/Pyhton-v3.11.10-blue)
![PyPI - Version](https://img.shields.io/badge/shiny%20for%20python-v0.10.2-blue)
![PyPI - Version](https://img.shields.io/badge/chromadb-v0.5.23-brown)
![PyPI - Version](https://img.shields.io/badge/llama%20index-v0.12.5-blue)
![PyPI - Version](https://img.shields.io/badge/Writer_Palmyra_med_llm-70b-blue)
![PyPI - Version](https://img.shields.io/badge/NVIDIA_platform-green)
![PyPI - Version](https://img.shields.io/badge/ISAAC_sepsis-3.0-%23000055)


# Palmyra_med_sepsis_app
 This is the repository for a research project concerning building LLM-RAG-based apps
## Overview
The repository contains files with persisting ChromaDB vector stores used for the functioning of an RAG-based software application that uses elements of a [multi-agentic approach](https://www.crewai.com/).
## The software applications for decision-making at an early stage of sepsis
The application requires input of information about a particular sepsis case as a clinical vignette. By pressing respective buttons on the application GUI, the user will get 
* *literature-based recommendations* concerning case management,
* *antibiotic recommendations*
* a *statement concerning the compliance of the generated recommendations with current sepsis guidelines*.
![GUI](https://github.com/user-attachments/assets/985f9ec4-6ef4-4909-aa2b-c45e51bfc8fd)

### Availability
For experimenting with the application can be accessed at https://huggingface.co/spaces/viapascurta/N_S_P_med. 
By activating the **How to Use the Application** button on the upper horizontal menu, the user gets detailed instructions on how to use the application.
