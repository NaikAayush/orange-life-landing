<template>
  <section>
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="py-12 md:py-20 border-t border-gray-800">

        <!-- Section header -->
        <div class="max-w-3xl mx-auto text-center pb-12 md:pb-20">
          <h2 class="h2 mb-4">Open, to anyone and everyone</h2>
          <p class="text-xl text-gray-400">The Orange Life platform is open to everyone in the world with internet access, regardless of their country, gender identity or religious beliefs.</p>
        </div>

        <!-- Articles -->
        <div class="max-w-sm mx-auto grid gap-8 md:grid-cols-3 md:gap-6 lg:gap-6 items-start md:max-w-none">

          <!-- 1st article -->
          <article class="flex flex-col h-full" data-aos="fade-up">
            <a class="block" href="https://github.com/orange-life">
              <figure class="relative h-0 pb-9/16 overflow-hidden">
                <img class="absolute inset-0 w-full h-full object-cover transform hover:scale-105 transition duration-700 ease-out" src="../images/open-source.png" width="352" height="198" alt="News 10" />
                <figcaption class="absolute top-0 right-0 mt-4 mr-4 text-xs font-medium inline-flex text-center text-gray-100 py-1 px-3 rounded-full bg-gray-900 bg-opacity-75 pointer-events-none" href="https://github.com/orange-life">GitHub</figcaption>
              </figure>
            </a>
            <div class="flex-grow flex flex-col h-full p-6 bg-gray-800">
              <h3 class="h4 mb-2">
                <a class="hover:text-gray-100 transition duration-150 ease-in-out" href="https://github.com/orange-life">Open Source</a>
              </h3>
              <p class="text-lg text-gray-400 flex-grow">All of the code and tools used in Orange Life are open source. This means any experts can verify the code used to secure your records.</p>
              <div>
                <a class="btn-sm text-white bg-purple-600 hover:bg-purple-700 mt-6" href="https://github.com/orange-life">
                  <span class="text-sm">GitHub Organization</span>
                  <svg class="w-3 h-3 fill-current text-purple-400 flex-shrink-0 ml-2" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                    <path d="M6 5H0v2h6v4l6-5-6-5z" />
                  </svg>
                </a>
              </div>
            </div>
          </article>

          <!-- 2nd article -->
          <article class="flex flex-col h-full" data-aos="fade-up" data-aos-delay="200">
            <a class="block" href="https://life.theorange.network/">
              <figure class="relative h-0 pb-9/16 overflow-hidden">
                <img class="absolute inset-0 w-full h-full object-cover transform hover:scale-105 transition duration-700 ease-out" src="../images/news-11.jpg" width="352" height="198" alt="News 11" />
                <figcaption class="absolute top-0 right-0 mt-4 mr-4 text-xs font-medium inline-flex text-center text-gray-100 py-1 px-3 rounded-full bg-gray-900 bg-opacity-75 pointer-events-none" href="https://life.theorange.network/">Website</figcaption>
              </figure>
            </a>
            <div class="flex-grow flex flex-col h-full p-6 bg-gray-800">
              <h3 class="h4 mb-2">
                <a class="hover:text-gray-100 transition duration-150 ease-in-out" href="https://life.theorange.network/">Open Platform</a>
              </h3>
              <p class="text-lg text-gray-400 flex-grow">No login or signup is required. Just generate a key and get started. No KYC, no forms, no personal data is collected.</p>
              <div>
                <a class="btn-sm text-white bg-purple-600 hover:bg-purple-700 mt-6" href="https://life.theorange.network/">
                  <span class="text-sm">Get Started</span>
                  <svg class="w-3 h-3 fill-current text-purple-400 flex-shrink-0 ml-2" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                    <path d="M6 5H0v2h6v4l6-5-6-5z" />
                  </svg>
                </a>
              </div>
            </div>
          </article>

          <!-- 3rd article -->
          <article class="flex flex-col h-full" data-aos="fade-up" data-aos-delay="400">
            <a class="block" href="https://devfolio.co/submissions/orange-life-af3a">
              <figure class="relative h-0 pb-9/16 overflow-hidden">
                <img class="absolute inset-0 w-full h-full object-cover transform hover:scale-105 transition duration-700 ease-out" src="../images/news-12.jpg" width="352" height="198" alt="News 12" />
                <figcaption class="absolute top-0 right-0 mt-4 mr-4 text-xs font-medium inline-flex text-center text-gray-100 py-1 px-3 rounded-full bg-gray-900 bg-opacity-75 pointer-events-none" href="https://devfolio.co/submissions/orange-life-af3a">Devfolio</figcaption>
              </figure>
            </a>
            <div class="flex-grow flex flex-col h-full p-6 bg-gray-800">
              <h3 class="h4 mb-2">
                <a class="hover:text-gray-100 transition duration-150 ease-in-out" href="https://devfolio.co/submissions/orange-life-af3a">Support us!</a>
              </h3>
              <p class="text-lg text-gray-400 flex-grow">You can show support for us by liking and comment on our Devfolio submission, for the EthOdyssey online hackathon.</p>
              <div>
                <a class="btn-sm text-white bg-purple-600 hover:bg-purple-700 mt-6" href="https://devfolio.co/submissions/orange-life-af3a">
                  <span class="text-sm">Show support</span>
                  <svg class="w-3 h-3 fill-current text-purple-400 flex-shrink-0 ml-2" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                    <path d="M6 5H0v2h6v4l6-5-6-5z" />
                  </svg>
                </a>
              </div>
            </div>
          </article>

        </div>

      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'CaseStudies'
}
</script>
