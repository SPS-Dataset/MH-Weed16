# MH-Weed16
MH-Weed16:An Indian Multiclass Annotated Weed Dataset for Computer Vision Tasks


Detailed Process of Annotation using open labeling
1)  URL of MH-Weed16 dataset is  https://doi.org/10.34740/kaggle/dsv/11528454, download and extract zip files
   and copy the 'class_list.txt', 'start.py', and 'start.bat' files and put them in the main folder of intel real_sense_clicks.
2) You need to install:

	1. Python.

	2.OpenCV version > 3.0 

		- python -mpip install -U pip
		- python -mpip install -U opencv-python
		- python -mpip install -U opencv-contrib-python

	3. numpy, tqdm and lxml:

		- python -mpip install -U numpy
		- python -mpip install -U tqdm
		- python -mpip install -U lxml



3) Run the project step by step:
	
	1. Open the main/ directory.
	2. Insert the input images in the folder.
	3. Insert the classes in the file class_list.txt (one class name per line).
	4. click on the start.bat file:

4) After running the code use the keyboard key and mouse click the event:

	1. Keyboard key:
		1. Press key 'a' for the previous image
		2. Press key 'd' next image
		3. press key 's' previous class
		4. press key 'w' next  class
		5. press key 'q' and 'Esc' exit window

	2. Mouse:
		1. Use two separate left clicks to do each bounding box
		2. Right-click -> quick delete!


Citation for Dataset: kaggle: @misc{sayali_shinde_dr_vahida_attar_2025,
	title={MH-Weed16},
	url={https://www.kaggle.com/dsv/11528454},
	DOI={10.34740/KAGGLE/DSV/11528454},
	publisher={Kaggle},
	author={Sayali Shinde and Dr.Vahida Attar},
	year={2025}
}


Mendeley Data: Shinde, Sayali; Attar, Dr. Vahida; Technological University Pune, COEP; Technology Innovation Hub, Indian Statistical Institute Kolkata, IDEAS (2024), “MH-Weed16:An Indian Multiclass Annotated Weed Dataset for Computer Vision Tasks ”, Mendeley Data, V1, doi: 10.17632/d3n3mgjjbv.1


