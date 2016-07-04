# Sass-Boilerplate


A simple sass boilerplate with Bootstrap and Respond-to Mixing. The boilerplate contains a bunch of useful mixins.

## Alerts 

Creates Alert/Button styles.

### Usage

```scss

.alert{
  @include alert-variant(#f36,darken(#f36,5%),#333);
}
===============================Output==========================
.alert {
  background-color: #ff3366;
  border-color: #ff1a53;
  color: #333333;
}
.alert a {
  color: #1a1a1a;
}

```

## Animate

It's the sass version of animate.css

## Background Trasparent

The background transparent property with fallback for IE

### Usage

```scss
 =============================Use==================================
 .backgroundtransparent{
   @include backgroundTransparent(#f36,.5);
 }
 ===============================Output==============================
 .backgroundtransparent {
   background-color: rgba(255, 51, 102, 0.5);
   filter: progid:DXImageTransform.Microsoft.gradient(startColorstr=#80FF3366,endColorstr=#80FF3366);
 }
 :root .backgroundtransparent {
   filter: none;
 }
 ===================================================================

 ```

 ## Border radius

 ### Usage

 ```scss
	.bordered_div{
		@include border-radius(5px);
	}

 ```

