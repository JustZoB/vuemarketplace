<template>
  <svg
    class="icon"
    :class="theme"
    xmlns="http://www.w3.org/2000/svg"
    width="24"
    height="24"
    viewBox="0 0 24 24"
    fill="none"
  >
    <rect y="3.5" width="24" height="1" fill="#191919"/>
    <rect y="11.5" width="24" height="1" fill="#191919"/>
    <rect y="19.5" width="24" height="1" fill="#191919"/>
    <circle cx="5.5" cy="4" r="3" fill="white" stroke="#191919"/>
    <circle cx="18.5" cy="12" r="3" fill="white" stroke="#191919"/>
    <circle cx="10.5" cy="20" r="3" fill="white" stroke="#191919"/>
  </svg>
</template>

<script>
export default {
  name: 'IconFilters',
  props: ['theme']
}
</script>
