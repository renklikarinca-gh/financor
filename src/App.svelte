<script>
  import { Route } from 'tinro'
  import Navbar from './componets/Navbar.svelte'
</script>

<Navbar />

<Route path="/">Home</Route>
<Route path="/profile">Profile</Route>
<Route path="/settings">Settings</Route>

<style lang="scss">
  @import 'styles/colors';

  :global(body) {
    background: $gray-200;
  }
</style>
