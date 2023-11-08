# array-methods
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Array methods</title>
</head>

<body>



    <script>

        // //array methods
        // // length
         var a=[""]
         console.log(a.length);
        // //srting conversion
        var a=["prathyusha","yagna","rishita","varsha","pravalika"]
         console.log(a);
         a=a.toString()
         console.log(a);
        // //push......
        var a=["prathyusha","yagna","rishita","varsha","pravalika"]
         console.log(a.push("mark"));
        console.log(a);
        // //pop...........
        var a=["prathyusha","yagna","rishita","varsha","pravalika"]
         a.pop()
        console.log(a);
        // //unshift.........
        var a=["prathyusha","yagna","rishita","varsha","pravalika"]
         a.unshift("doddapuneni")
         console.log(a);
        // //shift
         var a=["prathyusha","yagna","rishita","varsha","pravalika"]
         a.shift()
         console.log(a);
        // //join
         var a=["prathyusha","yagna","rishita","varsha","pravalika"]
         a=(a.join("-"));
         console.log(a);
        // //delete------------------
         var a=["prathyusha","yagna","rishita","varsha","pravalika"]
         delete(a[2])
        console.log(a);
        // //splice
        var a=["prathyusha","yagna","rishita","varsha","pravalika"]
         a.splice(1,0,"prathyusha");
        console.log(a);
        a.splice(3,1,"srikanth")
         console.log(a);
        a.splice(2,4)
        console.log(a);





        // task-1
        var a=["yagna","prathyusha","rishita","doddapuneni"]
         b=""
        for(i=0;i<a.length;i++){
            if(i%2==0){
                  b+=(a[i]);  
            }
         }
        console.log(b);
        
        //task-2

         var a=["yagna","prathyusha","rishita","doddapuneni"];
        c=""
        for(i=0;i<a.length;i++){
        console.log(a[i]);
         for(b=0;b<a[i].length;b++){
        console.log(b);

        }
 }

         var a = ["yagna","prathyusha","rishita","doddapuneni"];
         for (i = 0; i < a.length; i++) {
             console.log(a[i]);
            for (b = 0; b < a[i].length; b++) {
                 if (b % 2 == 0) {
                    console.log((a[i][b]))
                    
                }
            }
        }



 var a=["prathyusha","rishita","yagna"]
 count=[]

for(i in a){
    v=0;
for(b in a[i]){
    v++
}
count.push(v)
 }
 console.log(count);

var a=["doddapuneni","prathyusha"]
d=[]
for(i=0;i<a.length;i++){
for(b=0;b<a[i].length;b++){
if(a[i][b]=="a"||a[i][b]=="e"||a[i][b]=="i"|a[i][b]=="o"||a[i][b]=="u" ){
     console.log(a[i][b]);
 d+=a[i][b]
 }
 }
}
console.log(d);
 console.log(d.length)




    </script>
</body>

</html>
