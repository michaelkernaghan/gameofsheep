<!-- App.svelte -->
<!-- <script>
  import { Router, Link, Route } from "svelte-routing";
  import Home from "./routes/+page.svelte";
  import Play from "./routes/play/+page.svelte";
  import NFTs from "./routes/nfts/+page.svelte";

    // Used for SSR. A falsy value is ignored by the Router.
    export let url = "";
</script>

<Router url="{url}">
  <nav>
    <Link to="/">Home</Link>
    <Link  to="play">Play</Link>
    <Link  to="nfts">NFTs</Link>
  </nav>
  <div>
    <Route path="play" component={Play} />
    <Route path="nfts" component={NFTs} />
    <Route path="/" component="{Home}" />
  </div>
</Router> -->
<h1>Hello and welcome to my site!</h1>
<a href="/play">Play</a>
<a href="/nfts">NFTs</a>