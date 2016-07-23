# Roadmap

This document describes the roadmap for `tensflow.rb.`

[![Code Climate](https://codeclimate.com/github/Arafatk/tensorflow.rb/badges/gpa.svg)](https://codeclimate.com/github/Arafatk/tensorflow.rb)
[![Join the chat at https://gitter.im/Arafatk/tensorflow.rb](https://badges.gitter.im/Arafatk/tensorflow.rb.svg)](https://gitter.im/Arafatk/tensorflow.rb?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


## Simpler things to get started:

- Polish the README based on your experiences on setting up the project, so it becomes easier for the next to join.
- Add any missing specs you see, e.g. `Session#ruby_array_to_c` and the likes. Some of the methods in Graph, Session, Tensor should probably also be private if only called from within the class. If not, they must be tested.
- Similar to 2. above, several methods could be cleaned up, and be written more ruby like (e.g. no `()` if no args and prefer `key: :value` over `:key => :value`.

## More advanced/new features:

- [ ] Look at the [Basic Usage tutorial](https://www.tensorflow.org/versions/r0.9/get_started/index.html). What are we missing to be able to complete this?
  - [ ] `tf.Variable`, please coordinate with @Arafatk.
  - [ ] `tf.Constant`, please coordinate with @chrhansen.
  - [ ] `tf.random_uniform`
  - [ ] `tf.zeros`
  - [ ] `tf.reduce_mean`
  - [ ] `tf.train.GradientDescentOptimizer`
