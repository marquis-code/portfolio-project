<template>
  <div class="relative isolate bg-white mt-10">
    <div class="mx-auto grid max-w-7xl grid-cols-1 lg:grid-cols-2">
      <div class="relative px-6 pb-20 pt-24 sm:pt-32 lg:static lg:px-8 lg:py-48">
        <div class="mx-auto max-w-xl lg:mx-0 lg:max-w-lg">
          <div
            class="absolute inset-y-0 left-0 -z-10 w-full overflow-hidden bg-gray-100 ring-1 ring-gray-900/10 lg:w-1/2">
            <svg
              class="absolute inset-0 h-full w-full stroke-gray-200 [mask-image:radial-gradient(100%_100%_at_top_right,white,transparent)]"
              aria-hidden="true">
              <defs>
                <pattern id="83fd4e5a-9d52-42fc-97b6-718e5d7ee527" width="200" height="200" x="100%" y="-1"
                  patternUnits="userSpaceOnUse">
                  <path d="M130 200V.5M.5 .5H200" fill="none" />
                </pattern>
              </defs>
              <rect width="100%" height="100%" stroke-width="0" fill="white" />
              <svg x="100%" y="-1" class="overflow-visible fill-gray-50">
                <path d="M-470.5 0h201v201h-201Z" stroke-width="0" />
              </svg>
              <rect width="100%" height="100%" stroke-width="0" fill="url(#83fd4e5a-9d52-42fc-97b6-718e5d7ee527)" />
            </svg>
          </div>
          <h2 data-aos="flip-left" class="text-3xl font-bold tracking-tight text-gray-900">Get in touch</h2>
          <p data-aos="flip-left" class="mt-6 text-lg leading-8 text-gray-600">I'd love to hear from you, let's build
            something amazing
            together.</p>
          <dl class="mt-10 space-y-4 text-base leading-7 text-gray-600">
            <div class="flex gap-x-4">
              <dt class="flex-none">
                <span data-aos="flip-left" class="sr-only">Address</span>
                <svg class="h-7 w-6 text-gray-400" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                  stroke="currentColor" aria-hidden="true">
                  <path stroke-linecap="round" stroke-linejoin="round"
                    d="M2.25 21h19.5m-18-18v18m10.5-18v18m6-13.5V21M6.75 6.75h.75m-.75 3h.75m-.75 3h.75m3-6h.75m-.75 3h.75m-.75 3h.75M6.75 21v-3.375c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21M3 3h12m-.75 4.5H21m-3.75 3.75h.008v.008h-.008v-.008zm0 3h.008v.008h-.008v-.008zm0 3h.008v.008h-.008v-.008z" />
                </svg>
              </dt>
              <dd data-aos="flip-left">Lagos, Nigeria.</dd>
            </div>
            <div class="flex gap-x-4">
              <dt class="flex-none">
                <span class="sr-only">Telephone</span>
                <svg class="h-7 w-6 text-gray-400" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                  stroke="currentColor" aria-hidden="true">
                  <path stroke-linecap="round" stroke-linejoin="round"
                    d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z" />
                </svg>
              </dt>
              <dd><a class="hover:text-gray-900" href="tel:+2348147626503">+234 814-762-6503</a></dd>
            </div>
            <div class="flex gap-x-4">
              <dt class="flex-none">
                <span class="sr-only">Email</span>
                <svg class="h-7 w-6 text-gray-400" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                  stroke="currentColor" aria-hidden="true">
                  <path stroke-linecap="round" stroke-linejoin="round"
                    d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75" />
                </svg>
              </dt>
              <dd><a class="hover:text-gray-900" href="mailto:abahmarquis@gmail.com">abahmarquis@gmail.com</a></dd>
            </div>
          </dl>
        </div>
      </div>
      <form @submit.prevent="handleSubmit" class="px-6 pb-24 pt-20 sm:pb-32 lg:px-8 lg:py-48"
      data-aos="fade-up">
      <div class="mx-auto max-w-xl lg:mr-0 lg:max-w-lg">
          <div class="grid grid-cols-1 gap-x-8 gap-y-6 sm:grid-cols-2">
              <div>
                  <label for="first-name"
                      class="block text-sm font-semibold leading-6 text-gray-900">First
                      name</label>
                  <div class="mt-2.5">
                      <input type="text" v-model="formData.firstName" name="first-name" id="first-name"
                          autocomplete="given-name"
                          class="block w-full rounded-md border-[0.6px] border-gray-600 px-3.5 py-3 text-gray-900 shadow-sm placeholder:text-gray-400 sm:text-sm sm:leading-6">
                  </div>
              </div>
              <div>
                  <label for="last-name" class="block text-sm font-semibold leading-6 text-gray-900">Last
                      name</label>
                  <div class="mt-2.5">
                      <input type="text" v-model="formData.lastName" name="last-name" id="last-name"
                          autocomplete="family-name"
                          class="block w-full rounded-md border-[0.6px] border-gray-600 px-3.5 py-3 text-gray-900 shadow-sm placeholder:text-gray-400 sm:text-sm sm:leading-6">
                  </div>
              </div>
              <div class="sm:col-span-2">
                  <label for="email"
                      class="block text-sm font-semibold leading-6 text-gray-900">Email</label>
                  <div class="mt-2.5">
                      <input type="email" v-model="formData.email" name="email" id="email"
                          autocomplete="email"
                          class="block w-full rounded-md border-[0.6px] border-gray-600 px-3.5 py-3 text-gray-900 shadow-sm placeholder:text-gray-400 sm:text-sm sm:leading-6">
                  </div>
              </div>
              <div class="sm:col-span-2">
                  <label for="phone-number"
                      class="block text-sm font-semibold leading-6 text-gray-900">Phone
                      number</label>
                  <div class="mt-2.5">
                      <input type="tel" v-model="formData.phoneNumber" name="phone-number"
                          id="phone-number" autocomplete="tel"
                          class="block w-full rounded-md border-[0.6px] border-gray-600 px-3.5 py-3 text-gray-900 shadow-sm placeholder:text-gray-400 sm:text-sm sm:leading-6">
                  </div>
              </div>
              <div class="sm:col-span-2">
                  <label for="message" class="block text-sm font-semibold leading-6 text-gray-900">Tell us
                      more about your project</label>
                  <div class="mt-2.5">
                      <textarea name="message" v-model="formData.tell_us_more_about_your_project"
                          id="message" rows="4"
                          class="block w-full rounded-md border-[0.6px] border-gray-600 px-3.5 py-3 text-gray-900 shadow-sm placeholder:text-gray-400 sm:text-sm sm:leading-6"></textarea>
                  </div>
              </div>
          </div>
          <div class="mt-8 flex justify-end">
              <button type="submit" :disabled="!isFormEmpty || processing"
                  class="rounded-md bg-indigo-600 disabled:cursor-not-allowed disabled:opacity-25 px-3.5 py-2.5 text-center text-sm font-semibold text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">
                  {{ processing ? 'processing' : 'Send message' }}</button>
          </div>
      </div>
  </form>
    </div>
  </div>

