# Practical Deep Learning for Coders (fast.ai courses)

These are the lecture materials from [Practical Deep Learning for Coders](http://course.fast.ai/). Two important parts of the course are  [our online forums](http://forums.fast.ai/) and [our wiki](http://wiki.fast.ai/index.php/Main_Page).  If you are encountering an error, we recommend that you first search the forums and wiki for a solution.  If you can't find the answer there, the next step is to ask your question on the forums.  See this advice on [how to ask for help](http://wiki.fast.ai/index.php/How_to_ask_for_Help) in a way that will allow others to most quickly and effectively be able to help you.  Please don't use Github Issues to ask for help debugging (many questions have already been answered in the forums).

## Setup a deep learning server on Amazon Web Services

To setup an Amazon Web Services (AWS) EC2 instance, execute the following scripts:

For a GPU-enabled server optimized for deep learning (subject to availability in your AWS region)
```
./setup/setup_p2.sh
```
For a regular server (available on all AWS regions) 
```
./setup/setup_t2.sh
```

These scripts will output information on how to connect to your instance and how to shut it down.
