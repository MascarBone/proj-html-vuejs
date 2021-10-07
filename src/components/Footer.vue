<template>
  <footer>
    <div class="container">
      <div class="row footer-top">
        <div class="col-3">
          <FootList :info="about"/>
        </div>
        <div class="col-3">
          <FootList :info="contact"/>
        </div>
        <div class="col-3">
          <FootSocials :info="socials"/>
        </div>
        <div class="col-3">
          <FootLogo :info="logoUdemy"/>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="row footer-bot align-items-center">
        <div class="col-auto">
          <FootLogo :info="logoMS"/>
        </div>
        <div class="col-auto">
          <FootCopyright :info="copyright"/>
        </div>
      </div>
    </div>
      
  </footer>
</template>

<script>
import FootList from './Footer/FootList.vue';
import FootLogo from './Footer/FootLogo.vue';
import FootCopyright from './Footer/FootCopyright.vue';
import FootSocials from './Footer/FootSocials.vue';


export default {
  name: 'Footer',

  components: {
    FootList,
    FootLogo,
    FootCopyright,
    FootSocials,
  },

  data: function() {
    return{
      about: {
        heading: 'About',
        list:[
          'Sed nec felis pellentesque, lacinia dui sed, ultricies sapien. Pellentesque orci lectus, consectetur vel, rutrum eu ipsum. Mauris accumsan eros libero posuere vulputate.' 
        ],
      },

      contact: {
        heading: 'Contact',
        list:[
          'USA, California 20, First Avenue, California',
          'Tel.: +1 212 458 300 32',
          'Fax: +1 212 375 24 14',
          'info@masterstudy.com'
        ],
      },

      socials: {
        heading: 'Social Network',
        list:[
          {
            id:'facebook',
            src:'Sed nec felis pellentesque, lacinia dui sed, ultricies sapien. Pellentesque orci lectus, consectetur vel, rutrum eu ipsum. Mauris accumsan eros libero posuere vulputate.',
          } 
        ],
      },

      logoUdemy: {
        id: 'udemy courses discount',
        src: require('../assets/images/icons-logos/top-udemy-courses-80-percent-off.jpg'),
      },

      logoMS: {
        id: 'master_study',
        src: require('../assets/images/icons-logos/footer-logo2x-50x56.png'),
      },

      copyright: [
        {
          id: 'text',
          descr: 'Copyright © 2020. ',
        },
        {
          id: 'link',
          src: '#',
          descr: 'MasterStudy',
        },
        {
          id: 'text',
          descr: ' Theme by ',
        },
        {
          id: 'link',
          src: '#',
          descr: 'StylemixThemes',
        },
      ]
    }
  }
}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

footer {
  background-color: $ebony-clay;
  color: $white;
  padding: 50px 0;
}
</style>