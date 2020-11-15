# scrub-system-for-de-identification
A scrub system for de-identification and cleaning of data to maintain the privacy of data when sharing it with other organizations. Here, we are focusing on the medical dataset as it is quite vulnerable to data leakage. But this algorithm can be applied to any dataset to ensure its privacy.
## How to use? 
python main.py -f Input_files/records.csv -o output_file_name
<br><br>
-f, --input-file-path: Input file path
<br>
-o, --output-file-name: Output file name
## Demo
<img src="screenshots/output.png" width="650px" alt="Output Image">
The above image is an illustration of the output.<br><br>
<strong>Note:</strong> 3 inputs are taken from the user as highlighted in the above image. Based on these inputs, the decision is formed and the output is shown. 
<br><br>
<strong>Check out the complete demo with explanation <a href="https://www.youtube.com/watch?v=XGd56JY03BU">here</a><strong>
<br>
<h2>Dataset used</h2> 
A medical open-source dataset named "Electronic Health Record (EHR) Incentive Program Payments for Eligible Providers" taken from <a href="https://catalog.data.gov/dataset/electronic-health-record-ehr-incentive-program-payments-for-eligible-providers-a4199/resource/52303c5a-ac7c-4064-9271-e960dbf69f74">here</a>
