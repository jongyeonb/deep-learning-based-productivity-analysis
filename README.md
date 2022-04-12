# deep-learning-based-productivity-analysis
deep-learning-based productivity analysis of construction machineries
Model 0
	
Model 1
- crawling_253_images
	<Dataset info>
	web-crawled images(crane, module, crane+module) for train, validation sets
	/AJ ho vid for test set
	train : validation = 9 : 1
	train: 227 images
	validation: 26 images
	test: 1920 x 1080, 24fps, 10114kbps, 7min45sec surveilance video
	<Performance info>
	mAP: 91.7%, sudden drops near iterations 1100, 1400, 2300
	precision:
	recall:
	
- crawling_cross_oversampling
	<Dataset info>
	
	<Performance info>

Model 2
- model2
	<Dataset info>
	pu + sb + sw + js, randomly split into train, validation sets
	AJ ho vid for test set
	train : validation = 0.82 : 0.18
	train: 133805 images
	validation: 29025 images
	test: 1920 x 1080, 24fps, 10114kbps, 7min45sec surveilance video
	<Performance info>
	mAP: 98.0%
	precision:
	recall:
	
	
- model2_v2
	<Dataset info>
	pu + sb + sw + js, randomly split into train, validation, test sets
	train : val : test = 0.64 : 0.16 : 0.2
	train: 107044 images
	validation: 26761 images
	test: 20925 images
	<Performance info>
	mAP: 97.9%
	precision: 
	recall: 
	
- model2_school
	<Dataset info>
	pu + sb + sw, randomly split into train, validation sets
	js for test set
	train : validation = 0.8 : 0.2
	train: 1007 images
	validation: 252 images
	test: 253 images
	<Performance info>
	mAP: 80.9%, sudden drop near iteration 1100
	precision:
	recall: 
	
*
image counts per con sites
sb: 
js:
sw:
pu:
ho: 
sh: 

* flag selection for performance analysis


* TP, FP, FN, TN reports + confusion matrix

* optimal iteration number, loss

* designing loss function

* designing CNN layer
