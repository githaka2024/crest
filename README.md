<img src="./dump/svg/dark.svg" alt="Logo" style="display: block;" id="logo-dark">
<img src="./dump/svg/light.svg" alt="Logo" style="display: none;" id="logo-light">

<script>
  const darkModeMediaQuery = window.matchMedia('(prefers-color-scheme: dark)');
  const logoDark = document.getElementById('logo-dark');
  const logoLight = document.getElementById('logo-light');

  function updateLogo(e) {
    if (e.matches) {
      logoDark.style.display = 'none';
      logoLight.style.display = 'block';
    } else {
      logoDark.style.display = 'block';
      logoLight.style.display = 'none';
    }
  }

  darkModeMediaQuery.addListener(updateLogo);
  updateLogo(darkModeMediaQuery);
</script>

When diving into web development or tackling practice projects, having a polished logo can make a significant impact, even if the project doesn't see the light of day. Crest delivers a <mark>top-notch logo</mark> to jump-start your project, accompanied by <mark>essential assets</mark> like favicons and PNG files, which are invaluable for crafting progressive web apps. With Crest, you can bypass the headache of logo design and concentrate fully on your development journey.
