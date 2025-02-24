# Finwave Pipeline

A tool to engage with the various modules of the finwave pipeline for extracting
and verifying fins.

# Local Setup
1. Download the source code
2. In the terminal: 
```bash
    cd src
    python3 -m venv venv
    source venv/bin/activate
    pip3 install -r requirements.txt
    python3 finwave_pipeline.py
```

# Running the Binaries:
1. Visit [the releases page](https://github.com/alexanderbarnhill/FinwavePipeline/releases`) 
and fetch the relevant binaries for your system
2. Download and extract the zip file
3. Run the `finwave_pipeline` file (or `finwave_pipeline.exe` on windows)

# Settings
The most important settings are 
- `input_directory` : the directory from which the tool will look for images
- `output_directory` : Where the files will be written extraction / verification

***make sure to hit 'save' before running the pipeline***

