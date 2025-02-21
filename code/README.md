# To replicate the analyses in our manuscript:  

<b>Unzip the following files and remove the original `.zip` versions:</b>
+ data/sustained_attention_experiment/19_2019_Oct_15/eye_data/19_7.txt.zip
+ data/variable_attention_experiment/10_2019_Nov_16/eye_data/10_7.zip
+ data/variable_attention_experiment/29_2020_Jan_13/eye_data/29_7.zip
+ data/variable_attention_experiment/9_2019_Nov_16/eye_data/9_7.zip
+ data/variable_attention_experiment/8_2019_Nov_16/eye_data/8_7.zip

<b>Run the code in each of this directory's jupyter notebooks, in numerical order:</b>

+ 1_compile_data.ipynb
+ 2_preprocess_data.ipynb
+ 3_analyze_data.ipynb

<b>If you would rather skip straight to the main analyses, simply run `3_analyze_data.ipynb` </b> 

<b> Note:</b> We use python datetime package to match up timepoints in our gaze data with our behavioral data. If you are in another timezone, you may run into issues. To get around this, you may opt to briefly set your computer's clock to EST (when running the first notebook) or adjust the datetime package (rersources here: https://docs.python.org/3/library/datetime.html)
