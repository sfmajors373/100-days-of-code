# 100 Days Of Code - Log

### Day 0: December 15, 2019

**Today's Progress**: Worked on setting up a Ubuntu vm to run solaris (the utilities library for the Spacenet dataset), which I can't run on my normal install due to issues with my Python version, so I am running a vm to try to make it install correctly there.  I got further than I did locally, but am having an issue with a pip wrapper now, so I will continue on that tomorrow.  I also worked on Udacity Introduction to Deep Learning with PyTorch lesson 6.10 and 6.11 which is the preparation for creating a multi-layer perceptron for classifying MNIST images.

**Thoughts:**  Today was just set up for more interesting stuff tomorrow.

**Link to work:** [MNIST mlp](https://github.com/sfmajors373/deep-learning-v2-pytorch/blob/master/convolutional-neural-networks/mnist-mlp/mnist_mlp_exercise.ipynb)

### Day 1: December 16, 2019

**Today's Progress**: Continued work on setting up the vm for solaris.  I keep trying to go quickly and making stupid mistakes and then throwing it out and starting over.  Bad practice all over.  I also checked out the introduction videos and lesson 1.1 and 1.2 in the Intel Edge scholarship Udacity course.

**Thoughts:**  Unfortunately, I was not in a great mental space for productively coding today.  Hopefully, I can get this vm working tonight but if not there is always tomorrow.  I just really want to move on to actually working on the project.

**Link to work:** Nothing to show today

### Day 2: December 17, 2019

**Today's Progress**: Finished the videos and exercises in lesson 3 for the Intel Edge course.  Worked on the mlp mnist notebook for lesson 6.12 for the deep learning course.  It is training now. 

**Thoughts:** Have a migraine.  Am nauseous.  That mlp isn't my best work, but it is working and today that is all that matters.  Maybe I will add dropout or change the loss/optimizer tomorrow.

**Link to work:** [MNIST mlp](https://github.com/sfmajors373/deep-learning-v2-pytorch/blob/master/convolutional-neural-networks/mnist-mlp/mnist_mlp_exercise.ipynb)

### Day 3: December 18, 2019

**Today's Progress**: Worked through lessons 6.13-6.19 in the deep learning course.  Also made another Ubuntu vm for the GIS project.

**Thoughts:** Good work day.

**Link to work:** Nothing to link today.  Just another prep day for exciting things later.

### Day 4: December 19, 2019

**Today's Progress**: Worked more on the Ubuntu VM for solaris.  Ended up back in my regular machine trying to run the solaris exercise without actually needing solaris.  The tutorial itself seems a bit buggy though.  And tqdm has a really weird progress bar message that looks like an error, but may not be an error.  I still don't know.

**Thoughts:** I'm really frustrated with solaris at the moment.  I really want to try to use it for my project, but it really looks like I am going to have to just buckle down and do this project without it. Recap of solaris problems: if installed, jupyter kernels is unstable and dies frequently.  If attempting to install and gets stuck, it will just show that I do not have a dependency installed and then I uninstall and reinstall and then move onto the next dependency, repeat the process which breaks the install of the first (and we are talking pandas, numpy etc, that do not conflict)

**Link to work:** Nothing to link today.  Just another prep day for exciting things later.

### Day 5: December 20, 2019

**Today's Progress**: Finished all videos for lesson 6, but still need to finish the Cifar-10 CNN notebook.  Continued fighting with my GIS data.

**Thoughts:** Not many thoughts today.

**Link to work:** Nothing to link today.  Just another prep day for exciting things later.

### Day 6: December 21, 2019

**Today's Progress**: Worked through the Bertelsmann Scholarship course lesson 7 on Style Transfer.  The model is training right now though so I am not yet certain that it worked.  I also continued work on my GIS project though I spent the entire day trouble shooting the wrong spot and creating many many duplicates of the image tiles so I have deleted those and am redoing that step (on a different machine than is training my style transfer model).  I also had a wonderful chat with the people in the Bertelsmann AI in Medical Science scholarship group discussing projects that some of us have already worked on and set up time to discuss potential future projects for us.

**Thoughts:** Reasonably productive day so long as all the training and image tiling goes well over night.

**Link to work:** [Style Transfer](https://github.com/sfmajors373/deep-learning-v2-pytorch/tree/master/style-transfer)  [Reference Article](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf)

### Day 7: December 22, 2019

**Today's Progress**: Completed the Character RNN and the Sentiment Analysis projects for the Bertelsmann Challenge while my GIS project worked on crunching satellite data numbers (still in the preprocessing step).  Also to note, the models for the scholarship are not trained yet as I need to reinstall drivers for the GPU so cuda will work on the server.

**Thoughts:** I got a lot done.  I'm pretty happy about it since I will need to have time to devote to the GIS project when I get the preprocessing done and my thesis once I collect more data for it.

**Link to work:** [Character RNN](https://github.com/sfmajors373/deep-learning-v2-pytorch/tree/master/recurrent-neural-networks/char-rnn)  [Sentiment Analysis](https://github.com/sfmajors373/deep-learning-v2-pytorch/tree/master/sentiment-rnn)
