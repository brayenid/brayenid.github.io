<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Document</title>
  <script src='js/jquery-3.2.1.min.js'></script>
<style type="text/css">
  body {background: #444;font-family: arial}
a:link {text-decoration: none;font-family: arial}
.bungkus {top:0;left:0;position:fixed;text-align:center;width: 10%;background: #444;height: 20px}
.nonehover{font-size:11px;box-shadow:1px 1px 5px rgba(0,0,0,0.7);display: inline-block;color:#666;text-align: center;height: 40px;line-height: 40px;position:relative;background:#333;padding:0;margin:0;text-align:left;width:100%}
.tombol{box-shadow:1px 1px 5px rgba(0,0,0,0.7);border-bottom:1px solid #555;display: inline-block;color:#fff;text-align: center;height: 40px;line-height: 40px;position:relative;background:#333;color:#fff;padding:0;margin:0;text-align:left;width:100%;transition:all .3s ease-out}
.tombol:last-child {border-bottom: 0}
.tombol a {font-family: arial;text-transform: uppercase;}
.tombol:before {content:"";position:absolute;bottom:0;width:0;height:8%;background:#4fafe9;transition:all .6s ease-in;}
.tombol:after {content:"";position:absolute;bottom:0;right:0;width:2%;height:0;background:#4fafe9;transition:.8s}
.tombol:nth-child(2):after{background: #ee352a}
.tombol:nth-child(2):before{background: #ee352a}
.tombol:nth-child(3):after{background: #1abc9c}
.tombol:nth-child(3):before{background: #1abc9c}
.tombol:nth-child(4):after{background: #dd352b}
.tombol:nth-child(4):before{background: #dd352b}
.tombol:hover:before {width:100%;}
.tombol:hover:after{height:100%;}
.tombol a{padding:0 0 0 20px;display:block;position:relative;line-height:42px;color:#fff;text-decoration:none;transition:all .3s ease-out}
.tombol a:hover {color:#fff;}
.tombol span{float:right;height:42px;line-height:42px;width:42px;text-align:center;display:inline-block;background:#4fafe9;color:#FFF;position:absolute;top:0;right:0;z-index:2}
.paragraf {transition:2s;width: 40%;margin: auto;margin-bottom:20px;margin-top:10px;background: #555;box-shadow: 1px 1px 5px rgba(0,0,0,0.2);padding: 4px 20px}
.paragraf.muncul {font-size: .9em;transform:translate(0,1220px);opacity: 0}
.paragraf h1 {color:#fff;text-align: center;font-family: arial}
.paragraf p {color:#fff;font-family: arial;font-size: 14px;line-height: 1.3em;text-align: justify;}
.bungkusanpar{width: 100%}
.sidebar {transition:all 1s;opacity:0;overflow:hidden;height:60px;box-shadow:1px 1px 5px rgba(0,0,0,0.2);background: #555;float: right;position: fixed;top:10px;right: 80px;width: 300px;}
.sidebar.muncul {opacity: 1;width: 80%;height: 200px}
.sidebar li {margin-right:5px;display: inline-block;list-style: none;list-style-position: outside}
.sidebar li:first-child {margin-left: -29px}
.sidebar li a {color:#fff;padding:10px;background: #666}
.sidebar p {line-height:1.3em;transition:opacity 1s 1s;text-align: justify;padding: 20px;color: #fff;font-size: 14px;opacity: 0}
.sidebar.muncul p {opacity: 1}
</style>
</head>
<body>
  <div class="bungkus">
    <div class="daftarmenu">
      <span class="tombol"><a class='page-scroll' href="#paragraf1">Paragraf 1</a></span>
      <span class="tombol"><a class='page-scroll' href="#paragraf2">paragraf 2</a></span>
      <span class="tombol"><a class='page-scroll' href="#paragraf3">paragraf 3</a></span>
      <span class="tombol"><a style='cursor:pointer' onclick='buka()'>+ Sidebar</a></span>
      <span class="nonehover" style="text-align: center;">BrayenID Project</span>
    </div>
  </div>
<div class='bungkusanpar'>
<section id="paragraf1" class="paragraf">
<h1>Paragraf 1</h1>
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Officiis perspiciatis, animi ullam provident odio itaque sunt ex laudantium deleniti tempore iusto doloribus dignissimos, facilis consectetur est porro eos accusantium deserunt, optio tempora. Eos commodi saepe numquam molestiae. Omnis, asperiores, ipsa? Beatae, cupiditate officia, saepe sed voluptas dignissimos molestias quam impedit numquam sint nemo quod esse ullam optio fuga aperiam facere quasi. Dolorum quibusdam tempora, nostrum quo eligendi asperiores, illum odit, aperiam reprehenderit mollitia eaque facere cumque, consectetur veritatis laboriosam perferendis ad deleniti provident assumenda fugit obcaecati? Eius, laboriosam esse vitae quae et optio reprehenderit ipsam in deserunt nulla ipsum iure.
  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ducimus explicabo, reiciendis, harum accusamus optio tempora asperiores dolores sunt earum placeat temporibus quis distinctio, ad magnam. Facere id quaerat quos consequuntur, eius quasi tenetur distinctio facilis dolores sit quidem magnam voluptatem sed tempora, repellendus eos deserunt totam reiciendis illo explicabo officiis. Recusandae nam molestiae omnis quas dolore natus sit dicta, ullam aut repellat fugit sunt, voluptatibus illo voluptatum repellendus, deserunt maiores accusantium earum laborum magnam quam. Hic iusto repudiandae excepturi dolorum, in reprehenderit omnis minima est reiciendis culpa libero non doloribus! Eum exercitationem ratione voluptatibus, dolorum nobis quia omnis ad quidem expedita aliquam. Praesentium, tempore sint aperiam, a vero saepe earum molestias amet nulla, doloribus quae qui rem repellat illo esse eveniet. Itaque, aspernatur optio inventore molestiae iste ad! Possimus corporis optio, dicta aperiam ipsa earum dolorum asperiores nisi fugit voluptatum accusantium, beatae alias tempora porro accusamus quo nihil dignissimos perspiciatis omnis nobis fugiat autem? Quia, accusamus velit! Ipsum nihil reprehenderit quas asperiores, dolorum laborum totam maxime porro saepe sint numquam vel, labore neque odio quia. Nostrum, inventore temporibus delectus, voluptates numquam sed repellendus molestias est ad ducimus, minus quidem eligendi, voluptatem. Ipsum, nemo, suscipit! Accusamus officia magni suscipit voluptates minima.</p>
</section>
<section id="paragraf2" class="paragraf">
<h1>Paragraf 2</h1>
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Officiis perspiciatis, animi ullam provident odio itaque sunt ex laudantium deleniti tempore iusto doloribus dignissimos, facilis consectetur est porro eos accusantium deserunt, optio tempora. Eos commodi saepe numquam molestiae. Omnis, asperiores, ipsa? Beatae, cupiditate officia, saepe sed voluptas dignissimos molestias quam impedit numquam sint nemo quod esse ullam optio fuga aperiam facere quasi. Dolorum quibusdam tempora, nostrum quo eligendi asperiores, illum odit, aperiam reprehenderit mollitia eaque facere cumque, consectetur veritatis laboriosam perferendis ad deleniti provident assumenda fugit obcaecati? Eius, laboriosam esse vitae quae et optio reprehenderit ipsam in deserunt nulla ipsum iure.
  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dignissimos facilis nulla iste ducimus quo. Distinctio fugiat, porro fugit sint, maiores in, impedit nihil exercitationem maxime itaque aperiam explicabo officia aliquid nesciunt, alias consequuntur quae? Ducimus assumenda quisquam voluptates dolorum ab earum debitis iure saepe facere amet obcaecati temporibus perferendis cumque nam, rerum, consequuntur velit nulla nobis voluptatibus adipisci eum iusto at distinctio commodi quod! Quasi hic possimus adipisci id quia dolorum illum error numquam, aliquid quis suscipit, officiis natus at. Dolores quis iusto deserunt eveniet, delectus. Aperiam iure, cumque porro aut sed soluta quia ipsam nemo optio, in provident veritatis.</p>
</section>
<section id="paragraf3" class="paragraf">
<h1>Paragraf 3</h1>
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Officiis perspiciatis, animi ullam provident odio itaque sunt ex laudantium deleniti tempore iusto doloribus dignissimos, facilis consectetur est porro eos accusantium deserunt, optio tempora. Eos commodi saepe numquam molestiae. Omnis, asperiores, ipsa? Beatae, cupiditate officia, saepe sed voluptas dignissimos molestias quam impedit numquam sint nemo quod esse ullam optio fuga aperiam facere quasi. Dolorum quibusdam tempora, nostrum quo eligendi asperiores, illum odit, aperiam reprehenderit mollitia eaque facere cumque, consectetur veritatis laboriosam perferendis ad deleniti provident assumenda fugit obcaecati? Eius, laboriosam esse vitae quae et optio reprehenderit ipsam in deserunt nulla ipsum iure.
  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Laudantium, facere dolor eaque in ut atque, officiis maiores qui eum harum enim tempora nulla praesentium, cumque placeat velit hic et minus blanditiis repellat asperiores eveniet eius! Necessitatibus magni beatae explicabo officia asperiores, vel possimus illum! Quam aliquam quae, mollitia sunt! Nesciunt voluptates, sapiente error veritatis voluptas saepe aperiam tenetur sed, corporis excepturi? Vero, saepe, doloribus! Obcaecati quam odio optio distinctio modi ipsam, magni, similique molestias vel voluptatibus adipisci veritatis in doloremque molestiae placeat deleniti veniam qui ullam nulla nobis esse. Corrupti nesciunt officiis vitae, fugiat accusamus blanditiis ducimus iusto, doloribus eos dolorem, nisi aspernatur! Officia ad ipsam accusantium, itaque quibusdam soluta ex et culpa. Sapiente quia deleniti in non natus eius, sunt quod. Accusantium id, ratione at corporis maiores nam sunt dicta sit perferendis incidunt doloremque exercitationem quam veniam explicabo magni distinctio nemo, asperiores ut beatae necessitatibus eveniet. Minima fugit distinctio pariatur totam, consequuntur, nulla laborum sint neque temporibus nesciunt laboriosam nam eligendi alias explicabo quia debitis veniam voluptate numquam illum.</p>
</section>
<section class="sidebar" id="sidebar">
  <ul>
    <li><a style="cursor: pointer;" onclick="buka()">Home</a></li>
    <li><a href="http://www.brayen.web.id">Author</a></li>
    <li><a href="http://">Tutorial</a></li>
  </ul>
<p>Ini hanyalah sedikit tutorial penggunaan jQuery dan CSS. Yang saya gunakan sebenarnya 90% CSS, untuk menguasai jQuery lebih jauh saya butuh waktu dan banyak proyek tentang jQuery supaya dapat mengenal jQuey lebih jauh. Tidak ada yang spesial dari transisi-transisi CSS yang saya gunakan, hanya yang ringan-ringan saja</p>
</section>
</div>
<script src='https://rawgit.com/brayenid/borneoscript3/master/jquery.easing.1.3.js'></script>
<script>
  //Scroll to section ID
$('.page-scroll').on('click',function(e){

  var href = $(this).attr('href');
  
  var bungkusanhref = $(href);

  $('html, body').animate({
    scrollTop: bungkusanhref.offset().top - 50}, 2000, 'easeOutExpo');
e.preventDefault()
});
function buka(){
  $('.sidebar,.sidebar p').toggleClass('muncul')
  $('.paragraf').toggleClass('muncul')
}
</script>
</body>
</html>
