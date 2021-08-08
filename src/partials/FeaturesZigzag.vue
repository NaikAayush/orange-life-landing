<template>
  <section>
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="py-12 md:py-20 border-t border-gray-800">

        <!-- Section header -->
        <div class="max-w-3xl mx-auto text-center pb-12 md:pb-16">
          <div class="inline-flex text-sm font-semibold py-1 px-3 m-2 text-green-600 bg-green-200 rounded-full mb-4">Keep your records to yourself</div>
          <h1 class="h2 mb-4">Secure and Private</h1>
          <!-- <p class="text-xl text-gray-400">Your records are encrypted using <b>state-of-the-art cryptographic methods</b></p> -->
        </div>

        <!-- Items -->
        <div class="grid gap-20">

          <!-- 1st item -->
          <div class="md:grid md:grid-cols-12 md:gap-6 items-center">
            <!-- Image -->
            <div class="max-w-xl md:max-w-none md:w-full mx-auto md:col-span-5 lg:col-span-6 mb-8 md:mb-0 md:order-1" data-aos="fade-up">
              <img class="max-w-full mx-auto md:max-w-none h-auto" src="../images/features-03-image-01.png" width="540" height="405" alt="Features 01" />
            </div>
            <!-- Content -->
            <div class="max-w-xl md:max-w-none md:w-full mx-auto md:col-span-7 lg:col-span-6" data-aos="fade-right">
              <div class="md:pr-4 lg:pr-12 xl:pr-16">
                <div class="font-architects-daughter text-xl text-purple-600 mb-2">More secure. Less concern.</div>
                <h3 class="h3 mb-3">Encrypt your records</h3>
                <p class="text-xl text-gray-400 mb-4">Your records are encrypted using <b>state-of-the-art cryptographic methods</b></p>
                <ul class="text-lg text-gray-400 -mb-2">
                  <li class="flex items-center mb-2">
                    <svg class="w-3 h-3 fill-current text-green-500 mr-2 flex-shrink-0" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                      <path d="M10.28 2.28L3.989 8.575 1.695 6.28A1 1 0 00.28 7.695l3 3a1 1 0 001.414 0l7-7A1 1 0 0010.28 2.28z" />
                    </svg>
                    <span>At first, no one can decrypt it except you</span>
                  </li>
                  <li class="flex items-center mb-2">
                    <svg class="w-3 h-3 fill-current text-green-500 mr-2 flex-shrink-0" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                      <path d="M10.28 2.28L3.989 8.575 1.695 6.28A1 1 0 00.28 7.695l3 3a1 1 0 001.414 0l7-7A1 1 0 0010.28 2.28z" />
                    </svg>
                    <span>Allow family and specific hospitals to view</span>
                  </li>
                  <li class="flex items-center">
                    <svg class="w-3 h-3 fill-current text-green-500 mr-2 flex-shrink-0" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                      <path d="M10.28 2.28L3.989 8.575 1.695 6.28A1 1 0 00.28 7.695l3 3a1 1 0 001.414 0l7-7A1 1 0 0010.28 2.28z" />
                    </svg>
                    <span>Record is encrypted and uploaded only once</span>
                  </li>
                </ul>
              </div>
            </div>
          </div>

          <!-- 2nd item -->
          <div class="md:grid md:grid-cols-12 md:gap-6 items-center">
            <!-- Image -->
            <div class="max-w-xl md:max-w-none md:w-full mx-auto md:col-span-5 lg:col-span-6 mb-8 md:mb-0 md:rtl" data-aos="fade-up">
              <img class="max-w-full mx-auto md:max-w-none h-auto" src="../images/features-03-image-02.png" width="540" height="405" alt="Features 02" />
            </div>
            <!-- Content -->
            <div class="max-w-xl md:max-w-none md:w-full mx-auto md:col-span-7 lg:col-span-6" data-aos="fade-left">
              <div class="md:pl-4 lg:pl-12 xl:pl-16">
                <div class="font-architects-daughter text-xl text-purple-600 mb-2">Access control. Reinvented.</div>
                <h3 class="h3 mb-3">Allow hospitals to view</h3>
                <p class="text-xl text-gray-400 mb-4">Simply scan the hospital's QR code and approve.</p>
                <ul class="text-lg text-gray-400 -mb-2">
                  <li class="flex items-center mb-2">
                    <svg class="w-3 h-3 fill-current text-green-500 mr-2 flex-shrink-0" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                      <path d="M10.28 2.28L3.989 8.575 1.695 6.28A1 1 0 00.28 7.695l3 3a1 1 0 001.414 0l7-7A1 1 0 0010.28 2.28z" />
                    </svg>
                    <span>Only the hospitals you allow can decrypt and view</span>
                  </li>
                  <li class="flex items-center mb-2">
                    <svg class="w-3 h-3 fill-current text-green-500 mr-2 flex-shrink-0" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                      <path d="M10.28 2.28L3.989 8.575 1.695 6.28A1 1 0 00.28 7.695l3 3a1 1 0 001.414 0l7-7A1 1 0 0010.28 2.28z" />
                    </svg>
                    <span>Records cannot be seen unless you allow</span>
                  </li>
                  <li class="flex items-center">
                    <svg class="w-3 h-3 fill-current text-green-500 mr-2 flex-shrink-0" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                      <path d="M10.28 2.28L3.989 8.575 1.695 6.28A1 1 0 00.28 7.695l3 3a1 1 0 001.414 0l7-7A1 1 0 0010.28 2.28z" />
                    </svg>
                    <span>Revoke access anytime</span>
                  </li>
                </ul>
              </div>
            </div>
          </div>

          <!-- 3rd item -->
          <div class="md:grid md:grid-cols-12 md:gap-6 items-center">
            <!-- Image -->
            <div class="max-w-xl md:max-w-none md:w-full mx-auto md:col-span-5 lg:col-span-6 mb-8 md:mb-0 md:order-1" data-aos="fade-up">
              <img class="max-w-full mx-auto md:max-w-none h-auto" src="../images/features-03-image-03.png" width="540" height="405" alt="Features 03" />
            </div>
            <!-- Content -->
            <div class="max-w-xl md:max-w-none md:w-full mx-auto md:col-span-7 lg:col-span-6" data-aos="fade-right">
              <div class="md:pr-4 lg:pr-12 xl:pr-16">
                <div class="font-architects-daughter text-xl text-purple-600 mb-2">Modern signatures.</div>
                <h3 class="h3 mb-3">Sign it</h3>
                <p class="text-xl text-gray-400 mb-4">Every record is signed with a unique key which can be verified to be generated by you.</p>
                <ul class="text-lg text-gray-400 -mb-2">
                  <li class="flex items-center mb-2">
                    <svg class="w-3 h-3 fill-current text-green-500 mr-2 flex-shrink-0" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                      <path d="M10.28 2.28L3.989 8.575 1.695 6.28A1 1 0 00.28 7.695l3 3a1 1 0 001.414 0l7-7A1 1 0 0010.28 2.28z" />
                    </svg>
                    <span>Every record is signed with a different key</span>
                  </li>
                  <li class="flex items-center mb-2">
                    <svg class="w-3 h-3 fill-current text-green-500 mr-2 flex-shrink-0" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                      <path d="M10.28 2.28L3.989 8.575 1.695 6.28A1 1 0 00.28 7.695l3 3a1 1 0 001.414 0l7-7A1 1 0 0010.28 2.28z" />
                    </svg>
                    <span>Verification takes place before downloading</span>
                  </li>
                  <li class="flex items-center">
                    <svg class="w-3 h-3 fill-current text-green-500 mr-2 flex-shrink-0" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                      <path d="M10.28 2.28L3.989 8.575 1.695 6.28A1 1 0 00.28 7.695l3 3a1 1 0 001.414 0l7-7A1 1 0 0010.28 2.28z" />
                    </svg>
                    <span>No one can pretend to be you</span>
                  </li>
                </ul>
              </div>
            </div>
          </div>

        </div>

      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'FeaturesZigzag'
}
</script>
