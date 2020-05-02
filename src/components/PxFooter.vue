<template>
  <footer class="shadow w-screen">
    <div class="flex items-center justify-center flex-wrap bg-green-400 p-6">
      <p class="copyright font-semibold text-xl">
        <a
          href="https://gomez-fernando.github.io/portfolio/"
          target="_blank"
          rel="noopener noreferrer"
        >Developed with &#x1F49A; by Fernando Gómez &copy; 2020</a>
      </p>
    </div>
  </footer>
</template>

<style>
footer {
  max-width: 100%;
}
.copyright {
  display: flex;
  justify-content: center;
  background-color: var(--oscuro);
  margin: 0 0 0 0;
  text-align: center;
  padding: 1rem;
}

.copyright a {
  text-decoration: none;
  transition: 0.3s ease all;
}

.copyright a:visited {
  color: white;
}

.copyright a:hover {
  text-decoration: none;
  color: yellow;
  margin-left: 10px;
  margin-right: 10px;
  transform: scale(1.1);
}
</style>
