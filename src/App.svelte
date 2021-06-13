<script>
  import { onMount } from "svelte";

  function goToLinkedIn() {
    window.location.href =
      "https://www.linkedin.com/in/andrew-budziszek-ssm-929a1663";
  }

  function goToGitHub() {
    window.location.href = "https://github.com/SonnyBrooks";
  }

  function goToTwitter() {
    window.location.href = "https://twitter.com/AndrewBudziszek";
  }

  function openEmail() {
    window.location.href = "mailto:andrew@budziszek.com?subject=Hello!";
  }
  
  function goToayyyymc() {
    window.location.href = "https://www.ayyyyymc.bet/"; 
  }
  
  function goToGme() {
    window.location.href = "https://www.isgmeup.space/";
  }
</script>

<main>
  <section class="wrapper">
    <div id="stars" />
    <div id="stars2" />
    <div id="stars3" />
    <div id="title">
      <span>BUDZISZEK</span>
      <br />
      <span>(BUD-ziz-ek)</span>
      <br />
      <div class="nameplate">
        <span class="small link" on:click={goToLinkedIn}>LinkedIn</span>
        <span class="small">|</span>
        <span class="small link" on:click={goToGitHub}>GitHub</span>
        <span class="small">|</span>
        <span class="small link" on:click={goToTwitter}>Twitter</span>
      </div>
      <span class="small link" on:click={openEmail}>andrew@budziszek.com</span> <br/>
      <span class="small link" on:click={goToayyyymc}>ayyyyymc.bet</span>
      <span class="small">|</span>
      <span class="small link" on:click={goToGme}>isgmeup.space</span>
    </div>
  </section>
</main>
