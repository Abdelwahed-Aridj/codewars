var countBits = function(n) {
   // create an array with split
   const array = (n).toString(2).split('');
   
   // make a sum with the array and make the index a Number
   const result = array.reduce((sum, num) => sum + Number(num), 0);
   
   return result;
};