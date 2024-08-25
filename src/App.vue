<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class=" bg-gray-300 flex justify-center text-black">
    <div class=" w-96">
      <div class="my-10">
        <img class="w-full h-60" src="" alt="">
        <div class="flex justify-evenly my-10">
          <button class="border-2 border-slate-400 rounded px-3 py-0.5">图片上传</button>
          <button class="border-2 border-slate-400 rounded px-3 py-0.5">图片下载</button>
        </div>
      </div>
      <div>
        <div class="my-8 text-black">
          <span>日期显示：</span> <input type="checkbox">
        </div>
        <div class="my-8">
          <span>时间：</span> <input type="date">
        </div>  
        <div class="my-8">
          <span>运动类型：</span> <input type="date">
        </div>
        <div class="my-8">
          <span>运动时长：</span> <input type="text">
        </div>
        <div class="my-8">
          <span>体重展示：</span> <input type="checkbox">
        </div>
        <div class="my-8">
          <span>体重（kg）：</span> <input type="text">
        </div>
        <button class="border-2 border-slate-400 rounded px-3 py-0.5">生成</button>
      </div>
    </div>
  </div>
</template>

<style scoped>
</style>
