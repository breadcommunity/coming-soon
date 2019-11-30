<template>
  <Layout>
    <main>
      <section class="container mx-auto px-4 mb-8">
        <h3>Submit a Project</h3>
        <p>To kickstart the platform, we need a bunch of projects ready and raring to go when we launch. Why not submit your project now and we'll get back to you?</p>
        <form action="https://getform.io/f/bb02ba2f-cd66-4720-9f2f-ae07012efaef" method="POST">
          <div class="field">
            <label for="project-name" class="required">Project Name</label>
            <input id="project-name" required="true" type="text" name="project-name" />
          </div>
          <div class="field">
            <label for="email" class="required">Email Address</label>
            <input id="email" required="true" type="email" name="email" />
          </div>
          <div class="field">
            <label for="project-link">Link (e.g. Website/Instagram)</label>
            <input id="project-link" type="text" name="project-link" />
          </div>
          <div class="field">
            <label for="project-description" class="required">Short Description <span class="text-xs font-medium">({{ 240 - description.length }} characters)</span></label>
            <textarea id="project-description" name="project-description" required="true" maxlength="240" v-model="description" class="h-32"></textarea>
          </div>
          <div class="field pt-2">
            <input type="submit" value="Submit" class="bg-purple-500 text-white border-none" />
          </div>
        </form>
      </section>
    </main>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Submit a Project'
  },
  data() {
    return {
      description: ''
    }
  }
}
</script>


<style>
label {
  @apply block font-bold text-gray-700 mb-1;
}

input, textarea {
  @apply w-full text-lg px-2 py-2 border-4 border-gray-200 rounded;
}

.field {
  @apply mb-4;
}

.required:after {
  content: " * ";
  display: inline;
  @apply text-red-400 text-sm;
}
</style>