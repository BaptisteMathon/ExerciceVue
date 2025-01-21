<script lang="ts" setup>
import YourProjects from '@/components/YourProjects.vue'
import Announcements from '@/components/Announcements.vue'
import Trending from '@/components/Trending.vue'
</script>
<template>
<div class="container project-box">
        <section class="dashboard">
          <div class="project">
            <h4>Your Projects</h4>
            <div class="project-grid">
              <YourProjects/>
            </div>
          </div>
          <section class="side">
            <div class="announcement">
              <h4>Announcements</h4>
              <div class="background-box">
                <Announcements/>
              </div>
            </div>
            <div>
              <h4>Trending</h4>
              <div class="background-box trending">
                <Trending/>
              </div>
            </div>
          </section>
        </section>
      </div>
</template>
<style></style>
