<script setup></script>

<template>
  <div class="border-1 p-6 form-border">
    <section>
      <label class="xx-large forest-pine mb-6 text-center d-inline-block w-100"
        >Enter details</label
      >
    </section>
    <section>
      <input class="input" title="First name" name="First name" placeholder="First name" />
      <input class="input" title="Last name" name="Last name" placeholder="Last name" /><input
        class="input w-100"
        title="Street"
        name="Street"
        placeholder="Street"
      /><input
        class="input"
        title="Postal code"
        name="Postal code"
        placeholder="Postal code"
      /><input class="input" title="City" name="City" placeholder="City" /><input
        class="input w-100"
        title="Phone number"
        name="Phone number"
        placeholder="Phone number"
      /><input class="input w-100" title="E-mail" name="E-mail" placeholder="E-mail" />
    </section>
    <section>
      <button class="btn w-100" type="submit" name="Proceed to payment">Proceed to payment</button>
    </section>
    <section class="brand-section">
      <img src="../assets/brands/McAfeeSecure.png" alt="Mcafee secure" class="" height="100%" />
      <img
        src="../assets/brands/TrusteVerified.png"
        alt="Truste verified"
        class="pl-4 pr-4"
        height="100%"
      />
      <img
        src="../assets/brands/256BitEncryption.png"
        alt="256 Bit Encryption"
        class=""
        height="100%"
      />
    </section>
  </div>
</template>

<style scoped>
.form-border {
  border-radius: 1.25rem;
}
.brand-section {
  height: 40px;
  display: flex;

  justify-content: center;
}
</style>
