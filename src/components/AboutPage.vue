<template>
  <div class="main-content">
    <div id="about">
    <el-row>
      <el-row id="whoAreWe">
        <h2>Welcome to the development version of LC-METASPACE!</h2>
        <p>The METASPACE platform is developed by software engineers, data scientists and mass spectrometrists from the <a
          href="http://www.embl.de/research/units/scb/alexandrov/">Alexandrov team at EMBL</a>. This work is a part of the
          <a href="http://project.metaspace2020.eu">European project METASPACE</a>.</p>
      </el-row>
    </el-row>
    </div>
  </div>
</template>

<script lang="ts">
 export default {
   name: 'about-page'
 }
</script>

<style>
 #about {
   display: flex;
   padding: 0px 20px;
   align-items: center;
   justify-content: center;
 }
</style>
