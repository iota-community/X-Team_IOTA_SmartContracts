<style>
  .home-container {
    align-items: center;
    display: flex;
    flex: 1;
    justify-content: center;
    margin: 2em 0;
    min-height: 400px;
  }

  .home-copy {
    flex: 1;
  }

  h1 {
    font-weight: 700;
    margin-bottom: 0.5em;
  }

  p {
    font-size: 1.4em;
    line-height: 1.5;
  }

  figure {
    margin: 0 1em;
    text-align: center;
  }

  img {
    width: 100%;
    max-width: 400px;
  }

  @media (max-width: 1020px) {
    p {
      font-size: 1.2em;
    }

    img {
      max-width: 300px;
    }
  }

  @media (max-width: 800px) {
    .home-container {
      flex-direction: column;
    }

    .home-copy {
      flex: 0;
      padding-bottom: 2em;
      text-align: center;
    }
  }
</style>

<svelte:head>
  <title>IOTA Smart Contracts X-Team</title>
</svelte:head>

<div class="home-container">
  <div class="home-copy">
    <h1>IOTA Smart Contracts X-Team</h1>
    <p>The IOTA Smart Contracts Initiative is a collaborative effort to help people in the IOTA Community by introducing consistent workflows around IOTA ISCP with content, and open source contributions.</p>
  </div>

  <figure>
    <img alt='Person typing on laptop' src='undraw-illustration.svg'>
  </figure>
</div>
