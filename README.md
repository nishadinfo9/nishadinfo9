Write a function called countVowels that takes a string as an argument and returns the number of vowels (a, e, i, o, u) in the string. Ignore case sensitivity.




function countVowels(str) { 

    let count = 0;

    for (let i = 0; i < str.length; i++) {

        if (str[i] === 'a' || str[i] ==='e' || str[i] === 'i' || str[i] === 'o' || str[i] === 'u') {
            count++
        }
    }
        return count;
    }   

console.log(countVowels("Javascript"));
