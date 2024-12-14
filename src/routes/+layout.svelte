<nav>
    <a href="/">Home</a>
    <a href="/work">Work</a>
    <a href="/socials">Socials</a>
    <a href="/resume">CV</a>
  </nav>
  
  <main>
    <slot /> <!-- Where the page content will be rendered -->
  </main>
  
  <style>
    nav {
      display: flex;
      gap: 1rem;
      background: #4a2020;
      color: white;
      padding: 1rem;
    }
  
    nav a {
      color: white;
      text-decoration: none;
    }
  
    nav a:hover {
      text-decoration: underline;
    }
  
    main {
      padding: 2rem;
    }
  </style>
  