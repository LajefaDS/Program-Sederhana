<template>
  <div class="d-flex justify-content-center align-items-center" style="margin-top: 13%;">
    <div class="container p-5 form-control border-info border-3 rounded-5" style="width: 50%;">
      <form
        @submit.prevent="submitForm"
        style="
          width: 100%;
          font-family: Arial, Helvetica, sans-serif;
          font-weight: bold;
          font-size: 18px;
        "
      >
        <div class="mb-3">
          <label for="exampleFormControlInput1" class="form-label"
            >Email address</label
          >
          <input
            type="email"
            class="form-control"
            id="exampleFormControlInput1"
            placeholder="alamatemail@gmail.com"
            v-model="formData.name"
            required
          />
        </div>
        <div class="mb-3">
          <label for="exampleFormControlTextarea1" class="form-label"
            >Example textarea</label
          >
          <textarea
            class="form-control"
            id="exampleFormControlTextarea1"
            rows="3"
            v-model="formData.email"
            placeholder="Masukkan Kata - Kata Anda..."
            required
          ></textarea>
        </div>
        <button type="submit" class="btn btn-primary">Submit</button>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      formData: {
        name: "",
        email: "",
      },
    };
  },
  methods: {
    submitForm() {
      alert(`Nama: ${this.formData.name}, Email: ${this.formData.email}`);
    },
  },
};
</script>