<<<<<<< HEAD
# Cool-ideas

function sequence(n, pattern) {
  return Array.from({length: n}, typeof pattern === "function" ? pattern : () => pattern)
}

function sequence(n, pattern) {
  return typeof pattern === "function" ? Array.from(Array(n), pattern) : Array.from(Array(n), x => x = pattern);
}
=======
# Cool-ideas
>>>>>>> parent of 5ea30f5... Update README.md
