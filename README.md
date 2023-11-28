<h1 align="center">Hi 👋, I'm Joaquin David Tiu</h1>
<h3 align="center">A 3rd year CS student</h3>

<img align="right" alt="coding" width="400" src="https://abstracta.us/wp-content/uploads/2018/10/doggy.gif">

<p align="left"> <a href="https://twitter.com/chuuuujd" target="blank"><img src="https://img.shields.io/twitter/follow/chuuuujd?logo=twitter&style=for-the-badge" alt="chuuuujd" /></a> </p>

- 📫 How to reach me **jdavid.tiu@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
  <a href="https://twitter.com/chuuuujd" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="chuuuujd" height="30" width="40" /></a>
  <a href="https://fb.com/https://www.facebook.com/tiuuu.jd/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="https://www.facebook.com/tiuuu.jd/" height="30" width="40" /></a>
  <a href="https://instagram.com/https://www.facebook.com/tiuuu.jd/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="https://www.facebook.com/tiuuu.jd/" height="30" width="40" /></a>
  <a href="https://discord.gg/chuuu1" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="chuuu1" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<!-- Your languages and tools section -->

<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=jdtiu322&show_icons=true&locale=en&layout=compact" alt="jdtiu322" /></p>

---

### Random Quote Generator:
> "Here is a random quote."
fetch('https://api.quotable.io/random')
  .then(response => response.json())
  .then(data => {
    document.querySelector('.quote').innerHTML = `> "${data.content}"<br>- ${data.author}`;
  })
  .catch(error => console.error(error));
