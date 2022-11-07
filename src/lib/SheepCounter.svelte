<script>
<<<<<<< HEAD
    let count = 0;
    let double = 0;
  
    $: if (count >= 16) {
      alert("The pen is full");
      count = 15;
    }
  
    const increment = () => {
      count += 1;
    };
    $: {
      console.log(`${count}`);
      console.log(`the count is ${count}`);
      double = count * 2;
      console.log(`double the count is ${double}`);
    }
  </script>
  
  <button on:click={increment}>
    Click to buy a sheep => {count} sheep
  </button>
=======
  let count = 0;

  $: if (count >= 16) {
    alert("The pen is full");
    count = 15;
  }

  const increment = () => {
    count += 1;
  };
</script>

<button on:click={increment}>
  Click to buy a sheep => {count} sheep
</button>
>>>>>>> 5425243e653bf6dfd0c1be6d0c8438861ebc19c7
