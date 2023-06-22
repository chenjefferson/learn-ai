# 1 Getting Started

## Lesson

### Summary

In XKCD, they joked in 2015 that detecting whether something was a bird was impossible. It went from something that's impossible to, in 2023, something that can be runnable on a laptop computer.

A DataBlock gives fast.ai all the information to create a model.

Dylan Williams - colored cup on their desk
Peter Lockhart - 
David Perkins - 
  - people learn better with a context
  - doing the interesting stuff at the front is how people
  - as much depth later. You'll get good at deploying

People learn things best when they hear things in different ways

- green: they're doing fine
- yellow: working through my understanding. I would benefit from the tecaher slowing down or revisiting
- red: stop! I am not understanding and have a question

You should make sureto check Radek's book. You can take deep learning things and art together.

Everyone at the ML teams at Tesla and OpenAI do this course.

### Motivation

Ex. multiple people at Stanford, including doctors and engineers, collaborating.

Looking inside a neural network and seeing what it learned: the weights

Can combine features to create more advanced features. There are things that the network creates for itself. The deeper you get, the more sophisticated they are.

They'll show fonudational techniques that, with creativity, can be applied broadly. An image classifier applied to sound achieved a state-of-the-art result.

- lots of data - big companies that want to sell tihngs
- lots of expensivecomputers - state of the art work for free
- math 

You can use transfer learning and get tons of progress.

Tensorflow has been dying recently, while PyTorch is growing. Research is a leading indicator of industry. Note that PyTorch requires hairy code by default, and is meant as a foundation.

Fast.ai simplifies a lot of this down. Lots of code means easy to make mistakes, forget best practices, etc. which fast.ai fixes.

Most students run their notebooks on a cloud server. Install the most recent version.

While training, because GPUs are quick, most of their time can be spent opening an image, and smaller images are often good enough for CV algorithms.

There's a small amount of models that work for almost everything, and tweaking neural networks is oftentimes not necessary nowadays.

Use image and category block, and then to split the problem set and how to transform them. We can usually fine tune models via `fine_tune`.

We can segment things as well! We create a learner and then run segmentation. `show_batch` on any data should show you useful data regardless of what you do. Tabular models are typically unique to the data and just fit. It's good to fit from a bit below the range to a bit above.

Everything's in the book and you can open it in notebooks. The source code for the library is also all notebooks.

Deep learning often breaks the state of the art in alot of things. It helps if it's something a human can do pretty quickly, while logical thought processes could take longer.

## High Level Overview

The model takes all the inputs, multiplies them, replaces the negatives with 0, and then passes it tothe next layer.

Weights start off as random, and are evaluated through a loss function. Neural networks are provably an infintely flexible function.

In theory, we can solve anything given enough time and data.

## Goal of Your First Week

Experiment.

## TODO

Collaborate in the forms. Recognizing the state of things, or evaluating

- [ ] Anki everything
- [ ] read the book
- [ ] evaluating the difficulty
- [ ] behavior metrics and carder behavior

### See

Ethics course: [link](ethics.fast.ai)
The tutorials: docs.fast.ai
