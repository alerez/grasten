<template>
  <main class="page__main main">
    <div class="main__container">
      <div class="main__body">
        <div class="main__description description">
          <div class="description__body">
            <div class="description__title">Надежный дом с <br> плоской крышей <br> « GRASTEN » за 20.16 млн.р.</div>
            <div class="description__button">{{ store.mainData.btn }}</div>
          </div>
        </div>

        <div class="main__download download">
          <div class="download__body">
            <div class="download__text">{{ store.mainData.text }}</div>
            <div class="download__button" @click="store.showModal = true">{{ store.mainData.button }}</div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<script setup>
import { useStore } from '@/store/index';

const store = useStore();
</script>
