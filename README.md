# Tensorboard
answer for windows environment tensorboard application
This file is ran for tf.__version__ '1.2.1',the Python environment is installed by Anaconda.
After you run the file,then run "tensorboard --logdir directory" through the Anaconda Prompt.
Ant then input "localhost:6006/" in Browser, which is just valid for Chrome. 
Notice: "tensorboard --logdir directory" the directory must in the same directory with your Python file,
which can diferent from the directory in "writer = tf.summary.FileWriter(r'F:\log', sess.graph)".
