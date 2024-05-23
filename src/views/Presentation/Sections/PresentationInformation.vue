<script setup>
import RotatingCard from "../../../examples/cards/rotatingCards/RotatingCard.vue";
import RotatingCardFront from "../../../examples/cards/rotatingCards/RotatingCardFront.vue";
import RotatingCardBack from "../../../examples/cards/rotatingCards/RotatingCardBack.vue";
import DefaultInfoCard from "../../../examples/cards/infoCards/DefaultInfoCard.vue";
</script>
<template>
  <section class="my-5 py-5">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-lg-4 ms-auto me-auto p-lg-4 mt-lg-0 mt-4">
          <RotatingCard>
            <RotatingCardFront
              image="https://images.unsplash.com/photo-1569683795645-b62e50fbf103?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=987&q=80"
              icon="touch_app"
              title="Platform Logics가 <br /> 제공하는 가치입니다."
              description="프론트, 백엔드, 모바일등의 경계를 없애고 AI시대에 맞춰 성장합니다."
            />

            <RotatingCardBack
              image="https://images.unsplash.com/photo-1498889444388-e67ea62c464b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1365&q=80"
              title="자세한 내용"
              description="ERP, 웹, 모바일 소프트웨어 개발 내역이 그 사실을 증명합니다."
              :action="[
                {
                  route: './/sections/page-sections/hero-sections.html',
                  label: '내역 확인',
                },
              ]"
            />
          </RotatingCard>
        </div>
        <div class="col-lg-6 ms-auto">
          <div class="row justify-content-start">
            <DefaultInfoCard
              icon="content_copy"
              title="문서화"
              description="인수인계를 위해 문서화된 가이드라인을 제공합니다."
            />
            <DefaultInfoCard
              icon="flip_to_front"
              title="유지보수"
              description="계약기간 외에도 지속적인 유지보수로 책임을 다합니다."
            />
          </div>
          <div class="row justify-content-start mt-5">
            <DefaultInfoCard
              class="mt-3"
              icon="price_change"
              title="시간과 비용 절약"
              description="요구사항을 중심으로한 정확하고 효율적인 솔루션으로 시간과 비용을 절약합니다."
            />
            <DefaultInfoCard
              class="mt-3"
              icon="devices"
              title="Web과 Mobile연동"
              description="Web과 Mobile과 연동이 가능한 기술로 생산성을 향상시킵니다."
            />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
