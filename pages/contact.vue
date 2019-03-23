<template>
  <no-ssr>
    <form name="contact" method="POST" data-netlify="true">
      <input type="hidden" name="form-name" value="contact">
      <p>
        <label>
          Your Name:
          <input type="text" name="name">
        </label>
      </p>
      <p>
        <label>
          Your Email:
          <input type="email" name="email">
        </label>
      </p>

      <p>
        <label>
          Message:
          <textarea name="message"></textarea>
        </label>
      </p>
      <p>
        <button type="submit">Send</button>
      </p>
    </form>
  </no-ssr>
</template>

<script>
export default {};
</script>

<style>
</style>
