API unit tests : 	A test file that hits the Flask endpoints (predict, train, logs)
Model unit tests : 	Tests for train/load/predict functions
Logging unit tests : 	Tests that check log files get written
Single test script :	A run-tests.py (or similar) that runs everything and passes
Performance monitoring :	Novelty or drift detection, plus a logged performance metric
Test isolation	: Tests write to a separate test model/log directory, not production ones
API works	predict works for one country and for all
Data ingestion function :	A reusable ingestion script or function
Multiple models compared	At least two models with a comparison table
EDA visualizations	Plots in a notebook or saved images
Docker	A Dockerfile that builds and runs the app
Baseline comparison plot	A figure comparing the model with the baseline
