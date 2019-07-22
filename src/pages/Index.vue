<template>
  <Layout>
    
    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <g-image alt="Example image" src="~/assets/headshot-2016.jpg" width="135" quality="100"/>
    
    <p>My name is Taylor, and I am passionate about the visual communication of complex information, especially where it concerns the relationship between people and the environment. I work as User Interface Designer for eBird at the Cornell Lab of Ornithology.</p>

	<p>⚠️ I'm currently rebuilding this site using <a href="https://gridsome.org/" target="_blank" rel="noopener">Gridsome</a>, so it'll be bare bones for for a while. 👋</p>

    <p class="home-links">
      <a href="https://twitter.com/mtaylorlong" target="_blank" rel="noopener">@mtaylorlong</a>
    </p>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Home'
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
