<template>
  <div class="flex items-center justify-center bg-green-100 min-h-screen">
    <div class="bg-white p-8 rounded-lg shadow-md w-full max-w-md">
        <h2 class="text-2l font-bold text-green-800 mb-6 text-center">Register</h2>
        <form class="flex flex-col gap-4">
         <input v-model="name" type="name" placeholder="Full names" class="border border-gray-300 rounded-md py-2 px-4 focus:outline-none focus:ring-2 focus:ring-green-500"/>
         <input v-model="email" type="email" placeholder="Email required" class="border border-gray-300 rounded-md py-2 px-4 focus:outline-none focus:ring-2 focus:ring-green-500"/>
         <input v-model="password" type="password" placeholder="Password required" class="border border-gray-300 rounded-md py-2 px-4 focus:outline-none focus:ring-2 focus:ring-green-500"/>
         <input v-model="number" type="name" placeholder="Your phone number required" class="border border-gray-300 rounded-md py-2 px-4 focus:outline-none focus:ring-2 focus:ring-green-500"/>
         <input v-model="number" type="name" placeholder="Other" class="border border-gray-300 rounded-md py-2 px-4 focus:outline-none focus:ring-2 focus:ring-green-500"/>
         <input v-model="gender" type="gender" placeholder="Gender required" class="border border-gray-300 rounded-md py-2 px-4 focus:outline-none focus:ring-2 focus:ring-green-500"/>
         <input v-model="age" type="number" placeholder="Your age is required" class="border border-gray-300 rounded-md py-2 px-4 focus:outline-none focus:ring-2 focus:ring-green-500"/>
         <input v-model="password" type="password" placeholder="Confirm Password" class="border border-gray-300 rounded-md py-2 px-4 focus:outline-none focus:ring-2 focus:ring-green-500"/>
        </form>
        <p class="text-center text-sm mt-4 text-gray-600">Already have an account? Please login here
        <RouterLink to="/login" class="text-green-700 font-semi-bold hover:underline">Login</RouterLink>
        </p>
    </div>
  </div>  
</template>