<script>
export default {
  data() {
    return {
      Title: 'Work Experience',
      jobTitle: 'Front-end Developer'
    }
  }
}
</script>

<template>
  <section class="flex flex-col max-w-8l mx-auto px-6 sm:px-6 w-5/6 max-md:w-full">
    <div class="flex-row max-sm:flex-col">
      <h2 class="text-2xl font-bold text-center p-4">{{ Title }}</h2>
      <h3 class="text-lg py-1.2">
        {{ jobTitle }}@
        <a href="https://www.awaredigital.co.uk/" class="font-bold text-blue-400">Aware Digital</a>
      </h3>
      <ul class="list-disc w-auto px-1">
        <li>August 2021 - July 2022</li>
        <li>
          Working alongside both back-end and front-end developers on upcoming Magento websites.
        </li>
        <li>
          Creating and maintaining large-scale eCommerce websites using Frontend Development tools
          within Magento such as Sass, Phtml, Alpine JS, Hyva and JavaScript.
        </li>
      </ul>
    </div>

    <div class="flex-row max-sm:flex-col pt-5">
      <h3 class="text-lg py-1.2">
        {{ jobTitle }} @
        <a
          href="https://www.sgworld.com/?utm_term=sg%20world&utm_campaign=SG+World+Brand+Advert&utm_source=adwords&utm_medium=ppc&hsa_acc=8938409363&hsa_cam=13257716876&hsa_grp=123538577220&hsa_ad=523866470832&hsa_src=g&hsa_tgt=kwd-322252472350&hsa_kw=sg%20world&hsa_mt=b&hsa_net=adwords&hsa_ver=3&gad=1&gclid=Cj0KCQjw9rSoBhCiARIsAFOiplmwoDGDN_CP416iWGiz0Z0akag5XZkGVqMP8xLG98SYGzYCYf0qAMcaAlDVEALw_wcB"
          class="font-bold text-blue-400"
          >SG World</a
        >
      </h3>
      <ul class="list-disc w-auto px-1">
        <li>February 2023 - Present</li>
        <li>
          Creating and maintaining the overall functionality and styling of the application through
          bug fixes and new features and components.
        </li>
        <li>
          Using front end development tools such as Angular, Native Script, SCSS and Bootstrap.
        </li>
      </ul>
    </div>
  </section>
</template>
