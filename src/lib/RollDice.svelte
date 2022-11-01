<script>
    let count = 0;
    const randomDice1 = Math.floor(6 * Math.random()) + 1;
    const randomDice2 = Math.floor(6 * Math.random()) + 1;
    const diceRoll = randomDice1 + randomDice2;

    const increment = () => {
        count += diceRoll;
    };
</script>

<button on:click={increment}>
    Your Board Location Number => {count}
</button>
