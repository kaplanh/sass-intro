#  Sass Intro


![sasintro](https://github.com/kaplanh/sass-intro/assets/101884444/013aef79-20b2-445d-8d18-6229de6143b0)
[Live Link](https://kaplanh.github.io/sass-intro/)
## Description

Project aims to create website site using sass.

## Problem Statement

- Your company has recently started on a project that aims to create a company website page. So you and your colleagues have started to work on the project.

## Project Skeleton 

```
008-Sass-intro(folder)
|
        |----readme.md               
        |----images  
        |----index.html  
        |----css (folder)   
              |----style.css  
              |----style.css.map  
        |----scss (folder)     
              |----_variables.scss 
              |----_reset.scss               
              |----main.scss  
        
```
## Objective

Ma

### At the end of the project, following topics are to be covered;

- HTML 

- CSS

- Sass / Scss

### At the end of the project, developers will be able to;

- improve coding skills within HTML, CSS & Sass/Scss

- use git commands (push, pull, commit, add etc.) and Github as Version Control System.





  
  <body>
	  <header>
      <h1 class="heading">SCSS</h1>
    </header>
  <h2>CSS Preprosessorler</h2>
  <p>CSS preprosessorler, CSS'in geliştirilmiş ve genişletilmiş versiyonlarını oluşturmak için kullanılan araçlardır. Bu araçlar, CSS yazımını daha etkili, modüler ve yönetilebilir hale getirmek için çeşitli özellikler sunarlar. CSS preprosessorler, daha sonra CSS'e derlenerek tarayıcılar tarafından anlaşılabilen düz CSS koduna dönüştürülür.</p>
  

CSS preprosessorlerin sağladığı temel özellikler şunlardır:
<ul>
<li><strong>Değişkenler:</strong> Değerleri depolayarak tekrar kullanılabilirlik sağlar. Değişkenler, stil kodunda kullanılan renkler, fontlar, uzunluklar gibi değerleri tek bir yerden yönetmeyi ve kolayca değiştirmeyi sağlar.</li>

<li><strong>Nesting:</strong> CSS kurallarını iç içe geçmiş bir yapıda yazmayı sağlar. Bu sayede, karmaşık veya derinlemesine seçicilere gerek kalmadan daha düzenli ve okunabilir bir stil kodu oluşturulabilir.</li>

<li><strong>Mixinler:</strong> Tekrar kullanılabilir stil bloklarını tanımlayarak stil özelliklerini kolayca eklemeyi sağlar. Mixinler, stil kodunda kullanılan karmaşık veya tekrar eden stil tanımlarını birleştirmek için kullanılır.</li>

<li><strong>Partials ve @import:</strong> Büyük stil dosyalarını daha küçük parçalara bölebilir ve yönetilebilir hale getirebilir. Partials, stil kodunun farklı dosyalara bölünerek daha iyi bir organizasyon sağlamasını sağlar. @import ise bu parçaları ana stil dosyasına dahil etmek için kullanılır.</li>

<li><strong>Operatörler:</strong> Matematiksel işlemleri ve renk manipülasyonunu destekler. Bu sayede, stil kodunda hesaplamalar yapmak veya renkleri manipüle etmek daha kolay hale gelir.</li>

<li><strong>Koşullu ifadeler:</strong> If-else yapısı ile stil kodunu kontrol etmenizi sağlar. Belirli koşullara göre farklı stil tanımları yapabilir veya farklı değerleri kullanabilirsiniz.
</li>
</ul>
<p>CSS preprosessorler, stil kodunun daha iyi bir organizasyon ve daha kolay bir şekilde yazılmasını sağlayarak geliştirme sürecini daha verimli hale getirir. Popüler CSS preprosessorler arasında SCSS (Sassy CSS), Less ve Stylus bulunmaktadır. Bu araçlar, web geliştiricilere CSS yazımını geliştirmek ve daha etkili bir şekilde çalışmak için güçlü araçlar sunarlar.</p>
<h2>SCSS Nedir?</h2>
  <p>SCSS, Sassy CSS'nin kısaltmasıdır ve CSS'e daha fazla özellik ve esneklik ekleyen bir CSS preprosessordür.</p>
  <p>SCSS kullanmanın bazı avantajları şunlardır:</p>
  <ul>
    <li>Değişkenler: Değerleri depolayarak tekrar kullanılabilirlik sağlar.</li>
    <li>Nesting: İç içe geçmiş yapılar oluşturarak kodu daha okunabilir hale getirir.</li>
    <li>Mixins: Tekrar kullanılabilir kod bloklarını tanımlayarak stil özelliklerini kolayca ekleyebilirsiniz.</li>
    <li>Partials ve @import: Büyük stil dosyalarını daha küçük parçalara bölebilir ve yönetilebilir hale getirebilirsiniz.</li>
    <li>Operatörler: Matematiksel işlemleri ve renk manipülasyonunu destekler.</li>
    <li>Koşullu ifadeler: If-else yapısı ile stil kodunu kontrol etmenizi sağlar.</li>
  </ul>
  <p>SCSS dosyaları, CSS dosyalarına dönüştürülmeden önce SCSS yorumlanır. Bu, daha gelişmiş ve etkili bir şekilde stil kodu yazmanıza olanak tanır.</p>
   <h2>SASS/SCSS Terminal Komutları</h2>
  <p>SASS, komut satırı üzerinden çalışabilen bir CSS preprosessor'dür. İşte bazı SASS terminal komutları:</p>
  <ul>
    <li><strong>sass --watch input.scss:output.css</strong>: `input.scss` dosyasını izleyerek her değişiklikte otomatik olarak `output.css` dosyasını oluşturur.</li>
    <li><strong>sass input.scss output.css</strong>: `input.scss` dosyasını derleyerek `output.css` dosyasını oluşturur.</li>
    <li><strong>sass --watch input-dir:output-dir</strong>: `input-dir` klasörünü izleyerek her değişiklikte otomatik olarak `output-dir` klasöründe CSS dosyalarını oluşturur.</li>
    <li><strong>sass --style compressed input.scss output.css</strong>: `input.scss` dosyasını derleyerek sıkıştırılmış (`compressed`) bir `output.css` dosyası oluşturur.</li>
  </ul>
  <p>Bu komutlar, SASS dosyalarınızı derlemek, izlemek ve çıktı almak için kullanılabilir. Komutları terminalde çalıştırarak SASS işlemlerini gerçekleştirebilirsiniz.</p>
  <pre><code>
    sass --watch input.scss:output.css
    sass input.scss output.css
    sass --watch input-dir:output-dir
    sass --style compressed input.scss output.css
  </code></pre>

    <div class="content">
        <h2>Değişkenler</h2>
    <p>Değişkenler, stil değerlerini depolamak ve tekrar kullanmak için kullanılır.</p>
    <pre><code>
$primary-color: #007bff;
$secondary-color: #6c757d;

.box {
  color: $primary-color;
  background-color: $secondary-color;
}
    </code></pre>
    <h2>Nesting (Yerleştirme)</h2>
    <p>Nesting, iç içe geçmiş stil kuralları oluşturmak için kullanılır.</p>
    <pre><code>
.box {
  width: 200px;
  height: 200px;

  p {
    color: #333;
  }

  a {
    text-decoration: none;
    &:hover {
      color: blue;
    }
  }
}
    </code></pre>
    <h2>BEM Notasyonu ve SCSS Nesting Örneği</h2>
    <p>BEM notasyonu ile SCSS kullanarak class isimlerini birleştirebilir ve daha düzenli bir CSS kodu elde edebilirsiniz. Bu, kodunuzun daha okunabilir ve bakımı daha kolay hale gelmesine yardımcı olur.</p>
<pre><code>
    &lt;span class="block"&gt;
        &lt;span class="block__element"&gt;
            &lt;span class="block__element--modifier"&gt;&lt;/span&gt;
        &lt;/span&gt;
    &lt;/span&gt;

  .block {
  background-color: #f5f5f5;
  padding: 10px;

  &__element {
    // Element özellikleri

    &--modifier {
        // Modifier özellikleri
    }
  }

  
}
  </code></pre>
      <h2>Mixin</h2>
      <p>
        Mixin, tekrar eden stil kodlarını yeniden kullanmak için kullanılır.
      </p>
      <pre><code>
@mixin box-shadow($x, $y, $blur, $color) {
  box-shadow: $x $y $blur $color;
}

.box {
  @include box-shadow(0px, 0px, 5px, rgba(0, 0, 0, 0.3));
}
    </code></pre>
<h2>Include</h2>
    <p>Include, mixin'leri stil koduna dahil etmek için kullanılır.</p>
    <pre><code>
@mixin box-shadow($x, $y, $blur, $color) {
  box-shadow: $x $y $blur $color;
}

.box {
  @include box-shadow(0px, 0px, 5px, rgba(0, 0, 0, 0.3));
}
    </code></pre>
      <h2>Operatörler</h2>
      <p>
        Operatörler, matematiksel hesaplamaları ve değer manipülasyonunu yapmak
        için kullanılır.
      </p>
      <pre><code>
$box-width: 200px;
$box-height: 150px;
$padding: 20px;

.box {
  width: $box-width;
  height: $box-height;
  padding: $padding;
  margin: ($box-width + $padding) / 2;
}
    </code></pre>
      <div class="content">

    <h2>If-Else</h2>
    <p>If-Else, koşullu ifadeleri kullanarak stil kodunu kontrol etmek için kullanılır.</p>
    <pre><code>
$box-width: 200px;
$box-height: 150px;

.box {
  @if $box-width > $box-height {
    width: $box-width;
  } @else {
    height: $box-height;
  }
}
    </code></pre>
 <h2>For Döngüsü</h2>
      <p>
        For döngüsü, tekrarlayıcı bir yapı kullanarak stil kodlarını dinamik
        olarak oluşturmak için kullanılır.
      </p>
      <pre><code>
@for $i from 1 through 5 {
  .list-item-#{$i} {
    color: darken($primary-color, $i * 10%);
  }
}
    </code></pre>
    <h2>Partials ve @import</h2>
  <p>`Partials`, SCSS dosyalarını daha küçük parçalara bölmek için kullanılan bir yöntemdir. `@import` ise bu parçalara referans yapmamızı sağlar.</p>
  <pre><code>
    // _variables.scss
    // _mixins.scss
    // styles.scss
     _variables.scss, _mixins.scss ve styles.scss gibi dosya isimleri, partial dosyalarını temsil etmektedir.

    SCSS partial dosyaları _ ile başlar ve genellikle tek bir özelliği veya bir mixin'i içerir. 
    Bu partial dosyaları daha sonra ana stil dosyası olan styles.scss dosyasında @import ile referans alınır.

    Örneğin, styles.scss dosyasında _variables.scss ve _mixins.scss dosyalarını import etmek istediğimizde şu şekilde yapabiliriz:
    @import 'variables';
    @import 'mixins';
  </code></pre>
    </div>
  </body>
</html>

## Notes

- You can use HTML and CSS with sass/scss to complete this project.



<p align="center"> ⌛<strong> Happy Coding </strong> ✍ </p>
