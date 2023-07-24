<template>
  <div class="swimlane">
  <!-- Put your content here-->
  </div>
</template>

<script>

/**
 *
 * Scenario
 *
 * As a user I would like to view a "News All Day" swimlane that lists
 * video thumbnails with their titles.
 *
 * Acceptance Criteria
 * - Has a header titled "News All Day"
 * - Calls videos api endpoint to fetch video items
 * - Renders a list of VideoCards with the data returned from the api
 * - Layout matches the design provided
 * - Every 5 minutes check and see if we have new content to display, and only re-render the page if we do.
 * - Only check for new content if the user remains on this page.
 * Stretch goals
 * - write a unit test with jest for your component(s) 
 *
 */

import { ref } from 'vue';

const videos = ref([])

function setVideos() {
  //
}

export default {
  name: 'App',
  components: { }
}
</script>

<style>
</style>
