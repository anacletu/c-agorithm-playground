# Function to add an algorithm (creates a library)
function(add_algorithm ALGORITHM_NAME)
 add_library(${ALGORITHM_NAME} ${ALGORITHM_NAME}.c)
endfunction()

# Add mathematical algorithms
add_algorithm(karatsuba)