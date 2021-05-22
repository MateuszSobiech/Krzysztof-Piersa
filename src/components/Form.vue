<template>
  <form class="contact-form" @submit.prevent="sendEmail">
    <input placeholder="Email" type="email" name="user_email" required />
    <textarea
      rows="8"
      placeholder="Wiadomość"
      name="message"
      required
    ></textarea>
    <input type="submit" value="Send" />
  </form>
</template>

<script>
import emailjs from 'emailjs-com';

export default {
  name: 'Form',
  methods: {
    sendEmail: (e) => {
      emailjs.sendForm('service_t1z2wm6', 'template_5mcpa1f', e.target, 'user_2AT0xp8qJ8kyV49PdjYvX')
        .then(() => {
          alert('Wiadomość została wysłana!');
        }, () => {
          alert('Wystąpił błąd prosimy o spróbowanie później lub wysłanie wiadomości ręczknie na adres piersa.krzysiek@gmail.com');
        });
      const form = document.querySelector('.contact-form');
      form.reset();
    }
  }
}
</script>

<style>
.contact-form {
  display: flex;
  padding: 20px;
  flex-direction: column;
  background-color: ghostwhite;
}
input[type="email"] {
  height: 35px;
  font-weight: bold;
  border: none;
  text-align: center;
  border-bottom: 3px solid black;
}

textarea {
  font-weight: bold;
  margin-top: 20px;
  border: none;
  border-bottom: 3px solid black;
}

textarea::placeholder {
  text-align: center;
  padding-top: 50px;
}

input[type="submit"] {
  margin-top: 20px;
  padding: 5px;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
  font-weight: bold;
  font-size: 20px;
  background-color: rgb(136, 196, 251);
  border-radius: 10px;
  border: none;
}

@media (min-width: 768px) {
  .contact-form {
    width: 50%;
    margin-left: auto;
    margin-right: auto;
  }
}
</style>