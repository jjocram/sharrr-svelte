<script lang="ts">
  import FaHeart from 'svelte-icons/fa/FaHeart.svelte'
  import Button from '$components/Button.svelte'
</script>

<footer class="p-6 pt-8 flex flex-col items-center text-center text-gray-600">
  <div class="py-4 flex flex-col items-center justify-center text-center p-5 max-w-sm">
    <small class="mb-3"
      >*Together for privacy over profits. Your donation keeps this project running.</small
    >
    <Button
      href="https://donate.stripe.com/28oeV1gKP3bv4b6144"
      variant="dark"
      size="small"
      class="plausible-event-name=Donate"
      target="_blank"
    >
      <div class="flex mr-2 w-4 h-4">
        <FaHeart />
      </div>
      Donate</Button
    >
  </div>
  <small>
    Created by{' '}
    <a class="underline hover:text-primary" href="https://bsky.app/profile/stophe.com">
      @stophe.com</a
    >
    <!-- Use <a class="underline hover:text-primary" href="https://scrt.link">scrt.link</a> for greater needs. -->
    &bull;
    <a class="underline hover:text-primary" href="https://github.com/stophecom/sharrr-svelte">
      Github</a
    >
  </small>
</footer>
