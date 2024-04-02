<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Tentang Saya</template>
    Saya adalah mahasiswa di kampus universitas islam riau yang terletak di jalan Kaharuddin Nst
    Pekanbaru. Saat ini saya berada di semester 4 jurusan Teknik Informatika Universitas Islam Riau.
    Saya Berasal dari Kabupaten Rokan Hilir ,Kecamatan Bagan Sinembah Provinsi Riau
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>

    SDN 001 BAGAN SINEMBAH 2010-2016<br />
    SMPS PEMBANGUNAN BAGAN SINEMBAH 2016-2019<br />
    SMKS PEMBANGUNAN BAGAN SINEMBAH 2019-2022<br />
    UNIVERSITAS ISLAM RIAU 2022-NOW
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Pengalaman</template>
    Magang di PT.Indihome cabang Bagan Sinembah Maret 2021-Juni 2021
    <ul>
      <li>Memasang wifi menggunakan kabel fiber optik</li>
      <li>Meperbaiki arus jaringan yang putus</li>
      <li>Menyeting Access point</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Skill</template>
    <ul>
      <li>Pemasangan jaringan komputer</li>
      <li>IoT(Internet Of Things)</li>
      <li>HTML</li>
      <li>PHP</li>
      <li>C++</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hubungi Saya</template>

    Instagram :<a href="https://www.instagram.com/_zakykrnwan/" target="_blank">_zakykrnwan </a
    ><br />
    Email : zakykurniawan8817@gmail.com<br />
    No HP : 223510366
  </WelcomeItem>
</template>
