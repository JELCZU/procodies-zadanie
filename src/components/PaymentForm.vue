<script setup></script>

<template>
  <div class="border-1 p-6 form-border">
    <section class="pb-6">
      <label class="xx-large forest-pine text-center d-inline-block w-100">Enter details</label>
    </section>
    <section class="pb-4">
      <section class="d-flex pb-4">
        <input
          class="input flex-item-2 mr-4"
          title="First name"
          name="First name"
          placeholder="First name"
        />
        <input
          class="input flex-item-2"
          title="Last name"
          name="Last name"
          placeholder="Last name"
        />
      </section>
      <section class="pb-4">
        <input class="input w-100" title="Street" name="Street" placeholder="Street" />
      </section>
      <section class="d-flex pb-4">
        <input
          class="input flex-item-2 mr-4"
          title="Postal code"
          name="Postal code"
          placeholder="Postal code"
        />
        <input class="input flex-item-2" title="City" name="City" placeholder="City" />
      </section>
      <section class="pb-4">
        <input
          class="input w-100"
          title="Phone number"
          name="Phone number"
          placeholder="Phone number"
        />
      </section>
      <section c>
        <input class="input w-100" title="E-mail" name="E-mail" placeholder="E-mail" />
      </section>
    </section>
    <section class="pb-4">
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
.flex-item-2 {
  flex: 0 50%;
}
</style>
