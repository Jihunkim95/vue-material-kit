<script setup>
import DefaultReviewCard from "@/examples/cards/reviewCards/DefaultReviewCard.vue";
</script>
<template>
  <section class="py-7">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 mx-auto text-center">
          <h2 class="mb-0">솔루션 및 사용고객</h2>
          <h2 class="text-gradient text-success mb-3">
            100+ 고객
          </h2>
          <p class="lead">
            100명 이상의 고객이 Platform Logics가 제공한 솔루션을 사용중입니다.
          </p>
        </div>
      </div>
      <div class="row mt-6">
        <DefaultReviewCard
          name="배규태"
          date="1일 전"
          review='"훌륭한 제품입니다. 문서도 훌륭하고 작업을 보다 효율적으로 수행하는 데 도움이 되었습니다."'
          :rating="5.0"
        />
        <DefaultReviewCard
          class="ms-md-auto"
          color="bg-gradient-success"
          name="채혜성"
          date="1주 전"
          review='"저렴한 비용에도 불구하고, 원하는 요구사항을 최대한 반영해주려고 했는것을 감사하게 생각합니다."'
          :rating="5.0"
        />

        <DefaultReviewCard
          name="조민정"
          date="3주 전"
          review='"훌룡한 제품입니다. 적극적 그리고 지속적인 협조에 감사드립니다."'
          :rating="5.0"
        />
      </div>
      <!-- <hr class="horizontal dark my-5" />
      <div class="row">
        <div class="col-lg-2 col-md-4 col-6 ms-auto">
          <img
            class="w-100 opacity-6"
            src="@/assets/img/logos/gray-logos/logo-apple.svg"
            alt="Logo"
          />
        </div>
        <div class="col-lg-2 col-md-4 col-6">
          <img
            class="w-100 opacity-6"
            src="@/assets/img/logos/gray-logos/logo-facebook.svg"
            alt="Logo"
          />
        </div>
        <div class="col-lg-2 col-md-4 col-6">
          <img
            class="w-100 opacity-6"
            src="@/assets/img/logos/gray-logos/logo-nasa.svg"
            alt="Logo"
          />
        </div>
        <div class="col-lg-2 col-md-4 col-6 ms-lg-0 ms-md-auto">
          <img
            class="w-100 opacity-6"
            src="@/assets/img/logos/gray-logos/logo-vodafone.svg"
            alt="Logo"
          />
        </div>
        <div class="col-lg-2 col-md-4 col-6 me-md-auto mx-md-0 mx-auto">
          <img
            class="w-100 opacity-6"
            src="@/assets/img/logos/gray-logos/logo-digitalocean.svg"
            alt="Logo"
          />
        </div>
      </div> -->
    </div>
  </section>
</template>
