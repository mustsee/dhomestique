<template>
<div>
  <hero />
  <services />
  <values />
</div>
</template>

<script>
  import Hero from "../components/Hero";
  import Services from "../components/Services";
  import Values from "../components/Values";

export default {
  components: {
    'hero': Hero,
    'services': Services,
    'values': Values,
  }
}
</script>


