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
<pre>
    Saya adalah mahasiswa Universitas Islam Riau yang berdomisili di daerah rumbai.
    Saya mengambil mata kuliah teknik informatika prodi teknik
    Saat ini saya sudah semester 4 dengan kesibukan sebagai kakak asuh,
    dan juga saya di amanahkah di dalam HIMATIF sebagai STAFF Hubungan Masyarakat yang beranggotakan 7 orang.
</pre>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>

    SDN 066 PEKANBARU<br />
    SMPN 6 PEKANBARU <br />
    SMKN 7 PEKANBARU<br />
    UNIVERSITAS ISLAM RIAU 2022-NOW
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Pengalaman</template>
    Magang di PT.TELKOM JALAN SUDIRMAN BAGIAN TELKOM AKSES
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
      <li>Pemasangan WiFi</li>
      <li>IoT(Internet Of Things)</li>
     <li>BackEnd</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hubungi Saya</template>

    <a href="https://www.instagram.com/haqqi.qi" target="_blank">haqqi.qi</a
    ><br />
    Email : haqqisyahputra08@gmail.com<br />
    No HP : 223510766
  </WelcomeItem>
</template>
