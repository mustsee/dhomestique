<template>
<div>
  <hero />
  <services />
</div>
</template>

<script>
  import Hero from "../components/Hero";
  import Services from "../components/Services";

export default {
  components: {
    'hero': Hero,
    'services': Services
  }
}
</script>


