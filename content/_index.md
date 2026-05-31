---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  # 1. BÖLÜM: SOHE LAB Giriş, İki Fotoğraf ve İki Kolonlu Metin Düzeni
  - block: markdown
    id: sohelab
    content:
      title: '🔬 SOHE LAB / Social & Health Psychology Lab'
      subtitle: ''
      text: |-
        ![SOHE LAB Team](lab-1.jpeg) ![SOHE LAB Research](lab-2.jpeg)

        <table style="width:100%; border:none; border-collapse:collapse; margin-top:20px;">
          <tr>
            <td style="width:50%; padding-right:25px; vertical-align:top; border:none; line-height:1.6;">
              Welcome to the official portal of **SOHE LAB**. Directed by Assoc. Prof. Dr. Melike Eğer Aydoğmuş at Hacettepe University, our laboratory investigates the psychological mechanisms underlying human behavior, social attitudes, and well-being.
              <br><br>
              Our primary research lines focus on the dynamics of **stigma, perfectionism, self-compassion, self-determination theory (psychological needs and motivation), and emotion processing**. Utilizing advanced quantitative analyses, structural equation modeling (SEM), and mixed-methods research designs, SOHE LAB aims to bridge universal psychological constructs with profound cultural dynamics. We strive to generate scientific evidence that informs public health, shapes educational interventions, and guides policy-making for vulnerable groups.
            </td>
            <td style="width:50%; padding-left:25px; vertical-align:top; border-left:1px solid #e3e3e3; border-top:none; border-right:none; border-bottom:none; line-height:1.6;">
              **SOHE LAB Araştırma Dünyasına Hoş Geldiniz.** Hacettepe Üniversitesi bünyesinde Doç. Dr. Melike Eğer Aydoğmuş direktörlüğünde faaliyet gösteren laboratuvarımızda; insan davranışının, sosyal tutumların ve psikolojik iyi oluşun arkasındaki mekanizmaları inceliyoruz.
              <br><br>
              Temel araştırma alanlarımız arasında **damgalama (stigma), mükemmeliyetçilik, öz-şefkat, öz-belirleme kuramı (psikolojik ihtiyaçlar ve motivasyon) ve duygu işleme süreçleri** yer almaktadır. İleri nicel analizler, yapısal eşitlik modellemesi (SEM) ve karma yöntemli desenler kullanan SOHE LAB, evrensel psikoloji yaklaşımlarını kültürel dinamiklerle harmanlamayı ve toplumsal refaha katkı sunacak bilimsel çıktılar üretmeyi amaçlar.
            </td>
          </tr>
        </table>
    design:
      columns: '1'
    
  # 2. BÖLÜM: Our Team / Ekibimiz (YENİ YERİ: Direktörün Üstüne Taşındı)
  - block: markdown
    id: team
    content:
      title: '👥 Our Team / Ekibimiz'
      subtitle: 'The minds driving the research at SOHE LAB'
      text: |-
        #### **Director / Laboratuvar Direktörü**
        * **Assoc. Prof. Dr. Melike Eğer Aydoğmuş** (Hacettepe University)

        #### **Lab Coordinator / Laboravuvar Koordinatörü**
        * **Damla Gültekin Gökçeli, M.A.** - Email: [damlagultekin@hacettepe.edu.tr](mailto:damlagultekin@hacettepe.edu.tr)

        #### **Graduate Student Researchers / Lisansüstü Öğrenci Araştırmacılar**
        * **Cihangir Arkaç** * **Kübra Ceren Babaoğlu**

        #### **Undergraduate Student Researchers / Lisans Öğrenci Araştırmacılar**
        * **Şebnem Ünal** * **Abdulkerim Altuğ Koç** * **Kıymet Ayşegül Kardeş** * **Zeynep Sude Gürlesin** * **Zehra Nur Ayaz** * **Tuğçe Topçuoğlu** * **Tuana Yücel** * **Asya Çetin** * **Bilge Durak** * **Zeynep Yüksel** * **Beyza Ekin Nigar**
    design:
      columns: '1'
    
  # 3. BÖLÜM: Director / Direktör Profil Alanı (YENİ YERİ: Ekibimizin Altına Kaydırıldı)
  - block: resume-biography-3
    id: about
    content:
      username: me
      text: ''
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  # 4. BÖLÜM: Publications / Öne Çıkan Yayınlar
  - block: collection
    id: papers
    content:
      title: Featured Publications / Öne Çıkan Yayınlar
      count: 0
      filters:
        folders:
          - publications
        featured_only: false
    design:
      view: article-grid
      columns: '2'

  # 5. BÖLÜM: Projects / Projeler (Ziyaretçiyi yönlendiren kurumsal butonlu alan)
  - block: markdown
    id: projects
    content:
      title: '🔬 Projects / Projeler ve Araştırmalar'
      subtitle: 'Ongoing and completed research projects at SOHE LAB'
      text: |-
        At **SOHE LAB**, we manage national and international research projects utilizing advanced psychological methodologies, tracking psychological health, stigma, and self-compassion constructs. 

        To explore our active grants, cross-cultural studies, and completed research pipelines, please visit our dedicated projects portal.

        ---

        **SOHE LAB** bünyesinde, ileri psikoloji metodolojilerini kullanarak damgalama, psikolojik ihtiyaçlar ve öz-şefkat gibi temaları inceleyen ulusal ve uluslararası projeler yürütmekteyiz. Aktif fonlarımızı, kültürlerarası çalışmalarımızı ve tamamlanan araştırma projelerimizi incelemek için lütfen projeler portalımızı ziyaret edin.

        <br>

        <a href="projects/" style="background-color: #007bff; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; font-weight: bold; display: inline-block;">Explore Projects / Projeleri İncele ➡️</a>
    design:
      columns: '1'

  # 6. BÖLÜM: SOHE Life / Labdan Kareler (Galeri)
  - block: collection
    id: news
    content:
      title: SOHE Life / Labdan Kareler
      subtitle: ''
      text: ''
      page_type: blog
      count: 10
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card

  # 7. BÖLÜM: Talks / Etkinlikler ve Konuşmalar
  - block: collection
    id: talks
    content:
      title: Talks & Events / Etkinlikler ve Konuşmalar
      filters:
        folders:
          - events
    design:
      view: card

  # 8. BÖLÜM: Join Us / Bize Katılın
  - block: markdown
    id: join
    content:
      title: '🚀 Join Us / Bize Katılın'
      subtitle: 'Become a part of the SOHE LAB research team'
      text: |-
        <table style="width:100%; border:none; border-collapse:collapse;">
          <tr>
            <!-- İNGİLİZCE KATILIM METNİ -->
            <td style="width:50%; padding-right:25px; vertical-align:top; border:none; line-height:1.6; text-align:justify;">
              **SOHE LAB** is always delighted to welcome passionate and highly motivated undergraduate and graduate students into our research pipeline. Being a part of our team offers firsthand field and kitchen experience in literature reviews, experimental designs, advanced quantitative methodologies, data collection, and manuscript preparation. Researchers who are eager to specialize in social and health psychology domains—such as stigma, psychological needs, personality, motivation, cross-cultural differences, perfectionism, self-compassion, and emotion processes—and who hold an interest in mixed methods are welcome to join us as volunteer lab members. To be a volunteer, please email our Lab Coordinator Damla Gültekin Gökçeli via <a href="mailto:damlagultekin@hacettepe.edu.tr">damlagultekin@hacettepe.edu.tr</a>. Those who wish to complete their Master's or Ph.D. studies under the supervision of the Director as an official member of the lab may reach out via the lab director’s email address at <a href="mailto:melike.aydogmus@hacettepe.edu.tr">melike.aydogmus@hacettepe.edu.tr</a>.
            </td>
            <!-- TÜRKÇE KATILIM METNİ -->
            <td style="width:50%; padding-left:25px; vertical-align:top; border-left:1px solid #e3e3e3; border-top:none; border-right:none; border-bottom:none; line-height:1.6; text-align:justify;">
              **SOHE LAB** bünyesinde, araştırma mutfağımıza dahil olacak tutkulu, motivasyonu yüksek lisans ve lisansüstü öğrencileriyle çalışmaktan her zaman mutluluk duyuyoruz. Ekibimizde yer almak; literatür taraması, deneysel desenler, ileri nicel yöntemler, veri toplama ve makale hazırlama süreçlerinde doğrudan saha ve mutfak deneyimi kazanma fırsatı sunar. Sosyal ve sağlık psikolojisi temalarında (damgalama, psikolojik ihtiyaçlar, kişilik, motivasyon, kültürler arası farklılıklar, mükemmeliyetçilik, öz-şefkat, duygu süreçleri) uzmanlaşmak isteyen ve karma yöntemlere ilgi duyan araştırmacılar, laboratuvar koordinatörümüz Damla Gültekin Gökçeli'ye <a href="mailto:damlagultekin@hacettepe.edu.tr">damlagultekin@hacettepe.edu.tr</a> adresi üzerinden e-posta göndererek gönüllü laboratuvar üyeleri olarak bize dahil olabilirler. Direktör danışmanlığında yüksek lisans ve doktora çalışmalarını laboratuvarın resmi bir üyesi olarak tamamlamak isteyenler ise direktörün <a href="mailto:melike.aydogmus@hacettepe.edu.tr">melike.aydogmus@hacettepe.edu.tr</a> adresli e-postası aracılığıyla iletişim kurabilirler.
            </td>
          </tr>
        </table>
    design:
      columns: '1'
---
