# The Trane Project

Trane is an automated learning system for the acquisition of complex and highly hierarchical skills.
It is based on the principles of spaced repetition, mastery learning, and chunking.

Given a set of exercises which have been bundled into lessons and further bundled in courses, as
well as the dependency relationships between those lessons and courses, Trane selects exercises to
present to the user. It makes sure that exercises from a course or lesson are not presented until
the exercises in their dependencies have been sufficiently mastered. It also tries to keep the
difficulty of the exercises balanced, so that the selected exercises lie slightly outside the user's
current abilities.

Trane is named after John Coltrane, whose nickname Trane was often used in wordplay with the word
train (as in the vehicle) to describe the overwhelming power of his playing. It is used here as a
play on its homophone (as in "*trane* a new skill").

# Documentation

Latest documentation can be found at the [official site](https://trane-project.github.io/)

# Repositories

- The library implementing the core logic: [trane](https://github.com/trane-project/trane).
- The command line interface: [trane-cli](https://github.com/trane-project/trane-cli).
- Official courses:
  - [trane-music](https://github.com/trane-project/trane-music): Courses on music. Under construction.
  - [trane-earmaster](https://github.com/trane-project/trane-earmaster): Augments EarMaster exercises for use with Trane.
  - [trane-leetcode](https://github.com/trane-project/trane-leetcode): Courses on algorithm and data
  structure problems using exercises from LeetCode.
  - [trane-rustlings](https://github.com/trane-project/trane-rustlings): A course to learn Rust using
    trane and rustlings.
