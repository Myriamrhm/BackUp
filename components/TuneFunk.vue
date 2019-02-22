<template>
    
</template>

<script defer>
// Les chansons
var GetDown = new Audio('http:\/\/cdn-preview-5.deezer.com\/stream\/c-5e1563919c3d6a9630b9029489b1805a-6.mp3')
var Boogie = new Audio('http:\/\/cdn-preview-f.deezer.com\/stream\/c-feca60d18748299cd6dbd6c16dc69355-5.mp3')
var Inferno = new Audio('http:\/\/cdn-preview-b.deezer.com\/stream\/c-bd7a93208d747c1a9d12ba0c5e1ce697-3.mp3')
var Fever = new Audio('http:\/\/cdn-preview-f.deezer.com\/stream\/c-f154f31d722b26d757064abc48e4e2d4-4.mp3')
var Rasputin = new Audio('http:\/\/cdn-preview-d.deezer.com\/stream\/c-de1dfba04a23297cf9a39c53aa0a59ba-4.mp3')
var September = new Audio('http:\/\/cdn-preview-9.deezer.com\/stream\/c-92794b97c54b527362ee418254c5ebab-4.mp3')
var Groove = new Audio('http:\/\/cdn-preview-f.deezer.com\/stream\/c-f3239d1b1e78396639b752004d5c8978-5.mp3')
var Freak = new Audio('http:\/\/cdn-preview-4.deezer.com\/stream\/c-4f9973c5da89068816a6085cc72314f5-4.mp3')
var Enough = new Audio('http:\/\/cdn-preview-0.deezer.com\/stream\/c-0aba38b899344f494e908cb6f9968f82-2.mp3')
var Silence = new Audio('http:\/\/cdn-preview-f.deezer.com\/stream\/c-f9ca315f3bf66995386dffe05b7b0cb8-2.mp3')
var TakeOnMe = new Audio('http:\/\/cdn-preview-e.deezer.com\/stream\/c-e817b793ead610762756f4f3a48dfcd9-11.mp3')
var NewOrder = new Audio('http:\/\/cdn-preview-7.deezer.com\/stream\/c-77ccd542c217cc66acdc0cd550cf4612-4.mp3')
// 

September.play()
September.addEventListener('ended', function(){
       GetDown.play()
   })
GetDown.addEventListener('ended', function(){
       Boogie.play()
   })
Boogie.addEventListener('ended', function(){
       Inferno.play()
   })
Inferno.addEventListener('ended', function(){
       Fever.play()
   })
Fever.addEventListener('ended', function(){
       Rasputin.play()
   })
Rasputin.addEventListener('ended', function(){
       Groove.play()
   })
Groove.addEventListener('ended', function(){
       Freak.play()
   })
Freak.addEventListener('ended', function(){
       Silence.play()
   })
Silence.addEventListener('ended', function(){
       NewOrder.play()
   })
NewOrder.addEventListener('ended', function(){
       TakeOnMe.play()
   })
TakeOnMe.addEventListener('ended', function(){
       Enough.play()
   })
</script>

<style>

</style>
