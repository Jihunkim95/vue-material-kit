<script setup>
// example component
import HorizontalTeamCard from "@/examples/cards/teamCards/HorizontalTeamCard.vue";

// images
import emma from "@/assets/img/JhKim-heart.jpeg";
import william from "@/assets/img/JhKim-finger.jpeg";
import ivana from "@/assets/img/JhKim-hello.jpeg";
import marquez from "@/assets/img/JhKim-note.jpeg";
</script>

<template>
  <section class="pb-5 position-relative bg-gradient-dark mx-n3">
    <div class="container">
      <div class="row">
        <div class="col-md-8 text-start mb-5 mt-5">
          <h3 class="text-white z-index-1 position-relative">
            팀 소개
          </h3>
          <p class="text-white opacity-8 mb-0">
            삶에서 하고 싶은 일은 해내는 팀을 소개합니다.
          </p>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-6 col-12">
          <HorizontalTeamCard
            class="mt-4"
            :image="emma"
            :profile="{ name: 'Jihoon Kim', link: 'javascript:;' }"
            :position="{ label: 'Boss', color: 'success' }"
            description="안녕하세요 ! 하고싶고 이루고 싶은게 많은 대표입니다.😆"
          />
        </div>
        <div class="col-lg-6 col-12">
          <HorizontalTeamCard
            class="mt-lg-4 mt-5"
            :image="william"
            :profile="{ name: 'Jihoon Kim', link: 'javascript:;' }"
            :position="{ label: 'UI Designer', color: 'success' }"
            description="UI Designer을 맏고 있습니다. 잘 부탁해요 🙌"
          />
        </div>
      </div>
      <div class="row mt-4">
        <div class="col-lg-6 col-12">
          <HorizontalTeamCard
            class="mt-4 z-index-2"
            :image="ivana"
            :profile="{ name: 'Jihoon Kim', link: 'javascript:;' }"
            :position="{ label: 'PM', color: 'success' }"
            description="프로젝트 매니저를 담당하고 있습니다."
          />
        </div>
        <div class="col-lg-6 col-12">
          <HorizontalTeamCard
            class="mt-lg-4 mt-5 z-index-2"
            :image="marquez"
            :profile="{ name: 'Jihoon Kim', link: 'javascript:;' }"
            :position="{ label: 'Developer', color: 'success' }"
            description="개발을 좋아해서 개발을 합니다."
          />
        </div>
      </div>
    </div>
  </section>
</template>
