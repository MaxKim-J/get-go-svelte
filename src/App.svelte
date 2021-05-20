<script lang="ts">
  import Router from 'svelte-spa-router'
  import routes from './routes'
  import MainText from '~/components/Main/MainText.svelte'
</script>

<MainText />
<Router {routes} />
