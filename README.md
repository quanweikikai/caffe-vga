--------------------------------------------------------
		Solver to train caffe vgg16				   
--------------------------------------------------------

train:
caffe train -solver ./solver.prototxt
caffe train -solver ./solver.prototxt -weights [weights file]
caffe train -solver ./solver.prototxt -weights [weights file] --gpu [gpu num]
