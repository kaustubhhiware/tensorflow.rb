# Simpler things to get started:

- Polish the README based on your experiences on setting up the project, so it becomes easier for the next to join
- Add any missing specs you see, e.g. `Session#ruby_array_to_c` and the likes. Some of the methods in Graph, Session, Tensor should probably also be private if only called from within the class. If not, they must be tested.
- Similar to 2. above, several methods could be cleaned up, and be written more ruby like (e.g. no `()` if no args and prefer `key: :value` over `:key => :value`. But I wouldn't touch any of these methods until we for sure have specs

# More advanced/new features:

- [ ] Start work on `tf.Variable`, but coordinate with @Arafatk.
- [ ] Start work on `tf.Constant`, but coordinate with @chrhansen.
- [ ] Look at the Basic Usage tutorial. What are we missing to be able to complete this?
- [ ] If you're strong in setting up Travsis-CI + C-compilers, help me with chrhansen/tensorflow.rb#1 which I'm currently struggling with https://travis-ci.org/chrhansen/tensorflow.rb/builds/145432105
