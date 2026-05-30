---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
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

  - block: markdown
    content:
      title: '🔬 SOHE LAB / Social & Health Psychology Lab'
      subtitle: ''
      text: |-
        Welcome to the official portal of **SOHE LAB**. Directed by Assoc. Prof. Dr. Melike Eğer Aydoğmuş at Hacettepe University, our laboratory investigates the psychological mechanisms underlying human behavior, social attitudes, and well-being. 

        Our primary research lines focus on the dynamics of **stigma, perfectionism, self-compassion, self-determination theory (psychological needs and motivation), and emotion processing**. Utilizing advanced quantitative methodologies, path analyses, structural equation modeling (SEM), and mixed-methods research designs, SOHE LAB aims to bridge universal psychological constructs with profound cultural dynamics. We strive to generate scientific evidence that informs public health, shapes educational interventions, and guides policy-making for vulnerable groups.

        ---

        **SOHE LAB Araştırma Dünyasına Hoş Geldiniz.** Hacettepe Üniversitesi bünyesinde Doç. Dr. Melike Eğer Aydoğmuş direktörlüğünde faaliyet gösteren laboratuvarımızda; insan davranışının, sosyal tutumların ve psikolojik iyi oluşun arkasındaki mekanizmaları inceliyoruz. Temel araştırma alanlarımız arasında **damgalama (stigma), mükemmeliyetçilik, öz-şefkat, öz-belirleme kuramı (psikolojik ihtiyaçlar ve motivasyon) ve duygu işleme süreçleri** yer almaktadır. İleri kantitatif yöntemler, yol analizi, yapısal eşitlik modellemesi (SEM) ve karma yöntemli desenler kullanan SOHE LAB, evrensel psikoloji yaklaşımlarını kültürel dinamiklerle harmanlamayı ve toplumsal refaha katkı sunacak bilimsel çıktılar üretmeyi amaçlar.
    design:
      columns: '1'

  - block: markdown
    id: team
    content:
      title: '👥 Our Team / Ekibimiz'
      subtitle: 'The minds driving the research at SOHE LAB'
      text: |-
        #### **Director / Laboratuvar Direktörü**
        * **Assoc. Prof. Dr. Melike Eğer Aydoğmuş** (Hacettepe University)

        #### **Lab Coordinator / Laboratuvar Koordinatörü**
        * **Damla Gültekin Gökçeli, M.A.** - Email: [damlagultekin@hacettepe.edu.tr](mailto:damlagultekin@hacettepe.edu.tr)

        #### **Graduate Student Researchers / Lisansüstü Öğrenci Araştırmacılar**
        * **Cihangir Arkaç** * **Kübra Ceren Babaoğlu**

        #### **Undergraduate Student Researchers / Lisans Öğrenci Araştırmacılar**
        * **Şebnem Ünal** * **Abdulkerim Altuğ Koç** * **Kıymet Ayşegül Kardeş** * **Zeynep Sude Gürlesin** * **Zehra Nur Ayaz** * **Tuğçe Topçuoğlu** * **Tuana Yücel** * **Asya Çetin** * **Bilge Durak** * **Zeynep Yüksel** * **Beyza Ekin Nigar**
    design:
      columns: '1'

  - block: markdown
    id: join
    content:
      title: '🚀 Join Us / Bize Katılın'
      subtitle: 'Become a part of the SOHE LAB research team'
      text: |-
        At **SOHE LAB**, we are always looking for passionate, motivated, and dedicated undergraduate and graduate students to join our research pipeline. Working with us offers hands-on experience in experimental designs, advanced quantitative methodologies, data collection, and manuscript preparation.

        **Who can apply?**
        * **Undergraduate Students:** Psychology or related disciplines who are eager to learn research processes and support active projects as volunteer researchers.
        * **Graduate Students (MA/PhD):** Researchers looking to specialize in social and health psychology constructs (stigma, perfectionism, self-compassion) with a strong background or interest in mixed methods.

        *Application periods generally open at the beginning of each academic semester. If you are interested in joining our team, please send your CV and a brief statement of purpose to our lab coordinator.*

        ---

        **SOHE LAB** bünyesinde, araştırma mutfağımıza dahil olacak tutkulu, motivasyonu yüksek lisans ve lisansüstü öğrencileriyle çalışmaktan her zaman mutluluk duyuyoruz. Ekibimizde yer almak; deneysel desenler, ileri kantitatif yöntemler, veri toplama ve makale hazırlama süreçlerinde doğrudan saha ve mutfak deneyimi kazanma fırsatı sunar.

        **Kimler Başvurabilir?**
        * **Lisans Öğrencileri:** Araştırma süreçlerini öğrenmeye hevesli, gönüllü araştırmacı olarak aktif projelere destek vermek isteyen psikoloji ve ilişkili bölümlerin öğrencileri.
        * **Lisansüstü Öğrencileri (Yüksek Lisans/Doktora):** Sosyal ve sağlık psikolojisi temalarında (damgalama, mükemmeliyetçilik, öz-şefkat) uzmanlaşmak isteyen ve karma yöntemlere ilgi duyan araştırmacılar.

        *Başvuru dönemleri genel olarak her akademik dönemin başında açılmaktadır. Ekibimizin bir parçası olmakla ilgileniyorsanız, özgeçmişinizi ve kısa bir niyet mektubunu lab koordinatörümüze e-posta yoluyla iletebilirsiniz.*
    design:
      columns: '1'

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

  - block: collection
    content:
      title: Recent Publications / Güncel Yayınlar
      text: ''
      count: 0
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Talks & Events / Etkinlikler ve Konuşmalar
      filters:
        folders:
          - events
    design:
      view: card

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
      spacing:
        padding: [0, 0, 0, 0]
---
