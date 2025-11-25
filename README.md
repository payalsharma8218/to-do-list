// implement promiseAll function
const p1=new Promise((resolve,reject)=>{
    resolve("promise successfully")
})
const p2=new Promise((resolve,reject)=>{
    resolve(2)
})
const p3=new Promise((resolve,reject)=>{
    resolve(6)
})
const p4=new Promise((resolve,reject)=>{
    resolve(7)
})
promiseAll([p1,p2,p3,p4]).then((res)=>{
    console.log(res);
})

//ye function implement karna hai 
