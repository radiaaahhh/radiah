<template>
  <main>
    <Head>
      <Title>Radiah's Profile</Title>
      <Link rel="icon" href="favicon.png" />
      <Link rel="preconnect" href="https://fonts.googleapis.com" />
      <Link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
      <Link
        href="https://fonts.googleapis.com/css2?family=Zen+Kaku+Gothic+Antique&display=swap"
        rel="stylesheet"
      />
    </Head>

    <img src="image01.jpg" alt="profile picture" />
    <h1>@radiaaahhh</h1>
    <div>
      <p>Radiah#0072 | ラデヤ</p>
      <p>misery incarnate</p>
      <p>a woman by definition but not much</p>
      <p>else if im not rotting im plotting murder</p>
    </div>
    <div>
      <p>said rot:</p>
      <p>
        anime chess, chinese scifi dmc but woman, blue rat, card game show and
        buff gay men having a pose off. have fun guessing that nonsense
      </p>
    </div>

    <NuxtLink
      to="https://twitter.com/radiaaahhh"
      target="_blank"
      class="button"
    >
      Twitter
    </NuxtLink>

    <NuxtLink
      to="https://instagram.com/radiaaahhh"
      target="_blank"
      class="button"
    >
      Instagram
    </NuxtLink>
  </main>
</template>

<style>
html,
body,
#__nuxt {
  height: 100%;
  margin: 0;
  padding: 0;
}

body::after {
  content: "";
  background: url("background.jpg");
  opacity: 0.8;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  position: absolute;
  z-index: -1;
  background-position: center;
}

#__nuxt {
  display: flex;
  align-items: center;
  justify-content: center;
}

main {
  max-width: 500px;
  color: #fafafa;
  font-family: 'Zen Kaku Gothic Antique', sans-serif;
}

.button {
  display: block;
  padding: 5px;
  background: linear-gradient(to right, #730e2a, #005245);
  margin-bottom: 7px;
  color: #fafafa;
  text-align: center;
}
</style>
