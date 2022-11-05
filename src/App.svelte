<script>
  import SheepCounter from "./lib/SheepCounter.svelte";
  import Box from "./lib/Box.svelte";
  import BuySheep from "./lib/BuySheep.svelte";
  import SellSheep from "./lib/SellSheep.svelte";
  import MoneyCounter from "./lib/MoneyCounter.svelte";
    import RollDice from "./lib/RollDice.svelte";
</script>

<main>
  <div>
    <img src="./images/Game of Sheep.png" width = "300" alt="GameofSheep" />
  </div>
  <br><br>
  <Box>
    <div>
      <div class="note">Roll Dice</div>
      <div class="card">
        <RollDice />
      </div>
    </div>
  </Box>
  <Box>
    <div>
      <div class="note">Amount of Sheep</div>
      <div class="card">
        <SheepCounter />
      </div>
    </div>
  </Box>
  <Box>
    <div>
      <div class="note">Amount of Money</div>
      <div class="card">
        <MoneyCounter />
      </div>
    </div></Box
  >
  <Box>
    <div>
      <div class="note">Sell Sheep</div>
      <div class="card">
        <SellSheep />
      </div>
    </div>
  </Box>
  <Box>
    <div>
      <div class="note">Buy Sheep</div>
      <div class="card">
        <BuySheep />
      </div>
    </div>
  </Box>
  <Box>
    <div>
      <div class="note">Events</div>
    </div></Box
  >
  <Box>
    <div class="note">Wool Sale</div>
  </Box>
  <Box>
    <div>
      <div class="note">Drought Status</div>
    </div></Box
  >
  <Box>
    <div>
      <div class="note">Paddocks</div>
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

  <div class="footer">
    <p />
    <strong>A pen holds 15 sheep</strong>
    <p />
    <a href="https://github.com/michaelkernaghan/gameofsheep">V.0.0</a>
    created with
    <a
      href="https://tezostaquito.io/"
      target="_blank"
      rel="noopener noreferrer nofollow">Taquito</a
    >!
  </div>
 
<div>
  <h1>NFTs</h1>
  <h2>Benefits</h2>
  <img src="./images/Benefits/Fire Fighting Equipment.png" width = "350" alt="Fire Fighting Equipment" />
  <img src="./images/Benefits/Hay Stack.png" width = "350" alt="Hay Stack" />
  <img src="./images/Benefits/Insurance Policy for Stud Ram.png" width = "350" alt="Insurance Policy for Stud Ram" />
  <h2>Control Programmes</h2>
  <img src="./images/Control Programmes/Control of Weeds and Insects.png" width = "350" alt="Control of Weeds and Insects" />
  <img src="./images/Control Programmes/Fertilized Pasture.png" width = "350" alt="Fertilized Pasture" />
  <img src="./images/Control Programmes/Worm Control Programme.png" width = "350" alt="Worm Control Programme" />
  <h2>Liabilities</h2>
  <img src="./images/Liabilities/High Stock Prices Ruling.png" width = "350" alt="High Stock Prices Ruling" />
  <img src="./images/Liabilities/New Shearing Shed.png" width = "350" alt="New Shearing Shed" />
  <img src="./images/Liabilities/Blow Fly Wave.png" width = "350" alt="Blow Fly Wave" />
  <h2>Stud Rams</h2> 
  <img src="./images/Stud Rams/Elmsford Park Rex.png" width = "350" alt="Elmsford Park Rex" />
  <img src="./images/Stud Rams/King of Warramboo.png" width = "350" alt="King of Warramboo" />
  <img src="./images/Stud Rams/Lachlan Lad.png" width = "350" alt="Lachlan Lad" />
  <img src="./images/Stud Rams/Mitchell's Pride.png" width = "350" alt="Mitchell's Pride" />
  <img src="./images/Stud Rams/Winton Boy II.png" width = "350" alt="Winton Boy II" />
</div>


</main>

<style>
  :global(body) {
    background-color: #a0aaa3;
  }
</style>
