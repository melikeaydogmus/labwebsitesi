---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  # 1. BÖLÜM: SOHE LAB Giriş, İki Fotoğraf (.jpeg) ve İki Kolonlu Metin Düzeni
  - block: markdown
    id: sohelab
    content:
      title: '🔬 SOHE LAB / Social & Health Psychology Lab'
      subtitle: ''
      text: |-
        <div style="display: flex; gap: 20px; margin-bottom: 30px; width: 100%;">
          <div style="flex: 1; text-align: center;">
            <img src="media/lab-1.jpeg" alt="SOHE LAB Team" style="width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); object-fit: cover;">
          </div>
          <div style="flex: 1; text-align: center;">
            <img src="media/lab-2.jpeg" alt="SOHE LAB Research" style="width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); object-fit: cover;">
          </div>
        </div>

        <table style="width:100%; border:none; border-collapse:collapse;">
          <tr>
            <td style="width:50%; padding-right:25px; vertical-align:top; border:none; line-height:1.6;">
              Welcome to the official portal of **SOHE LAB**. Directed by Assoc. Prof. Dr. Melike Eğer Aydoğmuş at Hacettepe University, our laboratory investigates the psychological mechanisms underlying human behavior, social attitudes, and well-being.
              <br><br>
              Our primary research lines focus on the dynamics of **stigma, perfectionism, self-compassion, self-determination theory (psychological needs and motivation), and emotion processing**. Utilizing advanced quantitative methodologies, path analyses, structural equation modeling (SEM), and mixed-methods research designs, SOHE LAB aims to bridge universal psychological constructs with profound cultural dynamics. We strive to generate scientific evidence that informs public health, shapes educational interventions, and guides policy-making for vulnerable groups.
            </td>
            <td style="width:50%; padding-left:25px; vertical-align:top; border-left:1px solid #e3e3e3; border-top:none; border-right:none; border-bottom:none; line-height:1.6;">
              **SOHE LAB Araştırma Dünyasına Hoş Geldiniz.** Hacettepe Üniversitesi bünyesinde Doç. Dr. Melike Eğer Aydoğmuş direktörlüğünde faaliyet gösteren laboratuvarımızda; insan davranışının, sosyal tutumların ve psikolojik iyi oluşun arkasındaki mekanizmaları inceliyoruz.
              <br><br>
              Temel araştırma alanlarımız arasında **damgalama (stigma), mükemmeliyetçilik, öz-şefkat, öz-belirleme kuramı (psikolojik ihtiyaçlar ve motivasyon) ve duygu işleme süreçleri** yer almaktadır. İleri kantitatif yöntemler, yol analizi, yapısal eşitlik modellemesi (SEM) ve karma yöntemli desenler kullanan SOHE LAB, evrensel psikoloji yaklaşımlarını kültürel dinamiklerle harmanlamayı ve toplumsal refaha katkı sunacak bilimsel çıktılar üretmeyi amaçlar.
            </td>
          </tr>
        </table>
    design:
      columns: '1'
    
  # 2. BÖLÜM: Director / Direktör Profil Alanı
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

  # 3. BÖLÜM: Our Team / Ekibimiz
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
---
