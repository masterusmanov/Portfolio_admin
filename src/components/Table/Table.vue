<template>
    
<div class="tables relative overflow-x-auto">
    <table class="w-full text-sm text-left text-black dark:text-gray-400">
        <thead class="text-md font-bold uppercase text-black bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
            <tr>
                <th scope="col" class="px-6 py-3">
                    ID
                </th>
                <th scope="col" class="px-6 py-3">
                    Users
                </th>
                <th scope="col" class="px-6 py-3">
                    Comments
                </th>
                <th scope="col" class="px-6 py-3">
                    Action
                </th>
            </tr>
        </thead>
        <tbody>
            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700">
                <th scope="row" class="px-6 py-4 font-bold text-gray-900 whitespace-nowrap dark:text-white">
                   1
                </th>
                <td class="px-6 py-4">
                    Fullname
                </td>
                <td class="px-6 py-4">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim repellendus veniam odio porro adipisci eum sit ad doloribus impedit cum.
                </td>
                <td class="px-6 py-2 flex">
                    <div class="w-6 h-6 py-1 rounded-md bg-red-500 mr-4 cursor-pointer">
                        <i class="bx bx-trash text-white text-[16px] flex items-center justify-center"></i>
                    </div>
                    <div class="w-6 h-6 py-1 rounded-md bg-blue-500 mr-4 cursor-pointer">
                        <i class="bx bx-task text-white text-[16px] flex items-center justify-center"></i>
                    </div>
                </td>
            </tr>
            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700">
                <th scope="row" class="px-6 py-4 font-bold text-gray-900 whitespace-nowrap dark:text-white">
                   2
                </th>
                <td class="px-6 py-4">
                    Fullname
                </td>
                <td class="px-6 py-4">
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ea, officiis molestias totam quaerat accusamus assumenda temporibus? Deserunt expedita sit exercitationem veritatis dolor beatae est, quidem nihil obcaecati deleniti aliquam ab.
                </td>
                <td class="px-6 py-2 flex">
                    <div class="w-6 h-6 py-1 rounded-md bg-red-500 mr-4 cursor-pointer">
                        <i class="bx bx-trash text-white text-[16px] flex items-center justify-center"></i>
                    </div>
                    <div class="w-6 h-6 py-1 rounded-md bg-blue-500 mr-4 cursor-pointer">
                        <i class="bx bx-task text-white text-[16px] flex items-center justify-center"></i>
                    </div>
                </td>
            </tr>
            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700">
                <th scope="row" class="px-6 py-4 font-bold text-gray-900 whitespace-nowrap dark:text-white">
                   3
                </th>
                <td class="px-6 py-4">
                    Fullname
                </td>
                <td class="px-6 py-4">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate commodi a beatae, ipsum molestias velit excepturi. Sint praesentium, beatae aut eaque nesciunt nulla quas facilis in vero molestiae eius porro voluptates minus debitis quo vel maiores eos blanditiis laudantium quae.
                </td>
                <td class="px-6 py-2 flex">
                    <div class="w-6 h-6 py-1 rounded-md bg-red-500 mr-4 cursor-pointer">
                        <i class="bx bx-trash text-white text-[16px] flex items-center justify-center"></i>
                    </div>
                    <div class="w-6 h-6 py-1 rounded-md bg-blue-500 mr-4 cursor-pointer">
                        <i class="bx bx-task text-white text-[16px] flex items-center justify-center"></i>
                    </div>
                </td>
            </tr>
        </tbody>
    </table>
</div>

</template>
  
  <script setup></script>
  
  <style lang="scss" scoped>
@media (max-width: 767px) {
    .tables{
        display: none;
    }    
}
</style>
  