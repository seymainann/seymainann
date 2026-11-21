<div align="center">

<img width="100%" alt="Bilgisayar Mühendisliği" src="https://capsule-render.vercel.app/api?type=venom&amp;color=0:0B1020,55:25255D,100:087F8C&amp;height=200&amp;section=header&amp;text=Bilgisayar%20M%C3%BChendisli%C4%9Fi&amp;fontSize=38&amp;fontColor=EAFBFF&amp;stroke=65E4DA&amp;strokeWidth=0.7&amp;animation=fadeIn" />

**Kocaeli Üniversitesi**

<img width="540" alt="Algoritmalar, nesne yönelimli programlama ve simülasyon" src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;size=19&amp;duration=2800&amp;pause=1100&amp;color=219B9A&amp;center=true&amp;vCenter=true&amp;width=540&amp;lines=%3E_+Algoritmalar;%3E_+Nesne+y%C3%B6nelimli+programlama;%3E_+Sim%C3%BClasyon" />

<br>

<img alt="C" src="https://img.shields.io/badge/C-253B80?style=for-the-badge&amp;logo=c&amp;logoColor=white" />
<img alt="Python" src="https://img.shields.io/badge/Python-17566D?style=for-the-badge&amp;logo=python&amp;logoColor=white" />
<img alt="Java" src="https://img.shields.io/badge/Java-593A87?style=for-the-badge&amp;logo=openjdk&amp;logoColor=white" />

</div>

## Projeler

<table>
  <tr>
    <td width="50%" valign="top">
      <img alt="C · Simülasyon" src="https://img.shields.io/badge/C-S%C4%B0M%C3%9CLASYON-087F8C?style=flat-square&amp;labelColor=17223A" />
      <h3>Teknik Destek Simülasyonu</h3>
      <p>Dosyadan okunan teknik destek görevlerini dört teknisyene dağıtan bir C programı.</p>
      <p><code>Shortest Job</code> <code>Priority</code> <code>Round Robin</code></p>
    </td>
    <td width="50%" valign="top">
      <img alt="Java · Nesne yönelimli programlama" src="https://img.shields.io/badge/JAVA-NESNE%20Y%C3%96NEL%C4%B0ML%C4%B0-7452A4?style=flat-square&amp;labelColor=17223A" />
      <h3>Robot Uygulaması</h3>
      <p>Robotu ve davranışlarını Java sınıflarıyla modellediğim bir çalışma.</p>
      <p><code>Sınıflar</code> <code>Nesneler</code> <code>Metotlar</code></p>
    </td>
  </tr>
</table>

### Simülasyon nasıl çalışıyor?

```mermaid
flowchart LR
    A["gorevler.txt"] --> B["Görevleri doğrula"]
    B --> C["Algoritmayla sırala"]
    C --> D["Teknisyene ata"]
    D --> E["Sonuçları raporla"]
    classDef input fill:#17223A,stroke:#6183C9,color:#FFFFFF
    classDef process fill:#26305B,stroke:#9B87DB,color:#FFFFFF
    classDef result fill:#075F63,stroke:#5DE3D5,color:#FFFFFF
    class A input
    class B,C,D process
    class E result
