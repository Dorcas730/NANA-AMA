// Function to process the array of numbers
function processArray(numbers) {
    return numbers.map(number => {
        if (number % 2 === 0) {
            // If the number is even, square it
            return number * number;
        } else {
            // If the number is odd, triple it
            return number * 3;
        }
    });
}

// Exporting the function for use in other files
module.exports = { processArray };
