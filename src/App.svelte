<script>
  import { Route } from 'tinro'
  import Navbar from './componets/Navbar.svelte'
</script>

<Navbar />

<Route path="/">
  <div class="view">Home</div>
</Route>
<Route path="/profile">Profile</Route>
<Route path="/settings">Settings</Route>

<style lang="scss">
  @import 'styles/colors';
  @import 'styles/mixins';

  :global(body) {
    background: $gray-200;
  }

  .view {
    @include container;
  }
</style>
