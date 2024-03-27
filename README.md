let a=0
let b=1
let n=10
console.log(a)
console.log(b)
for(i=2; i<n; i++)
{
    sum=a+b
    a=b
    b=sum
    console.log(sum)
}
