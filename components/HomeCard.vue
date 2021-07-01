<!--<template>
    <div class="w-full h-96 bg-yellow-300">
        <div class="text-white text-left ml-8 mt-5">
            <div class="font-bold text-2xl">
            {{ title }}
            </div>
            <div class="text-md font-light mr-32">
            {{ description }}
            </div>
            <button class="absolute text-sm px-7 py-3 mt-5 rounded-md font-semibold tracking-wide bg-white text-blue-700">
                Mulai Belajar
            </button>
        </div>
    </div>
</template> -->

<template>
  <nav class="navbar navbar-expand-lg navbar-dark">
    <a class="navbar-brand" href="#">KetahUIparkir</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo01"
      aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="/">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/faq">FAQ</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/contact-us">Contact Us</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'HomeCard'
/* name: 'HomeCard',
  props: {
    title: {
      type: String,
    },
    description: {
      type: String,
    }
  } */
}
</script>