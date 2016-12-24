# Angular Owl Carousel - 2

Impl for [OwlCarousel2]


### Installation
```ssh
bower install angular-owl-carousel2
```


### Usage

```html
<ng-owl-carousel class="owl-theme" owl-items="items" owl-properties="properties">
    <div class="item"><h4>Free Item</h4></div>
    <div class="item" data-ng-repeat="item in items"><h4>{{$index}}</h4></div>
</ng-owl-carousel>
```
   [OwlCarousel2]: <https://github.com/OwlCarousel2/OwlCarousel2>