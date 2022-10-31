<script>
  import Counter from "./lib/Counter.svelte";
  import Box from "./lib/Box.svelte";
</script>

<main>
  <div class="container">
    <!-- <h1>Game of Sheep</h1> -->
    <div>
      <div class="columns">
        <Box>
          <div>
            <div class="note">Amount of Sheep</div>
            <div class="card">
              <Counter />
            </div>
            <!-- <input
                type="text"
                class="amount"
                bind:value={compoundValueInput}
              />
              <button on:click={compoundValue}>Go!</button>
              <div class="storage">
                New Compound Value Storage: {JSON.stringify(
                  compoundValueStorage
                )}
              </div> -->
          </div>
        </Box>
        <Box>
          <div>
            <div class="note">Amount of Money</div>
            <!-- <button on:click={createBigMap}>Go!</button>
              <div class="storage">
                New Big Map Id: {JSON.stringify(createBigMapStorage)}!
              </div>
            </div> -->
          </div></Box
        >
        <Box>
          <div>
            <div class="note">Events</div>
            <!-- <input type="text" class="amount" bind:value={simpleValueInput} />
              <button on:click={singleValue}>Go!</button>
              <div class="storage">
                New Simple Value Storage: {simpleValueStorage}
              </div> -->
          </div></Box
        >
        <Box>
          <div>
            <div class="note">Stock Sale</div>
            <!-- <button on:click={updateStudRam}>Update Stud Rams</button> -->
          </div>
        </Box>
        <Box>
          <div>
            <div class="note">Wool Sale</div>
            <!-- <button on:click={updateStudRam}>Update Stud Rams</button> -->
          </div>
        </Box>
        <Box>
          <div>
            <div class="note">Drought Status</div>
            <!-- <input type="text" class="amount" bind:value={compoundKeyInput} />
              <button on:click={compoundKey}>Go!</button>
              <div class="storage">
                New Compound Key Storage: {compoundKeyStorage}
              </div>
            </div> -->
          </div></Box
        >
        <Box>
          <div>
            <div class="note">Paddocks</div>
            <!-- <input
                type="text"
                class="amount"
                bind:value={compoundKeyCompoundValueInput}
              />
              <button on:click={compoundKeyCompoundValue}>Go!</button>
              <div class="storage">
                New Compound Key Compound Value Storage: {JSON.stringify(
                  compoundKeyCompoundValueStorage
                )}
              </div> -->
          </div>
        </Box>
        <Box>
          <div>
            <div class="note">Stud Rams</div>
            <!-- <button on:click={updateStudRam}>Update Stud Rams</button> -->
          </div>
        </Box>
        <Box>
          <div>
            <div class="note">Haystacks</div>
            <!-- <button on:click={updateStudRam}>Update Stud Rams</button> -->
          </div>
        </Box>
        <Box>
          <div>
            <div class="note">Mortgages</div>
            <!-- <button on:click={updateStudRam}>Update Stud Rams</button> -->
          </div>
        </Box>
        <Box>
          <div>
            <div class="note">Programmes</div>
            <!-- <button on:click={updateStudRam}>Update Stud Rams</button> -->
          </div>
        </Box>
      </div>

      <div class="footer">
        <p />
        <a href="https://github.com/michaelkernaghan/gameofsheep">V.0.0</a>
        created with
        <a
          href="https://tezostaquito.io/"
          target="_blank"
          rel="noopener noreferrer nofollow">Taquito</a
        >!
      </div>
    </div>
  </div>
</main>

<style>
  :global(body) {
    background-color: #a0aaa3;
  }

  /*  h1 {
     color: blue;
     font-family: "Racing Sans One", cursive;
     font-size: 80px;
     margin: 10px;
   } */

  .container {
    font-size: 20px;
    max-width: 100%;
  }
</style>
