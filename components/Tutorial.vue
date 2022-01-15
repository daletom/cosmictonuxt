<template>
      <div class="mt-12 max-w-lg max-w-md mx-auto grid gap-5 lg:grid-cols-3 md:grid-cols-2 lg:max-w-none md:max-w-none">
        <div v-for="post in data" :key="post.id" class="flex flex-col rounded-lg shadow-lg overflow-hidden">
          <div class="flex-shrink-1">
            <nuxt-img
              class="h-48 w-full object-cover"
              :src="post.metadata.heroimage.imgix_url"
              alt=""
              provider="imgix"
              sizes="xl:413px, lg:50vw, md:448px, sm:900px, xs:90vw)"
              fit="crop"
              :modifiers="{ auto: 'compress', crop: 'faces,entropy', ar: '2.3:1'}"
            />
          </div>
          <div class="flex-1 bg-white p-6 flex flex-col justify-between">
            <div class="flex-1">
                <p class="text-xl font-semibold text-gray-900">
                  {{post.title}}
                </p>
                <p class="mt-3 text-base text-gray-500" v-html="post.content">
                </p>
            </div>
          </div>
        </div>
      </div>
</template>

<script>
export default {
  props: ['data']
}
</script>