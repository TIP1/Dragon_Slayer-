# Dragon_Slayer-
Game.js
var slaying=true;
var youHit=Math.floor(Math.random() * 2);
var damageThisRound=Math.floor(Math.random()*5 + 1);
var totalDamage=0;
while(slaying){
     if(youHit===true){
         console.log('nice!');
         totalDamage += damageThisRound;
         if(totalDamage>=4){
             console.log('You win!');
             slaying=false;
         }else{
             
             youHit=Math.floor(Math.random() * 2);
             }
         }
         else{
             console.log('Defeat!');}
             
    
   
    slaying=false
    }


