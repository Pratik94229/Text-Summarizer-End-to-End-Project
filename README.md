

# End-to-End Text Summarization Project

This is an end-to-end Text Summarization project that aims to generate concise summaries from given text documents using natural language processing techniques. The project includes various components and workflows to facilitate the text summarization process.

## Project Structure

├───.github
│   └───workflows
├───config
├───research
├───src
│   ├───textSummarizer
│   │   ├───components
│   │   ├───config
│   │   ├───constants
│   │   ├───entity
│   │   ├───logging
│   │   ├───pipeline
│   │   ├───utils

The project structure is organized as follows:

- `config.yaml`: Configuration file that contains project-specific settings and parameters.
- `research`: Contains notebook experiments which were performed before modular code implementation
- `params.yaml`: Parameter file that stores model-specific parameters and configurations.
- `entity`: Directory containing entity definitions and related files.
- `src/config`: Directory containing the configuration manager for accessing project configurations.
- `components`: Directory containing various components used in the text summarization pipeline.
- `pipeline`: Directory containing the main text summarization pipeline implementation.
- `main.py`: Main script that orchestrates the text summarization process.
- `.github/workflows`:Contains code for CICD .


## Getting Started

To get started with the project, please follow these steps:

1. Clone the repository:
```
git clone https://github.com/Pratik94229/Text-Summarizer-End-to-End-Project.git
```

2. Create a conda environment and activate it:
```
conda create -p venv python==3.8 
conda activate venv/
```

3. Install the required dependencies:
```
pip install -r requirements.txt
```

4. Run the application:
```
python app.py
```

5. Access the application:
Open your web browser and go to `http://localhost:8080` to access the text summarization service.


For any inquiries or questions, please feel free to contact me at pratik.941@gmail.com.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as per the terms of the license.

---

