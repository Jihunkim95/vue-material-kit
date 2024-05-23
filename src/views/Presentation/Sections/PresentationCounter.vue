<script setup>
import DefaultCounterCard from "../../../examples/cards/counterCards/DefaultCounterCard.vue";
</script>

<template>
  <section class="pt-3 pb-4" id="count-stats">
    <div class="container">
      <div class="row">
        <div class="col-lg-9 z-index-2 border-radius-xl mx-auto py-3">
          <div class="row">
            <div class="col-md-4 position-relative">
              <DefaultCounterCard
                color="success"
                title="신뢰"
                description="프로젝트의 시작부터 끝까지 대표가 기획하고 코딩합니다. 12곳 이상의 회사에 솔루션을 제공하였습니다."
                :count="12"
                suffix="+"
                :duration="3000"
                divider="vertical"
              />
            </div>
            <div class="col-md-4 position-relative">
              <DefaultCounterCard
                color="success"
                title="고객 중심"
                description="고객의 목소리에 귀 기울이고, 최상의 솔루션을 제공합니다. 100명이상의 고객이 플랫폼로직스가 제공하는 앱을 사용하고 있습니다."
                :count="100"
                suffix="+"
                :duration="3000"
                divider="vertical"
              />
            </div>
            <div class="col-md-4">
              <DefaultCounterCard
                color="success"
                title="열정"
                description="모든 일에 열정을 가지고 임하며, 최선을 다해 목표를 달성합니다."
                :count="99"
                suffix="%"
                :duration="3000"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