</template>

<script setup lang="ts">
const processing = ref(false)
const formData = ref({
    firstName: '',
    lastName: '',
    email: '',
    phoneNumber: '',
    tell_us_more_about_your_project: ''
});

async function handleSubmit() {
    processing.value = true
    const url = 'https://buildr-backend.onrender.com/api/auth/signup';  // Your API endpoint
    try {
        const response = await fetch(url, {
            method: 'POST',
            headers: {
                'Content-Type': 'application/json'
            },
            body: JSON.stringify(formData.value)
        });

        if (!response.ok) {
            throw new Error('Network response was not ok.');
        }

        const result = await response.json();
        showModal.value = true
        formData.value.firstName = ''
        formData.value.lastName = ''
        formData.value.email = ''
        formData.value.phoneNumber = ''
        formData.value.tell_us_more_about_your_project = ''
        useNuxtApp().$toast.info('Thanks for reaching out. I would revert back to you shortly.');
        
    } catch (error) {
        // if (process.client) {
        //     useNuxtApp().$toast('Error submitting form');
        // }
    } finally {
        processing.value = false
    }
}

const isFormEmpty = computed(() => {
    return !!(formData.value.firstName && formData.value.lastName && formData.value.email && formData.value.phoneNumber && formData.value.tell_us_more_about_your_project)
})

const capitalizeFirstLetter = (string: string) => {
    if (!string) return string; // Handle null, undefined, or empty string
    return string.charAt(0).toUpperCase() + string.slice(1);
}

// nextTick(() => {
//     if (process.client) {
//         useNuxtApp().$toast('notify after nextTick');
//     }
// });

// const notify = () => {
//     useNuxtApp().$toast.error('toastify success');
//     // or
//     // toast.info('toastify success');
// };


const showModal = ref(false);
</script>