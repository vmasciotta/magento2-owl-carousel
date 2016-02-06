# Magento 2 Owl Carousel

Questo semplice modulo ti permetterà di usare OwlCarousel seguendo le linee guida di Magento.
 
## Esempio di utilizzo
 
 Usando `data-mage-init`:
  
 ```html
 
 <div id="owl-demo" data-mage-init='{
   "OwlCarousel":{
         "autoPlay": 3000,
         "items" : 4,
         "itemsDesktop" : [1199,3],
         "itemsDesktopSmall" : [979,3]
   }
 }
 '>
     <div class="item"><img src="http://owlgraphic.com/owlcarousel/demos/assets/owl1.jpg" alt="Owl Image"></div>
     <div class="item"><img src="http://owlgraphic.com/owlcarousel/demos/assets/owl2.jpg" alt="Owl Image"></div>
     <div class="item"><img src="http://owlgraphic.com/owlcarousel/demos/assets/owl3.jpg" alt="Owl Image"></div>
     <div class="item"><img src="http://owlgraphic.com/owlcarousel/demos/assets/owl4.jpg" alt="Owl Image"></div>
     <div class="item"><img src="http://owlgraphic.com/owlcarousel/demos/assets/owl5.jpg" alt="Owl Image"></div>
     <div class="item"><img src="http://owlgraphic.com/owlcarousel/demos/assets/owl6.jpg" alt="Owl Image"></div>
     <div class="item"><img src="http://owlgraphic.com/owlcarousel/demos/assets/owl7.jpg" alt="Owl Image"></div>
     <div class="item"><img src="http://owlgraphic.com/owlcarousel/demos/assets/owl8.jpg" alt="Owl Image"></div>
 </div>
 ```
 
 Usando il tag `<script>`:
 
 ```html
 <div id="owl-demo">
     <div class="item"><img src="http://owlgraphic.com/owlcarousel/demos/assets/owl1.jpg" alt="Owl Image"></div>
     <div class="item"><img src="http://owlgraphic.com/owlcarousel/demos/assets/owl2.jpg" alt="Owl Image"></div>
     <div class="item"><img src="http://owlgraphic.com/owlcarousel/demos/assets/owl3.jpg" alt="Owl Image"></div>
     <div class="item"><img src="http://owlgraphic.com/owlcarousel/demos/assets/owl4.jpg" alt="Owl Image"></div>
     <div class="item"><img src="http://owlgraphic.com/owlcarousel/demos/assets/owl5.jpg" alt="Owl Image"></div>
     <div class="item"><img src="http://owlgraphic.com/owlcarousel/demos/assets/owl6.jpg" alt="Owl Image"></div>
     <div class="item"><img src="http://owlgraphic.com/owlcarousel/demos/assets/owl7.jpg" alt="Owl Image"></div>
     <div class="item"><img src="http://owlgraphic.com/owlcarousel/demos/assets/owl8.jpg" alt="Owl Image"></div>
 </div>
 
 <script type="text/x-magento-init">
     {
         "#owl-demo": {
             "OwlCarousel": {
                 "autoPlay": 3000,
                 "items": 4,
                 "itemsDesktop": [1199, 3],
                 "itemsDesktopSmall": [979, 3]
             }
         }
     }
 </script>
 ```
 
 