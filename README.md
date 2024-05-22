# Multilingual Statement Tuning

## Getting Started

    conda create -n myenv python=3.8
    conda activate myenv
    pip install -r requirements.txt
Now you should have all the dependencies for the code.

## Create Statement Data

To view a few examples of how to create statement data for training you can view the notebook

    ./create-statement-data.ipynb

## Statement Tuning
An example of how to train a statement tuned model is shown in 

    ./statement-tune.ipynb
The example is on monolingual data however it can be easily adapted if provided multilingual statement data on HuggingFace.

## Zero-shot Evaluation

To view how to carry out statement tuned Zero-shot evaluation on XCOPA view the notebook

    ./easy_zeroshot_eval.ipynb
