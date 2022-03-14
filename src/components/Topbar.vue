<template>
  <header class="header" v-once>
    <div class="header__branding">
      <Logo class="header__logo"/>
    </div>
  </header>
</template>

<script>
import Plus from '../assets/plus.svg';
import Arrow from '../assets/arrow.svg';
import Logo from '../assets/logo.svg';
import Facebook from '../assets/facebook.svg';
import Twitter from '../assets/twitter.svg';
import Github from '../assets/github.svg';
import Skillshare from '../assets/skillshare.svg';

export default {
  name: 'topbar',
  components: {
    Arrow,
    Plus,
    Logo,
    Facebook,
    Twitter,
    Github,
    Skillshare,
  },
};
</script>
