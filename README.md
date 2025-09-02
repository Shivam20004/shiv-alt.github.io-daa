
<!-- User-defined function to calculate sum of first N natural numbers -->
<script>
function sumOfNaturalNumbers(N) {
    let sum = 0;
    for (let i = 1; i <= N; i++) {
        sum += i;
    }
    return sum;
}

//Get user input
let N = parseInt(prompt("Enter a positive integer: "));

if (N > 0) {
    let result = sumOfNaturalNumbers(N);
    alert(`The sum of the first ${N} natural numbers is: ${result}`);
} else {
    alert("Please enter a positive integer greater than 0.");
}
</script>
             
