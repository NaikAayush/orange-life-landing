<template>
  <section>
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="pb-12 md:pb-20">

        <!-- Section header -->
        <div class="max-w-3xl mx-auto text-center pb-12 md:pb-16">
          <h1 class="h2 mb-4">Simple and convenient</h1>
          <!-- <p class="text-xl text-gray-400">You <i>do NOT need a blockchain wallet, metamask or any other tool</i> to use Orange Life. All you need to do is remember a friendly mnemonic, in case you need to recover your records. Uploading a record is as easy as selecting the file and clicking a button. Scan QR codes to grant access, just like you would for payments.</p> -->
        </div>

        <div class="grid md:grid-cols-3 bg-gray-800 divide-y md:divide-y-0 md:divide-x divide-gray-700 px-6 md:px-0 md:py-8 text-center">
          <!-- 1st item -->
          <div class="py-6 md:py-0 md:px-8">
            <div class="text-4xl font-bold leading-tight tracking-tighter text-purple-600 mb-2" data-aos="fade-up">No wallets or crypto</div>
            <div class="text-lg text-gray-400" data-aos="fade-up" data-aos-delay="200">You <i>do NOT need a blockchain wallet, metamask or any other tool</i> to use Orange Life.</div>
          </div>
          <!-- 2nd item -->
          <div class="py-6 md:py-0 md:px-8">
            <div class="text-4xl font-bold leading-tight tracking-tighter text-purple-600 mb-2" data-aos="fade-up">Simple mnemonics</div>
            <div class="text-lg text-gray-400" data-aos="fade-up" data-aos-delay="200">All you need to do is remember a friendly mnemonic, in case you need to recover your records.</div>
          </div>
          <!-- 3rd item -->
          <div class="py-6 md:py-0 md:px-8">
            <div class="text-4xl font-bold leading-tight tracking-tighter text-purple-600 mb-2" data-aos="fade-up">Friendly QR Codes</div>
            <div class="text-lg text-gray-400" data-aos="fade-up" data-aos-delay="200">Scan QR codes to grant access, just like you would for payments.</div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Stats'
}
</script>
