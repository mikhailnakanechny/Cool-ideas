# Cool-ideas

function sequence(n, pattern) {
  return Array.from({length: n}, typeof pattern === "function" ? pattern : () => pattern)
}
