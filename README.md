<div align="center">
  <h1>⚙️ Virtualización de Hardware</h1>
  <p><em>Ejercicios resueltos y APLs de la materia Virtualización de Hardware (3654) - 1C 2024 - UNLaM.</em></p>

  <!-- Badges -->
  <img src="https://img.shields.io/badge/Universidad-UNLaM-1F4F90?style=for-the-badge&logo=google-scholar&logoColor=white" alt="UNLaM" />
  <img src="https://img.shields.io/badge/Año-2024-2EA043?style=for-the-badge" alt="2024" />
  <img src="https://img.shields.io/badge/Estado-Completado-blue?style=for-the-badge" alt="Completado" />
  <img src="https://img.shields.io/badge/Lenguaje-Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/Lenguaje-PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" alt="PowerShell" />
  <img src="https://img.shields.io/badge/Grupo-2-7057D2?style=for-the-badge" alt="Grupo 2" />
</div>

<br>

## 📑 Índice
- [Información de la Asignatura](#informacion-de-la-asignatura)
- [Trayecto - Infraestructura](#trayecto)
- [Docentes](#docentes)
- [Integrantes](#integrantes)
- [Unidad 1 - Scripting de Sistemas Operativos](#unidad-1)
- [Unidad 2 - Tecnologías de Almacenamiento](#unidad-2)
- [Unidad 3 - Virtualización](#unidad-3)
- [Unidad 4 - Desarrollo en Lenguaje Nativo del SO](#unidad-4)
- [Unidad 5 - Contenedores / DevOps](#unidad-5)
- [Unidad 6 - Cloud](#unidad-6)
- [Herramientas Utilizadas](#herramientas-utilizadas)
- [Estructura del Proyecto](#estructura-del-proyecto)

---

📚 **[Repositorio de la Cátedra](https://github.com/unlam-sisop)**

---

<a id="informacion-de-la-asignatura"></a>
## ℹ️ Información de la Asignatura
* **Carrera**: Ingeniería en Informática
* **Asignatura**: Virtualización de Hardware (3654)
* **Cuatrimestre**: Primer Cuatrimestre
* **Año**: 2024
* **Grupo**: 2

<a id="trayecto"></a>
## 👨‍💻 Trayecto - Infraestructura
* **Año académico**: Tercer Año - Segundo Cuatrimestre
* **Responsable / Jefe de cátedra**: Villamayor, Alexis
* **Carga horaria semanal**: 4 hs
* **Carga horaria total**: 64 hs
* **Modalidad**: Virtual
* **Correlativas anteriores**
  * Redes de Computadoras (3643)
  * Sistemas Operativos (3649)

<a id="docentes"></a>
## 👨‍🏫 Docentes
* Boettner, Fernando
* Piubel, Fernando
* Rodriguez, Alejandro Edgar
* Villamayor, Alexis

<a id="integrantes"></a>
## 👥 Integrantes
<div align="center">

| DNI | Apellido/s | Nombre/s |
| :--: | :--: | :--: |
| **44.451.238** | Ocampo | Nicole Fabiana |
| **41.548.235** | Sandoval Vasquez | Juan Leandro |
| **32.788.835** | Tigani | Martin Sebastian |
| **37.792.844** | Villegas | Lucas Ezequiel |
| **38.703.964** | Vivas | Pablo Ezequiel |

</div>

---

<a id="unidad-1"></a>
## Unidad 1 - Scripting de Sistemas Operativos

<div align="center">
  <img src="https://instagram.fepa1-1.fna.fbcdn.net/v/t39.30808-6/768954379_1326180466205294_2092319402729549980_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=104&_nc_map=urlgen_bucketless&ig_cache_key=Mzk1ODgxMjQ0OTA1OTc4NjYwNw%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTI4MC5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=D2RFnzx1oXQQ7kNvwGPhyP8&_nc_oc=AdqRAB3Qfl68H-_h0QwcfBC5BfviS9BvIkF-fpZ-tBVzq5WoQ2XqRgcSW2jrupuPD9vL2w5CIevR9-uBBfqzo-25&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.fepa1-1.fna&_nc_gid=l76fpSX_sKo8DmELiGFEVg&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQTTFy4tDjhegXCqCuz0kQU0t1vkS04FrkMS-Q1bAYRu8Q&oe=6AFEBE7A" alt="Bash Scripting" width="450" />
  <br>
  <sup><em>Automatización de scripts mediante Bash Shell en Linux</em></sup>
  <br><br>
  <img src="https://www.linuxteck.com/wp-content/uploads/2026/06/Awk-fundamentals-cheat-sheet-for-beginners-Part-26.png" alt="AWK" width="450" />
  <br>
  <sup><em>Procesamiento y filtrado de texto avanzado con AWK</em></sup>
  <br><br>
  <img src="https://instagram.fepa2-1.fna.fbcdn.net/v/t39.30808-6/752619858_1313100507513290_1732861072108763479_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=106&_nc_map=urlgen_bucketless&ig_cache_key=Mzk0NzExNzc5MzQ5MDQ5NDg5OQ%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTIxNS5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=UZJ7OWoC_cwQ7kNvwHS7uDm&_nc_oc=AdpEKZeHjZTZsIsaqfk-u9rJbzIrN5LramoanrADei_qs1ibEKMNx6a5uI-9EF4wqQRI_PqDc8nfqnJC57OaLNu1&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.fepa2-1.fna&_nc_gid=Svg4g_Jr5vVoWh4k74Rg1Q&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQS5eA7E9NbNqzarFqcJe23QDwWp_l875VvmeqWMVGpyRA&oe=6AFEC140" alt="Comandos Básicos de PowerShell" width="450" />
  <br>
  <sup><em>Administración de entornos e infraestructuras con PowerShell</em></sup>
</div>
<br>

* Bash
* AWK
* PowerShell

---

<a id="unidad-2"></a>
## Unidad 2 - Tecnologías de Almacenamiento

<div align="center">
  <img src="https://media.licdn.com/dms/image/v2/D4D22AQHVIBK1R1WGSA/feedshare-shrink_800/B4DZgJX63aHAAs-/0/1752503933261?e=1796256000&v=beta&t=tJHfhnnk_PEdzqAv3REGfFPCWp6Tz5f92BeD1kjwJXo" alt="DAS vs NAS vs SAN" width="450" />
  <br>
  <sup><em>Comparativa general: DAS, NAS y SAN</em></sup>
  <br><br>
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTSAeaXchTaM9XRys0sL8bFp9UB6x0dO3xlTEScgqLeaukOCurUw1fwczk&s=10" alt="DAS vs SAN" width="450" />
  <br>
  <sup><em>Arquitectura de conexión DAS vs Redes de Almacenamiento SAN</em></sup>
  <br><br>
  <img src="https://instagram.faep28-1.fna.fbcdn.net/v/t39.30808-6/778972554_1335212075302133_7812469025377877054_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=108&_nc_map=urlgen_bucketless&ig_cache_key=Mzk2NzIzODEyNzE0MDIxMDY4OA%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTI0MC5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=_2wZ8OFz-8IQ7kNvwGJFjN9&_nc_oc=AdrjciSK18O07yoGEZ3vm0pzTvvdWL7oyy-FUuFdzbePYMYXzkLYns4u9C_5S-EbG0a_Q2qrisdo7bYD9aHPXL49&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.faep28-1.fna&_nc_gid=qV5IaemblCE23s62l0xTpw&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQQScRR17y4lbUjcvQ1sJilfZUyFKyLUzeRtEjQiUUMczw&oe=6AFEC258" alt="Tipos de RAID - Parte I" width="450" />
  <br>
  <sup><em>Organización de Arreglos de Discos Redundantes (RAID)</em></sup>
  <br><br>
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQn5_CprAFCbjp2eT4u0b39EiOJLihtkKlSxCtJRj7y1T0unS3oCKp7CuP_&s=10" alt="Tipos de RAID - Parte II" width="450" />
  <br>
  <sup><em>Niveles de RAID y técnicas de Paridad / Mirroring</em></sup>
</div>
<br>

* DAS - Direct Attached Storage
* NAS - Network Attached Storage
* SAN - Storage Area Network
* Protocolos
    * Orientado a Bloques
        * FC - Fibre Channel.
        * iSCSI - Internet SCSI.
        * FCoE - Fibre Channel over Ethernet.
        * SAS - Serial Attached SCSI.
    * Orientado a Archivos
        * CIFS - Common Internet File System / SMB - Server Message Block
        * NFS - Network File System.
* RAID - Redundant Array of Inexpensive (Independent) Disks.
    * Organización de Discos
        * Mirroring.
        * Duplexing.
        * Striping.
        * Paridad.
    * Niveles
        * Nivel 0 - Striping sin paridad.
        * Nivel 1 - Mirroring / Mirroring con Duplexing.
        * Nivel 4 - Striping de bloques con paridad dedicada.
        * Nivel 5 - Striping de bloques con paridad distribuida.
        * Nivel 6 - Striping de bloques con paridad doble distribuida.
        * Nivel 0 + 1
        * Nivel 1 + 0
    * JBOD - Just a Bunch Of Disks

---

<a id="unidad-3"></a>
## Unidad 3 - Virtualización

<div align="center">
  <img src="https://instagram.fepa2-1.fna.fbcdn.net/v/t39.30808-6/687698020_122277417290189612_6805950592731750553_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=104&_nc_map=urlgen_bucketless&ig_cache_key=Mzg9MjAxMjI1Nzk1MDA0MzE1OA%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuOTkyLnNkci5yZWd1bGFyX3Bob3RvLkMzIn0%3D&_nc_ohc=GDym31KzprcQ7kNvwE884mC&_nc_oc=Adqxq3omoSDyX5BgdyY4V50sqkK-x1H55-Vjl1J4G5Ro4oHZQu1kU4iv8RIydkoAqcOSb7D-gaVqO2J6aBmRUcKI&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.fepa2-1.fna&_nc_gid=f93oFc1Xj7NxSMzU9Jpy9w&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQTftaIio8X-zrFm4_WMplQKzEfVLKibV2fjM6Vxmh247w&oe=6AFED2FE" alt="Servidores" width="450" />
  <br>
  <sup><em>Infraestructura física y servidores de procesamiento</em></sup>
  <br><br>
  <img src="https://instagram.faep28-2.fna.fbcdn.net/v/t39.30808-6/697379114_122278401470189612_4582915656437097906_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=104&_nc_map=urlgen_bucketless&ig_cache_key=Mzg9Nzg3MDg3NDE0MTYyNzk2Mg%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTI1NC5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=c_nxiMZp1ioQ7kNvwHACeVg&_nc_oc=Ado2M2bA3vOu0qGi5ZAlgv_k7D_qceHNeSufDtU3W1Hk5ohGB87S__X0Q90bXuvCjhLVLUPMTWKHD1nRzdnu5WU9&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.faep28-2.fna&_nc_gid=HbJqPH6eRdP_jyQwE8oP0g&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQQWGV999LB5UQg3d7c2QgvcGo-EnT6ARZv4RMoQsVGdvw&oe=6AFED7CF" alt="Virtualizacion" width="450" />
  <br>
  <sup><em>Capa de abstracción y virtualización de recursos</em></sup>
  <br><br>
  <img src="https://www.palentino.es/blog/wp-content/uploads/2026/07/hipervisores.png" alt="Hipervisores" width="450" />
  <br>
  <sup><em>Clasificación de Hipervisores: Tipo 1 (Bare Metal) y Tipo 2 (Hosted)</em></sup>
</div>
<br>

* Ventajas y Desventajas.
* Tipos de Virtualización
    * Emulación.
    * Hipervisores
        * Tipo 1 - Bare Metal (Virtualización Completa).
        * Tipo 2 - Host Based.
    * Paravirtualización.
    * A nivel Sistema Operativo.
    * A nivel Kernel.
* Funciones especiales
    * Encapsulamiento.
    * Clones y Templates.
    * Snapshots.
    * Migraciones.
        * En frío.
        * En caliente.
            * Por archivos.
            * Por procesos.
* Thin Provisioning

---

<a id="unidad-4"></a>
## Unidad 4 - Desarrollo en Lenguaje Nativo del SO

<div align="center">
  <img src="https://miro.medium.com/v2/resize:fit:640/format:webp/1*Qdn6uayFB-sEIA02IuOdIg.png" alt="System Calls" width="400" />
  <br>
  <sup><em>Llamadas al Sistema (System Calls) y modos Kernel / User</em></sup>
  <br><br>
  <img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/1*87ImC9VPyubVPpSyOjQl-A.jpeg" alt="Semaforos" width="450" />
  <br>
  <sup><em>Sincronización mediante Semáforos y exclusión mutua</em></sup>
  <br><br>
  <img src="https://instagram.faep28-1.fna.fbcdn.net/v/t39.30808-6/672678937_122274737960189612_5303379421398700236_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=109&_nc_map=urlgen_bucketless&ig_cache_key=Mzg3ODAzMDc2NjE2OTIzNzE5Mg%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTQwOC5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=rWlqVlgzqdYQ7kNvwE19er_&_nc_oc=Adpc9Pg7veNd-DYZv0gjBNBC0aQAqIDUQez5a5JgBtpC5P855o0gzgaKIPBG88gfBHBg8ZApIbbElydDSnEERfX8&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.faep28-1.fna&_nc_gid=mDlHn0y90ofHmF9kK1K-KQ&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQRfSAsw8oc23URqAbEJhnWmuSxj-AGOx_Y2w0oBtDw5Mw&oe=6AFECAE3" alt="Procesos vs Hilos" width="450" />
  <br>
  <sup><em>Diferencias estructurales entre Procesos e Hilos (Threads)</em></sup>
  <br><br>
  <img src="https://instagram.fepa2-1.fna.fbcdn.net/v/t39.30808-6/714949254_122281541066189612_6530581940499800137_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=102&_nc_map=urlgen_bucketless&ig_cache_key=MzkxNjUzMzk4Mjc3NDY5NjQ2Nw%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTI1NC5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=urFe4uZI4usQ7kNvwFQvBXf&_nc_oc=Adplu789zToLxR0dsi6mtDo-VpqoKlVA2yUX1R6NAn-l3Pg2u6c94QGQQMSzrPLi0AV9ie55q7hq5zhGskhKEReZ&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.fepa2-1.fna&_nc_gid=__ji_GuLqBKu0YFqd5Twiw&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQSKxDm95dvAzqiEjh9QBUMFTL0XIqwFdrrcAvT-fMVeyA&oe=6AFECA22" alt="Hilos" width="450" />
  <br>
  <sup><em>Ejecución multihilo en el espacio del sistema operativo</em></sup>
  <br><br>
  <img src="https://instagram.fepa2-1.fna.fbcdn.net/v/t39.30808-6/701343737_122278904954189612_6149467831498239482_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=108&_nc_map=urlgen_bucketless&ig_cache_key=MzkwMTI1MzI3Njk4NTI5NTY5Mg%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTIwMy5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=HkQNDSdeP0oQ7kNvwEUxlh1&_nc_oc=AdqwX-zrlm1a37eg_I_EcHUlkfXpwSiKGfECfuCGValXlKrSt0QA7gLs4w-ZqftBL06V8qyWr7w_It9Q-_9uKt0o&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.fepa2-1.fna&_nc_gid=HCpzwD1IjGPEFKfsdMk7aw&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQQ60HxpxwodmT6G2PPi59aLndGyqtYjsb238AxLeUGztQ&oe=6AFECB78" alt="Sockets" width="450" />
  <br>
  <sup><em>Comunicación IPC y Sockets de red</em></sup>
  <br><br>
  <img src="https://instagram.faep28-2.fna.fbcdn.net/v/t39.30808-6/699761492_122278736642189612_8546733047505161309_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=104&_nc_map=urlgen_bucketless&ig_cache_key=Mzg5OTA0ODkzMDQ2MTczMTk0NA%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTIwNC5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=_TqWPGbfgq8Q7kNvwFb1nNP&_nc_oc=AdqahAgM-l9lsPkNvGdNnrVTPAz8nkQDJnF17zBwB1_6AV0hLBrbDKrXa5T2dR5q88Gd7PJ4_cv49TovIBRg7ssh&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.faep28-2.fna&_nc_gid=_GZz3P9H3vRus5E-iKK-9g&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQSVSlV33tJCQO6TfWogvpOj9v8VFI519REZF2oItmcjFw&oe=6AFEF465" alt="WebSockets" width="450" />
  <br>
  <sup><em>Protocolo de comunicación dúplex mediante WebSockets</em></sup>
</div>
<br>

* GCC, make, fork, wait, exec.
* FIFO, MC, Semáforos.
* Sockets, Threads.

---

<a id="unidad-5"></a>
## Unidad 5 - Contenedores / DevOps

<div align="center">
  <img src="https://instagram.fepa2-1.fna.fbcdn.net/v/t39.30808-6/674681831_122275573550189612_3367906394662364833_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=110&_nc_map=urlgen_bucketless&ig_cache_key=Mzg4MzI4NDkwMjQzMTMwOTgwMg%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTY1OS5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=VX5C0ur_KIsQ7kNvwHBvPbI&_nc_oc=AdqFTBz3c5ijj_X8iLhqU8PbTpZSdXAOvp8_1bYsEl8lOqObEJAlxteFt2Nsgpdea2wGcoMvePfwdPmx-FSdFlBw&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.fepa2-1.fna&_nc_gid=k-dmk5rAIl6vet3szGBfUg&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQTznR3a3zxh7yZeZH8PUb6kp12t6ZA_qMXO_tgf0_3g8Q&oe=6AFEDB94" alt="DevOps" width="450" />
  <br>
  <sup><em>Ciclo de vida e integración de la cultura DevOps</em></sup>
  <br><br>
  <img src="https://instagram.faep28-2.fna.fbcdn.net/v/t39.30808-6/700679147_122278740278189612_6965920115166342005_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=102&_nc_map=urlgen_bucketless&ig_cache_key=Mzg9OTMyMDE3OTcwMDM5MTQzMQ%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTIwNC5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=Rcv-6AVKjGoQ7kNvwFR8LO4&_nc_oc=AdrZiG7LPfRkaaMsl8HO8AwcxvOrg6y8WmR6_cgl7_B1pj2r7OMdXvKETC5kgKL84CTqYgJq8sIfuqMAHxshJD9_&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.faep28-2.fna&_nc_gid=3uvrgrz2I2gAeVKBGfCkDg&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQTD6pTMWyjoT8TGmAdQOCJDZa6Ynol4FzpvwTzYKPqEMA&oe=6AFEF072" alt="¿Qué es CI / CD? Versión 1" width="450" />
  <br>
  <sup><em>Principios de Integración y Despliegue Continuo (CI/CD)</em></sup>
  <br><br>
  <img src="https://instagram.faep28-1.fna.fbcdn.net/v/t39.30808-6/711720897_122281147868189612_8228253594966621601_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=100&_nc_map=urlgen_bucketless&ig_cache_key=MzkxMjk3MDM1NzY3MDAxMDQ6Mw%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTI1NC5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=P9G4ovEY5OoQ7kNvwELUtUc&_nc_oc=AdoGPDB9jg4qxovmM_4UzShWq3EByYS932yoBTHbkVpYLRfF5IWYBOFSPv6YH4UxHf2rnwU3_V-1J5nCf9YEHu-K&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.faep28-1.fna&_nc_gid=90vL48DaxK2EZjiZz78_mg&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQT2jj-AsY7FHhF-OubQBoBA_nzETNgZ0FRoyi3eqrNR0w&oe=6AFEEFC2" alt="¿Qué es CI / CD? Versión 2" width="450" />
  <br>
  <sup><em>Flujo de trabajo automatizado en pipelines de CI/CD</em></sup>
  <br><br>
  <img src="https://instagram.faep28-1.fna.fbcdn.net/v/t39.30808-6/678688976_122275573904189612_147892509996635890_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=103&_nc_map=urlgen_bucketless&ig_cache_key=Mzg4MzMxNDgxOTkwNTkyNjc5Mw%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTY1OS5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=aW8a20ykU8YQ7kNvwEZoi_s&_nc_oc=Adqb0RAL5VS7HJTEA7hmrmjRnDD4KrzKHYnEkHq1YwBcssqJPB9ZNrxps_QNq6bPg_dgLmnqiO2c4jyA7-R9FHuN&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.faep28-1.fna&_nc_gid=J64TiX2cDZOw8UrZ6L0Xfw&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQR2ccwik-uv9gfTBxNRGDX15zzn25udh3HiV1TfR6lOEQ&oe=6AFEF447" alt="Pipeline CI / CD" width="450" />
  <br>
  <sup><em>Etapas de pruebas, construcción y entrega en CI/CD</em></sup>
  <br><br>
  <img src="https://instagram.fepa2-1.fna.fbcdn.net/v/t39.30808-6/799949552_1357133363110004_239521008912578596_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=101&_nc_map=urlgen_bucketless&ig_cache_key=Mzk4NjIzMzE5Nzk5ODQ1MTExMQ%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTI4MC5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=AvE3oYG-x_MQ7kNvwFP__xQ&_nc_oc=AdoVmJIq5Zofhk2JqIiUtu4YF8lDgXSQ4NR79HHr47QRCtgkt-BwqCh1QR16rRn4ZPfMhdWhwIG4DoMhXLl2TMXH&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.fepa2-1.fna&_nc_gid=FstJYwn84EnCIvXh20QaNw&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQThdCeCv79bS483gUHqado22_wfJ_M5QbjTXqRUoNiNkw&oe=6AFEEAEF" alt="Contenedores vs Maquinas Virtuales" width="450" />
  <br>
  <sup><em>Comparativa técnica: Contenedores vs Máquinas Virtuales</em></sup>
  <br><br>
  <img src="https://instagram.fepa2-1.fna.fbcdn.net/v/t39.30808-6/699186847_122278730948189612_125759561596822859_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=107&_nc_map=urlgen_bucketless&ig_cache_key=Mzg9ODM1NDE2MDgwNjc2NTczMA%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTIwMC5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=MtkaOMbB-jgQ7kNvwGk1XfG&_nc_oc=Adr-eDsxNEttb7ysLxhjCnHFMQwn4zQ_PDlEooXfPpqMOHMA00WU1j1p_5hbDERDag1otxoQ-apA8yZfOxnDrNd1&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.fepa2-1.fna&_nc_gid=PW4qShfqEgIAY73nllUAjw&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQROIrkfOTxAhz56aMK1Pqa19-XuBrSP5tkjwDcy6ziAjw&oe=6AFEC948" alt="Docker" width="450" />
  <br>
  <sup><em>Motor de contenedorización Docker y Dockerfiles</em></sup>
  <br><br>
  <img src="https://instagram.faep28-2.fna.fbcdn.net/v/t39.30808-6/765051393_122290306034189612_858445467895987921_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=105&_nc_map=urlgen_bucketless&ig_cache_key=Mzk1NzkwNjM1Mjg8NjMxODMzOQ%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuMTI1NC5zZHIucmVndWxhcl9waG90by5DMyJ9&_nc_ohc=aasfby1xukYQ7kNvwEr7dmE&_nc_oc=AdrNgG5B736WKbybDjkERrEId7e-vdlHimvxmXyFeHKzCivRxIV41LjTJ7tQd6mzFdcIDt26oHLuNOz_6POVqPO9&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.faep28-2.fna&_nc_gid=FBGsKt4LfgVx0zmLasVkeA&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQRk52zRV87QDerbfKoALQegTHuYtC_SzGrDaKP7bOt45A&oe=6AFEFB91" alt="Kubernetes" width="450" />
  <br>
  <sup><em>Orquestación de clusters con Kubernetes (k8s)</em></sup>
</div>
<br>

* DevOps
    * Desarrollo.
    * Operaciones.
* Componentes
    * Planificación.
    * Codificación.
    * Construcción (CI). 
    * Testing.
    * Release.
    * Despliegue (CD).
    * Operación.
    * Monitoreo.
* Herramientas
* CI/CD
* Contenedores
    * Imágenes.
    * Docker
        * DockerFile.
        * DockerHub.
    * Volúmenes.
* Orquestadores
    * Beneficios.
    * Docker Swarm.
    * Kubernetes.

---

<a id="unidad-6"></a>
## Unidad 6 - Cloud

<div align="center">
  <img src="https://instagram.faep28-2.fna.fbcdn.net/v/t39.30808-6/687374803_122277415412189612_6596062178522913173_n.jpg?stp=dst-jpg_e35_tt6&_nc_cat=104&_nc_map=urlgen_bucketless&ig_cache_key=Mzg9MTgzMDg4OTg4NjAzNDU1NA%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQueHBpZHMuOTkyLnNkci5yZWd1bGFyX3Bob3RvLkMzIn0%3D&_nc_ohc=XzY1QuvuRqcQ7kNvwFGrpEZ&_nc_oc=AdrYeUXQlbSbjMl0eib8XVT2LsjE3qaYzhUu8cBnXEoeUWIVWxbhf3x0PN5CwCtgXSUptEXjrDD9Ogi12gPr46UY&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=instagram.faep28-2.fna&_nc_gid=juAZVMSKxZ1l0EPJ7abCVQ&_nc_ss=7a22e&_nc_ct=RQosPBUIFQIlBAAAAA&oh=00_AQSJrmsRSn1ESmq4eP9KUo5oIlrCi5HAC-igmwcAEPeKAw&oe=6AFEF017" alt="Cloud Computing" width="450" />
  <br>
  <sup><em>Modelos de Computación en la Nube (IaaS, PaaS, SaaS)</em></sup>
  <br><br>
  <img src="https://scontent.faep28-1.fna.fbcdn.net/v/t39.30808-6/273158770_4927816957263826_2339950353736211513_n.png?stp=dst-jpg_tt6&cstp=mx1080x1350&ctp=s1080x1350&_nc_cat=109&_nc_map=urlgen_bucketless&ccb=1-7&_nc_sid=127cfc&_nc_eui2=AeFF9Sv6WBRrbsZCJWihXoKhabLrh6fp1NJpsuuHp-nU0n-eUjpQ75eKfaxpgldeKa9ZLlC3x90FGvpBva6X1pXL&_nc_ohc=dntP8nX9lKcQ7kNvwG1Qw3v&_nc_oc=AdrUpNatoLss5FQe8foT7oKRz0CGlfGIpAHKRO-CrPas7Q4rbhq4oAzG5vOpAN9hRFN6Ev3ci_8gauFDpqDqVpl2&_nc_zt=23&_nc_ht=scontent.faep28-1.fna&_nc_gid=ZMyj4cKf3mAhoj_Dj1a8dA&_nc_ss=7b2a8&oh=00_AQQ3wDNaH6J8VSj06rCiuY6LTgl6a2y1FcF6E8z-_1XGhQ&oe=6AFEDE0D" alt="Tipos de Nubes" width="450" />
  <br>
  <sup><em>Despliegues en Nubes Públicas, Privadas e Híbridas</em></sup>
</div>
<br>

* Características.
* Tipos de Servicios
    * IaaS.
    * PaaS.
    * SaaS.
* Tipos de Nubes
    * Privadas.
    * Públicas.
    * Híbridas.
* Ventajas y desventajas.
* Servicios típicos.
* Conectividad.
* Conceptos básicos de networking.
* NAT - Network Address Translation / PAT - Port Address Translation
    * DNS - Domain Name System.
    * VPN - Virtual Private Network.

---

<a id="herramientas-utilizadas"></a>
## 🛠️ Herramientas Utilizadas
* **Bash / AWK**: Lenguajes de scripting empleados para la automatización de tareas y procesamiento de texto en entornos Linux.
* **PowerShell**: Lenguaje y entorno de comandos utilizado para la administración de infraestructura en sistemas Windows.
* **Lenguaje C / GCC**: Lenguaje nativo y compilador para el desarrollo a bajo nivel (llamadas al sistema, hilos, semáforos, sockets e IPC).
* **Docker**: Plataforma de virtualización a nivel del SO utilizada para la creación, empaquetado y ejecución de contenedores.
* **VirtualBox / VMware**: Hipervisores Hosted (Tipo 2) empleados para la prueba y gestión de entornos de máquinas virtuales.
* **Visual Studio Code**: Entorno de desarrollo (IDE) utilizado para la codificación y organización de los scripts y proyectos del repositorio.

---

<a id="estructura-del-proyecto"></a>
## 📁 Estructura del Proyecto
```text
📦 VirtualizacionDeHardware
 ┣ 📂 APL_1_Scripting
 ┃ ┣ 📂 Bash
 ┃ ┣ 📂 AWK
 ┃ ┗ 📂 PowerShell
 ┣ 📂 APL_2_Desarrollo_Nativo_C
 ┃ ┣ 📂 Sockets
 ┃ ┣ 📂 Hilos_Semaforos
 ┃ ┗ 📜 Makefile
 ┣ 📂 APL_3_Contenedores_Docker
 ┃ ┣ 📜 Dockerfile
 ┃ ┗ 📜 docker-compose.yml
 ┗ 📜 README.md
```
