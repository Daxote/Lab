<template>
  <ion-page class="custom">
    <ion-header :translucent="true" class="custom">
      <ion-toolbar class="custom">
        <ion-title>Programacion de Aplicaciones</ion-title>
      </ion-toolbar>
    </ion-header>
    
    <ion-content :fullscreen="true" class="custom">
      <ion-list class="custom">
          <ion-list-header class="custom"> Alumnos </ion-list-header>

          <ion-searchbar animated="true" placeholder="Ingrese nombre del alumno" class="custom"></ion-searchbar>
          
          <ion-item class="custom">
            <ion-avatar slot="start">
              <img src="p3.svg" />
            </ion-avatar>
            <ion-label class="custom">
              <h2>Mauro Luciano Hernández Fontena</h2>
              <h3>Ingenieria civil informatica</h3>

            </ion-label>
          </ion-item>

          <ion-item class="custom">
            <ion-avatar slot="start">
              <img src=p3.png />
            </ion-avatar>
            <ion-label class="custom">
              <h2>Erwin Matias Chavez</h2>
              <h3>Ingenieria civil informatica</h3>

            </ion-label>
          </ion-item>

          <ion-item class="custom">
            <ion-avatar slot="start">
              <img src= p3.png />
            </ion-avatar>
            <ion-label class="custom">
              <h2>Dante Morales Soto</h2>
              <h3>Ingenieria civil informatica</h3>

            </ion-label>
          </ion-item>

          <ion-item class="custom">
            <ion-avatar slot="start">
              <img src="p3.png" />
            </ion-avatar>
            <ion-label class="custom">
              <h2>Samuel Sanchez</h2>
              <h3>Ingenieria civil informatica</h3>

            </ion-label>
          </ion-item >
        </ion-list>


    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { Item } from '@ionic/core/dist/types/components/item/item';
import { IonContent, IonSearchbar, IonItem, IonAvatar, IonHeader, IonPage, IonTitle, IonToolbar, IonList, IonLabel } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HomePage',
  components: {
    IonContent,
    IonSearchbar,
    IonHeader,
    IonPage,
    IonItem,
    IonTitle,
    IonToolbar,
    IonList,
    IonLabel,
    IonAvatar

  }
});
</script>

<style scoped>
#container {
  text-align: center;
  
  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 16px;
  line-height: 22px;
  
  color: #FFFFFFFF;
  
  margin: 0;
}

#container a {
  text-decoration: none;
}

ion-searchbar.custom {
    --background: #C2C2C2;
    --color: #EBEBEB;
    --placeholder-color: #0A0A0A;
    --icon-color: #0A0A0A;
    --clear-button-color: #EBEBEB;

    --border-radius: 15px;
  }

  ion-searchbar.ios.custom {
    --cancel-button-color: #EBEBEB;
  }

  ion-searchbar.md.custom {
    --cancel-button-color: #fff;
  }

ion-content.custom {
  --background: #EBEBEB;
  --color: #EBEBEB;
  
}
ion-item.custom {
  --background: #EBEBEB;
}

ion-label.custom {
  --color: #000000;
}
ion-label.custom2 {
  --color: #525252;
}
ion-list.custom {
  --background: #EBEBEB;
  --color: #EBEBEB;
}

ion-toolbar.custom {
  --background: #EBEBEB;
  --color: #000000;
  text-align: center;
}
ion-list-header.custom {
  --background: #EBEBEB;
  --color: #000000;
  --text-align: center;
}
ion-header.custom {
  --background: #EBEBEB;
  --color: #000000;
  text-align: center;
}
ion-page.custom {
  --background: #EBEBEB;
  --color: #EBEBEB;
}
*{
  background: #EBEBEB
}
</style>