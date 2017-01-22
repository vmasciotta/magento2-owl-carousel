# Magento 2 Owl Carousel

This simple module allows You to use OwlCarousel following the Magento way.

## How to install

**This module is now available through *Packagist* ! You don't need to specify the repository anymore.**

Add the following lines into your composer.json
 
```
...
"require":{
    ...
    "vmasciotta/magento2-owl-carousel":"^1.0.0"
 }
```

Then type the following commands from your Magento root:

```
$ composer update
$ ./bin/magento cache:disable
$ ./bin/magento module:enable Vmasciotta_OwlCarousel
$ ./bin/magento setup:upgrade
$ ./bin/magento cache:enable
```
 or simply type this commands in your magento root directory:
  ```
   $ composer require vmasciotta/magento2-owl-carousel

   $ ./bin/magento cache:disable
   $ ./bin/magento module:enable Vmasciotta_OwlCarousel
   $ ./bin/magento setup:upgrade
   $ ./bin/magento cache:enable
  ```


## How to use
 
 Using `data-mage-init`:
  
 ```html
 <div id="demos">
     <div class="owl-carousel owl-theme" data-mage-init='{ "OwlCarousel": {"loop":true,"margin":10,"nav":true, "dots":false, "autoplay":true} }'>
         <div class="item"><h4>1</h4></div>
         <div class="item"><h4>2</h4></div>
         <div class="item"><h4>3</h4></div>
         <div class="item"><h4>4</h4></div>
         <div class="item"><h4>5</h4></div>
         <div class="item"><h4>6</h4></div>
         <div class="item"><h4>7</h4></div>
         <div class="item"><h4>8</h4></div>
         <div class="item"><h4>9</h4></div>
         <div class="item"><h4>10</h4></div>
         <div class="item"><h4>11</h4></div>
         <div class="item"><h4>12</h4></div>
     </div>
 </div>
 ```
 
 Using `text/x-magento-init`:
 
 ```html
 <div id="demos">
      <div class="owl-carousel owl-theme">
          <div class="item"><h4>1</h4></div>
          <div class="item"><h4>2</h4></div>
          <div class="item"><h4>3</h4></div>
          <div class="item"><h4>4</h4></div>
          <div class="item"><h4>5</h4></div>
          <div class="item"><h4>6</h4></div>
          <div class="item"><h4>7</h4></div>
          <div class="item"><h4>8</h4></div>
          <div class="item"><h4>9</h4></div>
          <div class="item"><h4>10</h4></div>
          <div class="item"><h4>11</h4></div>
          <div class="item"><h4>12</h4></div>
      </div>
  </div>
 
 <script type="text/x-magento-init">
     {
         "#owl-demo": {
             "OwlCarousel": {
                 "loop":true,
                 "margin":10,
                 "nav":true,
                 "autoplay":true,
                 "dots":false
             }
         }
     }
 </script>
 ```
 Using imperative notation:

 ```html
 <div id="demos">
       <div class="owl-carousel owl-theme">
           <div class="item"><h4>1</h4></div>
           <div class="item"><h4>2</h4></div>
           <div class="item"><h4>3</h4></div>
           <div class="item"><h4>4</h4></div>
           <div class="item"><h4>5</h4></div>
           <div class="item"><h4>6</h4></div>
           <div class="item"><h4>7</h4></div>
           <div class="item"><h4>8</h4></div>
           <div class="item"><h4>9</h4></div>
           <div class="item"><h4>10</h4></div>
           <div class="item"><h4>11</h4></div>
           <div class="item"><h4>12</h4></div>
       </div>
   </div>

 <script type="text/javascript">
    require([
            'jquery',
            'OwlCarousel'
        ], function ($) {
            $('.owl-carousel').owlCarousel({
                loop:true,
                margin:10,
                nav:true,
                autoplay:true,
                dots:false
            })
        });
<script>
 ```

 
