# Magento 2 Owl Carousel

This simple module allows You to use OwlCarousel following the Magento way.

Questo semplice modulo ti permetterà di usare OwlCarousel seguendo le linee guida di Magento.

## How to install

Add the following lines into your composer.json
 
```
...
"require":{
    ...
    "vmasciotta/magento2-owl-carousel":"1.0.0"
 },
 ...
 "repositories":[
     {"type": "vcs", "url":"git@github.com:vmasciotta/magento2-owl-carousel.git"}
 ]
```
 
Then type the following commands from your Magento root:

```
$ composer update
$ ./bin/magento cache:disable
$ ./bin/magento module:enable Vmasciotta_OwlCarousel
$ ./bin/magento setup:upgrade
$ ./bin/magento cache:enable
```
 
## How to use
 
 Using `data-mage-init`:
  
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
 
 Using `<script>` tag:
 
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
 
 