# List of Tutorials
[**Problem-Solving_Skill.ipynb**](https://nbviewer.jupyter.org/github/department-of-vet-pathology-unizg/tutorials/blob/master/notebooks/Problem-Solving_Skill.ipynb)

[**Microscope_Automation.ipynb**](https://nbviewer.jupyter.org/github/department-of-vet-pathology-unizg/tutorials/blob/master/notebooks/Microscope_Automation.ipynb)

# Other Resources
[**Linux Journey**](https://linuxjourney.com/) - A great resource for learning Linux

[**Jupyter notebook**](https://nbviewer.jupyter.org/github/fastai/course-v3/blob/master/nbs/dl1/00_notebook_tutorial.ipynb) - A quick tutorial on jupyter notebook 

[**fast.ai**](https://course.fast.ai/) - Deep learning course

---

# Motivation

Our goal is to apply Deep Learning in automating and developing more accurate, faster and less expensive diagnostic procedures in pathology. Deep learning is a set of algorithms that enables a computer to learn something from previous examples, in a way similar to how humans learn. For this reason, in media they are more often called "Artificial Intelligence".

Deep learning has proven to be an extremely effective technique for a broad range of computer vision task, especially in medicine. It is often more important to have a deep understanding of the data than it is to have a PhD in statistics and, as a result, there is a high, unfilled demand for data scientists with a background in medicine. We hope that students on this project will continue to develop in this field after graduating from VEF.

You can read more about the importance of deep learning in veterinary medicine in this blog post: [Why Veterinary Medicine Desperately Needs Deep Learning](https://medium.com/@kvinicki/why-veterinary-medicine-desperately-needs-deep-learning-daf1785f2146)

We'll be using [Python](https://github.com/department-of-vet-pathology-unizg/tutorials/blob/master/README.md#Python) as our programming language, [Jupyter notebook](https://nbviewer.jupyter.org/github/fastai/course-v3/blob/master/nbs/dl1/00_notebook_tutorial.ipynb) as programming environment and [Linux](https://github.com/department-of-vet-pathology-unizg/tutorials/blob/master/README.md#Linux) as OS.


# Python

Python is a high-level programming language, which means that "under the hood", it handles a lot of programming complexity for you. This makes Python not only beginner-friendly, but also ideal for domain experts and students without a prior background in computer science (like vet-med students). Python code is also very clean (readable) and compact - code written in Python is often a couple of times shorter than the same code written in C++ or Java. 

There are a lot of misconceptions about programming. As a vet student, you should think about Python simply as a tool. Python is a very powerful tool on its own, but with the help of a few popular libraries like numpy and OpenCV, it becomes a powerful environment for scientific computing and image processing. At the same time, Python can give us a flexibility that no other software can offer.

### Resources for Learning Python

There are two main resources that we recommend:
1.  As the **main resource** for learning Python we recommend **part I** of the **book [Python Crash Course](https://www.amazon.com/Python-Crash-Course-2nd-Edition/dp/1593279280)**. This book doesn't assume any prior programming experience.
2. If you prefer video lessons, you can start by watching [this youtube tutorial](https://www.youtube.com/watch?v=rfscVS0vtbw). It explains all the basics you need to know in only 4 hours. 

### How to Learn

The test of whether you understand code is not to read it and think "yeah, that makes sense". **The test of whether you understand something is whether you can write it yourself.**

There are at least 3 reasons for this:
1. Setting something aside and re-creating it forces your brain to [actively recall](https://en.wikipedia.org/wiki/Active_recall) the information, as opposed to passively reviewing. It's the difference between reading a textbook and using flashcards to quiz yourself. Active recall, unlike passive review, has been shown to be efficient in forming long-term memory.
2. It forces you to think about what step to take next, which ensures that you are thinking carefully about the *process*.
3. Experimenting with inputs and outputs helps you understand things intuitively.

These learning tips were taken from fast.ai [wiki](http://wiki.fast.ai/index.php/How_to_use_the_Provided_Notebooks)


# Linux

In data science, Linux is the standard. A majority of data science companies are using Linux as their primary OS. As a result, libraries that we will be using are also more stable and faster on Linux than on Windows. For example, this is a paragraph taken from fast.ai (deep learning library) GitHub page:

"_fastai v1 currently **supports Linux only**, and requires PyTorch v1 and Python 3.6 or later. Windows support is at an experimental stage: it should work fine but it's much slower and less well tested. Since Macs don't currently have good Nvidia GPU support, we do not currently prioritize Mac development._"

It is clear that, when we are talking about platform support, the majority of resources are directed toward Linux. Windows 10 is becoming less and less relevant in this field, and our students need to become familiar with Linux.


# Our Position on Education

We are advocating project-based learning. To keep students highly motivated and create a rewarding learning experience, it is crucial to allow them to work on meaningful projects. We are always trying to choose problems that are not only important to solve but, once they are solved, can also be tested and used directly for various diagnostic procedures on our department.

As a student, your primary goal should be to learn how to solve complex problem in veterinary medicine with Python and Deep Learning. You won't learn how to solve problems by reading the Python Crash Course book or by watching video lessons that we recommended. They are here just for picking some python basics and there is no point in spending more than a couple of weeks on them. 

Your first task after learning python basics will be to automate a microscope and [create a microscope slide scanner](https://nbviewer.jupyter.org/github/department-of-vet-pathology-unizg/tutorials/blob/master/notebooks/Microscope_Automation.ipynb). This task will show you just how powerful python is and, more importantly, it will help you develop some general principles for solving complex, real-world problems with python.

Just as with any new skill, when starting with programming, you need to go to "begginer mode" and accept just how much you suck at this new skill. That is ok. Learning to program is a process and we are always here to help you with it.

### Community

There is a profound change in the way how generations that grew up on the Internet define freedom and community. Today's education should reflect that!

The previous generation's definition of freedom was very simple: to be free is to be an autonomous agent, to be independent, to not be beholden to others so that one can have freedom as exclusivity.

For the generations that are now entering higher education, on the other hand, being an island to oneself is death. This generation asks the question: How can I flourish to the full extent of my possibilities? And it is clear that the answer to that is "I flourish to the extent that I'm embedded in the network after network, after network; community after community, where I can share my talents, and those talents can benefit the network and come back to benefit myself. Therefore, for these generations, freedom is not exclusivity, it's not being an autonomous agent. It's inclusivity. It's access to others in networks."

Education should be a shared experience. The teacher is important as a facilitator and guide, but the students have to teach each other. This project is designed in the way to facilitate that process and every student is encouraged to write and publish tutorials that could benefit himself and others.

*This text is adapted from _The Third Industrial Revolution_ by _Jeremy Rifkin_.
