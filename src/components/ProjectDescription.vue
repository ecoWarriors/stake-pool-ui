<script setup lang="ts">
</script>

<template>
  <section class="project-description-section container">
    <div>
      <h4 class="project-title">
        ESG's First Project
      </h4>
      <div>
        <div class="project-thumbnail">
          <img src="@/assets/img/project/thumbnail.png" alt="Project thumbnail">
          <img src="@/assets/img/project/statistics.png" alt="Project statistics">
        </div>
        <div class="project-description">
          <p>
            The septic waste disposal facility in Orlando, Florida is seeking a new environmentally-friendly technology solution for the treatment of septic waste water. NOAH Solutions proposed dehumidification technology will allow for 100% on-site treatment, producing 8% solids for fertilizer and 92% potable water for disposal back into the Florida public water system, eliminating the need for transportation and potential harm to agricultural land
          </p>
          <p>
            The goal of the ESG stake pool is to provide a way for anyone to have targeted environmental impact without the need to donate to a project. With the ESG pool, a small fee is taken initially to fund environmental projects with a high enough yield that stakers are made whole within the first year. Proceeds from the ESG will go directly towards environmental projects being passed through the ecoSystem.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
    .project-thumbnail {
        width: 50%;
        float: right;
        display: block;
        margin-left: 10px;
        margin-bottom: 10px;
    }
    .project-thumbnail img {
        width: 100%;
    }
    .project-title {
        line-height: 0;
        font-weight: 700;
    }
    .project-description-section {
        width: 100%;
    }

    @media only screen and (min-width: 800px) and (max-width: 1000px)  {
        .project-thumbnail {
            width: 62%;
        }
    }

    @media only screen and (max-width: 800px)  {
        .project-thumbnail {
            width: 100%;
            float: left;
            margin-left: 0px;
        }
    }

    /* @media only screen and (min-width: 1100px)  {
        .project-thumbnail {
            width: 50%;
        }
    } */
</style>

