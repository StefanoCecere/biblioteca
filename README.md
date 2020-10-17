# biblioteca
un po' di testi interessanti che trovo in giro e che siano riproducibili

se vuoi partecipare, crea una issue o ancora meglio una pull request!


<button class="btn js-toggle-dark-mode">Switch do DARK theme</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'dark') {
    jtd.setTheme('light');
    toggleDarkMode.textContent = 'Switch do DARK theme';
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = 'Switch do LIGHT theme';
  }
});
</script>


Il sito è pubblicato con GitHub Pages e il tema [Just the Docs](https://github.com/pmarsceill/just-the-docs)
