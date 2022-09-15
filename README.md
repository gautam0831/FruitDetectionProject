# Fruit Detection Project

Fruit	detection	is	an	important	initial	
step	to	make	autonomous	robots	for	various	
agricultural	tasks	such	as	harvesting	fruits,	
analyzing	ripeness,	and	detailed	mapping	of	
fields	according	to	fruit	density.	We	can	couple	
a	fruit	detector	with	mechanical	sensors	and	
components	to	create	a	fully-functioning	
autonomous	robot	to	harvest	fruits	at	a	far	
greater	rate.	
The	objective	is	to	discover	the	optimal	
approach	for	fruit	detection	from	images,	a	
relatively	unseen	research.	We	use	a	machine	
learning-based	method	to	classify	different	
fruits	by	not	only	determining	what	is	the	
object	of	interest,	but	also	its	location	by	
bounding	box	prediction.	We	approach	this	
problem	in	two	ways:	1)	Handcrafted	Features,	
2)	Deep	Networks.		While	implementing	
handcrafted	image	features	such	as		color	
histograms, Histogram	of	Oriented	Gradients	
(HOG)[5]	,	and	GIST	[1],	we	train	a	logistic	
regression	classifier	to	learn	a	fruit	detector.	
We	also	train	a	detector	under	a	state-of-theart	method–deep	learning–and	compare	the	
results	on	250	test	images	with	handcrafted	
learning	features,	both	qualitatively	and	
quantitatively	over	three	trials.	We	analyze	the	
deep	network,	which	is	built	upon	the	You	Only	
Look	Once	(YOLO)	deep	learning	platform,	by	
changing	the	amount	of	training	data	to	
observe	its	effect	on	detection	performance.	
After	experimentation,	we	found	that	deep	
networks	with	both	convolutional	and	fullyconnected	layers	perform	far	better	than	
handcrafted	features,	as	the	mean	average	
precision	(mAP)	for	the	deep	network	was	
45.3%	higher	than	that	of	the	combined	
handcrafted	detector.	The	mean	average	
precision	was	calculated	from	our	Precision	
versus	Recall	curves	for	corresponding	
detectors.
