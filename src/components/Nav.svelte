<script>
  export let segment;
</script>

<style>
  nav {
    border-bottom: 1px solid #6b2e6d;
    font-weight: 400;
    padding: 1em 0;
    margin-bottom: 3em;
  }

  ul {
    display: flex;
    margin: 0;
    padding: 0;
  }

  li {
    list-style: none;
    margin-right: 2em;
  }

  a {
    text-decoration: none;
    padding: 0.5em 1em;
    border-radius: 0.5em;
  }

  [aria-current] {
    background-color: #6b2e6d;
    color: white;
  }

  a:hover {
    background-color: #6b2e6d;
    color: white;
  }

  @media screen and (max-width: 800px) {
    ul {
      justify-content: center;
    }
  }
</style>

<nav>
  <ul>
    <li>
      <a aria-current={segment === undefined ? 'page' : undefined} href=".">
        Om mig
      </a>
    </li>
    <li>
      <a aria-current={segment === 'tech' ? 'page' : undefined} href="tech">
        Tech
      </a>
    </li>
  </ul>
</nav>
