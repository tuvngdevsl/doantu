<template>

  <head>
    <title>Kickz X</title>
    <link href="https://cdn.tailwindcss.com/">
    </link>
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&amp;display=swap"
      rel="stylesheet" />
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet" />
  </head>
  <div class="container mx-auto px-6 py-12">
    <!-- Header -->
    <div class="flex justify-between items-center">
      <div class="text-3xl font-bold">
        <i class="fas fa-bars"></i>
      </div>
      <div class="text-3xl font-bold">
        Kick X
      </div>
      <div class="space-x-4 flex items-center">
        <i class="fas fa-search"></i>
        <i class="far fa-heart"></i>
        <i class="fas fa-shopping-bag"></i>
      </div>
    </div>
    <!-- Main Content -->
    <div class="mt-12">
      <!-- Product Tagline -->
      <div class="flex justify-between items-center flex-wrap">
        <div class="text-sm uppercase tracking-widest text-gray-500 mb-2 sm:mb-0">
          Modern
        </div>
        <div class="text-sm uppercase tracking-widest text-gray-500">
          Comfort
        </div>
      </div>
      <h1 class="text-4xl sm:text-5xl md:text-6xl font-bold uppercase mt-4 leading-tight">
        Release Style
        <br class="hidden sm:block" />
        With Confidence
      </h1>
      <p class="text-sm text-gray-500 mt-4">
        Perfect blend of fashion and ease in our comfortable Clothes.
      </p>
      <!-- Product Image -->
      <div class="mt-8">
        <img
          alt="White sneaker with distinctive design and 'STRIPES' text on the heel strap, representing the Kick X brand."
          class="mx-auto" height="auto" src="/assets/images/logo.jpg" width="auto" />
      </div>
      <!-- Brands -->
      <div class="flex justify-between items-center mt-8 gap-8">
        <span class="text-3xl font-bold mb-2 ">
          Brands
        </span>
        <div class="grid grid-cols-3 md:grid-cols-3 gap-3 w-auto">
          <a href="https://zalo.me/{your_oa_id}">
            <img src="/assets/images/adidas.jpg" alt="zalo" class="w-[50px]" />
          </a>
          <a href="skype:live:.cid.8fbff0363ff1492a?chat">
            <img src="/assets/images/nike.jpg" alt="skype" class="w-[70px]" />
          </a>
          <a href="https://line.me/R/ti/p/bboyfinger123">
            <img src="/assets/images/puma.jpg" alt="line" class="w-[70px]" />
          </a>
        </div>
      </div>
    </div>
    <!-- Popular Collections -->
    <div class="container mx-auto px-4 py-8">
      <h2 class="text-4xl font-bold mb-2">
        Popular Collections
      </h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-2 gap-4">
        <!-- First Product -->
        <div class="relative">
          <img alt="Nike Air Max 270 React in blue and red with a white sole" src="/assets/images/anh1.jpg"
            class="mb-1 w-full" />
          <button class="absolute top-10 right-3 bg-black text-white p-2 rounded-full text-xs">
            <i class="fas fa-heart"></i>
          </button>
          <div class="absolute bottom-0 left-0 bg-gray-800 bg-opacity-40 p-1 w-full">
            <div class="flex justify-center space-x-20">
              <h3 class="text-lg font-semibold text-white">
                Nike Air Max 270 React
              </h3>
              <p class="text-gray-300 mt-1">
                $210.00
              </p>
            </div>
          </div>
        </div>
        <!-- Second Product -->
        <div class="relative">
          <img alt="Nike Air Max 270 React in blue and red with a white sole" src="/assets/images/anh2.jpg"
            class="mb-1 w-full" />
          <button class="absolute top-10 right-3 bg-black text-white p-2 rounded-full text-xs">
            <i class="fas fa-heart"></i>
          </button>
          <div class="absolute bottom-0 left-0 bg-gray-800 bg-opacity-40 p-1 w-full">
            <div class="flex justify-center space-x-20">
              <h3 class="text-lg font-semibold text-white">
                Nike Air Max 270 React
              </h3>
              <p class="text-gray-300 mt-1">
                $210.00
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Trending Now -->
    <div class="container mx-auto px-4 py-5">
      <h1 class="text-4xl font-bold mb-2">
        Trending Now
      </h1>
      <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mb-2 w-full">
        <div class="relative">
          <img src="/assets/images/anh5.jpg" alt="Mô tả ảnh" class="mb-4 w-full h-auto">
          <div class="absolute inset-0 flex items-center justify-center">
            <h1 class="text-2xl text-black font-bold absolute bottom-12  right-2/3 ">Jordan Dior</h1>
          </div>
        </div>
        <div class="relative">
          <img src="/assets/images/anh5.jpg" alt="Mô tả ảnh" class="mb-4 w-full h-auto">
          <div class="absolute inset-0 flex items-center justify-center">
            <h1 class="text-2xl text-black font-bold absolute bottom-12 right-2/3 ">Jordan Dior</h1>
          </div>
        </div>
      </div>
    </div>
    <!-- All Collections -->
    <div class="container mx-auto px-6 py-10">
      <div class="mb-8">
        <h2 class="text-4xl font-bold mb-2 h-auto ">
          All Collections
        </h2>
        <p class="text-right ">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit.<br>
          Quis cumque culpa nobis fugiat impedit provident.
        </p>
      </div>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
        <!-- Product 1 -->
        <div class="border rounded-lg p-4 flex flex-col items-center">
          <img alt="Placeholder image of Nike Air Max React in blue and red" class="mb-3" height="150"
            src="/assets/images/anh3.jpg" width="215" />
          <h3 class="text-lg font-semibold mb-2">
            Nike Air Max React
          </h3>
          <span class="text-gray-500 mb-4">
            $299.00
          </span>
          <button
            class="border rounded-full px-6 py-2 text-sm font-semibold text-gray-500 hover:border-gray-700 hover:text-gray-700">
            Add to Cart
          </button>
        </div>
        <!-- Product 2 -->
        <div class="border rounded-lg p-4 flex flex-col items-center">
          <img alt="Placeholder image of Nike Air Zoom Pegasus in red and black" class="mb-3" height="150"
            src="/assets/images/anh4.jpg" width="250" />
          <h3 class="text-lg font-semibold mb-2">
            Nike Air Zoom Pegasus
          </h3>
          <span class="text-gray-500 mb-4">
            $199.00
          </span>
          <button
            class="border rounded-full px-6 py-2 text-sm font-semibold text-gray-500 hover:border-gray-700 hover:text-gray-700">
            Add to Cart
          </button>
        </div>
        <!-- Product 3 -->
        <div class="border rounded-lg p-4 flex flex-col items-center">
          <img alt="Placeholder image of Nike Air Max Plus in white and blue" class="mb-3"
            src="/assets/images/anh10.jpg" width="230" />
          <h3 class="text-lg font-semibold mb-2">
            Nike Air Max Plus
          </h3>
          <span class="text-gray-500 mb-4">
            $249.00
          </span>
          <button
            class="border rounded-full px-6 py-2 text-sm font-semibold text-gray-500 hover:border-gray-700 hover:text-gray-700">
            Add to Cart
          </button>
        </div>
        <!-- Product 4 -->
        <div class="border rounded-lg p-4 flex flex-col items-center">
          <img alt="Placeholder image of Adidas Ultraboost in white" class="mb-3" height="200"
            src="/assets/images/anh6.jpg" width="260" />
          <h3 class="text-lg font-semibold mb-2">
            Adidas Ultraboost
          </h3>
          <span class="text-gray-500 mb-4">
            $180.00
          </span>
          <button
            class="border rounded-full px-6 py-2 text-sm font-semibold text-gray-500 hover:border-gray-700 hover:text-gray-700">
            Add to Cart
          </button>
        </div>
        <!-- Product 5 -->
        <div class="border rounded-lg p-4 flex flex-col items-center">
          <img alt="Placeholder image of Adidas NMD R1 in black and red" class="mb-3" height="150"
            src="/assets/images/anh7.jpg" width="170" />
          <h3 class="text-lg font-semibold mb-2">
            Adidas NMD R1
          </h3>
          <span class="text-gray-500 mb-4">
            $130.00
          </span>
          <button
            class="border rounded-full px-6 py-2 text-sm font-semibold text-gray-500 hover:border-gray-700 hover:text-gray-700">
            Add to Cart
          </button>
        </div>
        <!-- Product 6 -->
        <div class="border rounded-lg p-4 flex flex-col items-center">
          <img alt="Placeholder image of Nike Air Max 97 in white" class="mb-3" height="150"
            src="/assets/images/anh8.jpg" width="250" />
          <h3 class="text-lg font-semibold mb-2">
            Nike Air Max 97
          </h3>
          <span class="text-gray-500 mb-4">
            $160.00
          </span>
          <button
            class="border rounded-full px-6 py-2 text-sm font-semibold text-gray-500 hover:border-gray-700 hover:text-gray-700">
            Add to Cart
          </button>
        </div>
      </div>
      <div class="text-center mt-8">
        <button class="bg-black text-white rounded-full px-8 py-3 font-semibold">
          BROWSE ALL PRODUCTS
        </button>
      </div>
    </div>
    <!-- Our Showrooms -->
    <div class="container mx-auto px-4 py-8">
      <h1 class="text-4xl font-bold mb-6">
        Our Showrooms
      </h1>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-8">
        <div class="relative">
          <img src="https://demoda.vn/wp-content/uploads/2022/01/tai-anh-dong-de-thuong-1.gif" alt="Mô tả ảnh"
            class="mb-4 w-full h-auto">
          <div class="absolute inset-0 flex items-center justify-center">
            <h1 class="text-3xl text-black font-bold absolute bottom-6 right-1/2 ">Chữ muốn chèn vào ảnh</h1>
          </div>
        </div>
        <div class="relative">
          <img src="https://antimatter.vn/wp-content/uploads/2022/06/hinh-anh-dong-tinh-yeu.gif" alt="Mô tả ảnh"
            class="mb-4 w-full h-auto">
          <div class="absolute inset-0 flex items-center justify-center">
            <h1 class="text-3xl text-black font-bold absolute bottom-6 right-1/2 ">Chữ muốn chèn vào ảnh</h1>
          </div>
        </div>
      </div>
      <div class="bg-gray-800 p-8 text-center">
        <h2 class="text-3xl font-bold mb-4">
          Become a Member
        </h2>
        <p class="text-sm mb-6">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et
          dolore magna aliqua.
        </p>
        <button class="bg-black text-white px-6 py-2">
          JOIN NOW
        </button>
      </div>
      <!-- Footer -->
      <footer class="text-gray-600 text-sm mt-8">
        <!-- Newsletter Section -->
        <div class="flex justify-between items-center border-t border-gray-700 pt-4">
          <div>
            <p>
              Stay up for our newsletter offers
            </p>
            <form class="flex mt-2">
              <input class="p-2 bg-gray-800 text-white mr-2" placeholder="Enter your email" type="email" />
              <button class="bg-blue-800 text-white px-4 py-2" type="submit">
                Subscribe
              </button>
            </form>
          </div>
          <!-- Social Media Icons -->
          <div class="flex">
            <a class="mr-4" href="#">
              <i class="fab fa-facebook-f"></i>
            </a>
            <a class="mr-4" href="#">
              <i class="fab fa-twitter"></i>
            </a>
            <a class="mr-4" href="#">
              <i class="fab fa-instagram"></i>
            </a>
          </div>
        </div>
        <!-- Footer Links -->
        <div class="grid grid-cols-3 gap-4 mt-4">
          <div>
            <h3 class="font-semibold mb-2">
              Links
            </h3>
            <ul>
              <li class="mb-1">
                Home
              </li>
              <li class="mb-1">
                Blog
              </li>
              <li class="mb-1">
                Category
              </li>
            </ul>
          </div>
          <div>
            <h3 class="font-semibold mb-2">
              Features
            </h3>
            <ul>
              <li class="mb-1">
                About Us
              </li>
              <li class="mb-1">
                Catalog
              </li>
              <li class="mb-1">
                Contact Us
              </li>
            </ul>
          </div>
          <div>
            <h3 class="font-semibold mb-2">
              Company
            </h3>
            <ul>
              <li class="mb-1">
                Privacy Policy
              </li>
              <li class="mb-1">
                Terms
              </li>
              <li class="mb-1">
                Security
              </li>
            </ul>
          </div>
        </div>
        <!-- Copyright -->
        <p class="text-center mt-4">
          © 2023 KICKS, All rights reserved.
        </p>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'RELEASE STYLE\nWITH CONFIDENCE'
    }
  }
}
</script>

<style scoped>
body {
  font-family: 'Open Sans', sans-serif;
}
</style>