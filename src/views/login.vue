<template>
  <div class="flex items-center justify-center bg-green-100 min-h-screen">
    <div class="bg-white p-8 rounded-lg shadow-md w-full max-w-md">
        <h2 class="text-2l font-bold text-green-800 mb-6 text-center">Login In</h2>
        <form class="flex flex-col gap-4">
         <input v-model="email" type="email" placeholder="Email required" class="border border-gray-300 rounded-md py-2 px-4 focus:outline-none focus:ring-2 focus:ring-green-500"/>
         <input v-model="password" type="password" placeholder="Password required" class="border border-gray-300 rounded-md py-2 px-4 focus:outline-none focus:ring-2 focus:ring-green-500"/>
        <button type = "submit"
        class="bg-green-800 text-white py-2 rounded hover:bg-green-700-semibold">Sign In</button>
        </form>
        <p class="text-center text-sm mt-4 text-gray-600">Don't have an account? Please create it here 
        <RouterLink to="/register" class="text-green-700 font-semi-bold hover:underline">Register</RouterLink>
        </p>
    </div>
  </div>  
</template>