<template>
    <div class="w-full flex flex-col  gap-y-5 lg:flex lg:flex-row items-center justify-between">
      <div class="min-w-0 rounded-lg shadow-xs overflow-hidden bg-gray-500 w-full lg:w-[23%] cursor-pointer">
        <div class="p-4 flex items-center">
          <div class="w-12 h-12 p-3 rounded-full bg-orange-500 mr-4">
            <i class="bx bx-group text-white text-[25px] flex items-center justify-center"></i>
          </div>
          <div>
            <p class="mb-2 text-lg font-medium text-white">Total users</p>
            <p class="text-2xl font-bold text-white">0</p>
          </div>
        </div>
      </div>
  
      <div class="min-w-0 rounded-lg shadow-xs overflow-hidden bg-gray-500 w-full lg:w-[23%] cursor-pointer">
        <div class="p-4 flex items-center">
          <div
            class="w-12 h-12 p-3 rounded-full bg-green-500 mr-4"
          >
            <i
              class="bx bx-brain text-white text-[23px] flex items-center justify-center"
            ></i>
          </div>
          <div>
            <p class="mb-2 text-lg font-medium text-white">
              Total projects
            </p>
            <p class="text-2xl font-bold text-white">0</p>
          </div>
        </div>
      </div>
  
      <div class="min-w-0 rounded-lg shadow-xs overflow-hidden bg-gray-500 w-full lg:w-[23%] cursor-pointer">
        <div class="p-4 flex items-center">
          <div
            class="w-12 h-12 p-3 rounded-full bg-blue-500 mr-4"
          >
          <i class='bx bx-news text-white text-[25px] flex items-center justify-center'></i>
          </div>
          <div>
            <p class="mb-2 text-lg font-medium text-white">
              Comment
            </p>
            <p class="text-2xl font-bold text-white">0</p>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script setup></script>
  
  <style lang="scss" scoped></style>
  