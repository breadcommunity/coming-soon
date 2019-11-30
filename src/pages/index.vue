<template>
  <Layout>
    <main>
      <section class="container mx-auto px-4 mb-8">
        <p>Whether you’re creating <u>poetry</u>, <u>clothing</u>, <u>music</u>, <u>apps</u> or <u>running campaigns</u>, <u>hosting events</u> and <u>raising money</u>, share your work with an inspiring and supportive community from around the world.</p>
        <blockquote>Bread is about encouraging the Church to dream big, reach those in need and pioneer change.</blockquote>
      </section>
      <section class="container mx-auto px-4 mb-8">
        <h3>FAQs</h3>
        <details>
          <summary>Who is Bread for?</summary>
          Bread is for <strong>everyone</strong>. Whether you have a project to showcase or not, Bread is for everyone interested in keeping up to date with the latest creative works coming from the Church.
        </details>
        <details>
          <summary>What counts as a Project?</summary>
          Projects can be any idea or piece of creative work. Maybe you’re an entrepreneur building technology for digital evangelism or you're an artist running a faith-based events space. As long as it involves the idea of “creative worship”, it’s a project!        </details>
        </details>
        <details>
          <summary>What doesn't count as a Project?</summary>
          We do not allow for churches or commercial businesses to submit themselves are Projects. Every project is reviewed before it goes live.
        </details>
        <details>
          <summary>How can I get involved?</summary>
          You can keep up to date with us by following us on instagram <a href="https://instagram.com/breadcommunity">@breadcommunity</a>.
          If you’re a developer, designer or interested in marketing and you’d like to help build Bread, get in contact with us at <a href="mailto:hello@bread.community">info@bread.community</a>
        </details>
      </section>
      <section class="container mx-auto px-4 py-8 text-center">
        <g-link to="/submit" class="rounded-full no-underline bg-purple-500 text-white font-bold px-12 py-3 mx-auto">Submit a Project</g-link>
      </section>
    </main>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Coming Soon'
  }
}
</script>

<style>
h2 {
  @apply text-2xl mb-8;
}

h3 {
  @apply text-2xl font-bold mb-4;
}

p {
  @apply text-xl mb-8;
}

blockquote {
  @apply border-l-4 border-purple-400 p-4 pl-6 text-lg mb-4 bg-gray-200;
}

details {
  @apply text-xl mb-4;
}

summary {
  @apply outline-none font-bold;
}

a {
  @apply underline text-purple-600;
}
</style>