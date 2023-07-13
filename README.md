# shortcut
  
/**
 * Finds the shortest path between two nodes.
 * 
 * @param {string} startNode - The starting node.
 * @param {string} endNode - The ending node.
 * @returns {string[]} - An array of nodes representing the shortest path.
 */
function findShortestPath(startNode, endNode) {
  try {
    // Check if startNode and endNode are valid nodes
    if (typeof startNode !== 'string' || typeof endNode !== 'string') {
      throw new TypeError('Both startNode and endNode must be strings');
    }
    
    // Perform the shortest path algorithm
    // ...
    
    // Return the shortest path as an array of nodes
    return ['Node1', 'Node2', 'Node3'];
  } catch (error) {
    // Log the error
    console.error('Error:', error.message);
    return [];
  }
}
