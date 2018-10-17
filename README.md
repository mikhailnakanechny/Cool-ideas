# Cool-ideas

function sequence(n, pattern) {
  return Array.from({length: n}, typeof pattern === "function" ? pattern : () => pattern)
}

function sequence(n, pattern) {
  return typeof pattern === "function" ? Array.from(Array(n), pattern) : Array.from(Array(n), x => x = pattern);
}
